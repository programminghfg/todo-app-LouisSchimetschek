<script>
    export let todo;
    export let index;

    import { createEventDispatcher } from "svelte";

    const dispatch = createEventDispatcher();

    function triggerRemove() {
        console.log(index);
        dispatch("remove", index);
    }
  </script>
  
  <div class="todo-entry" class:done={todo.done}>
    <input
      type="checkbox"
      class="todo-done"
      bind:checked={todo.done}
      id={`checkbox_${index}`}
    />
    <label for={`checkbox_${index}`} class="todo-text">{todo.text}</label>
    <button class="delete-button" on:click={triggerRemove}>
      X
    </button>
  </div>
  
  <style>
  </style>
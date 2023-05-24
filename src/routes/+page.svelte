<!-- <script>
  export let name;
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Rubik+Pixels&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&display=swap');

  @font-face {
    font-family: 'RubikPixels-Regular';
    src: url(fonts/RubikPixels-Regular.woff);
  }

  @font-face {
    font-family: 'IBM Plex Mono', monospace;
    src: url(fonts/SF-Mono-Regular.woff);
  }

  * {
    box-sizing: border-box;
    font-family: 'IBM Plex Mono', monospace;
    background-color: rgb(255, 255, 255);
  }

  a {
    color: rgb(0, 0, 0);
    border-radius: 4px;
    position: relative;
    top: 2em;
    right: 100px;
    margin: auto;
    position: fixed;
  }

  .wrapper {
    display: grid;
    width: 800px;
    gap: 40px;
    margin: auto;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 75px 80px 300px 100px 150px 50px;
    grid-template-areas:
      "header header header header"
      "nav nav nav nav"
      "aside aside orange orange"
      "aside aside orange orange"
      "footer footer footer footer";
  }

  header {
    background-color: transparent;
    grid-area: header;
  }

  nav {
    background-color: transparent;
    grid-area: nav;
    display: flex;
  }

  aside {
    background-color: transparent;
    grid-area: aside;
    display: block;
  }

  .yellow {
    background-image: yellow;
    grid-area: yellow;
  }

  .orange {
    background-color: transparent;
    grid-area: orange;
  }

  footer {
    background-color: transparent;
    grid-area: footer;
  }

  .logo {
    height: 150px;
    width: 200px;
    margin-bottom: 10px;
    font-size: 80px;
    font-family: 'Rubik Pixels', cursive;
  }
</style>
 -->
 <body>
  <a href="../../index.html">home</a>
  <div id="wrapper">
      <header><div id="logo">Internet</div></header>
      <nav>Das Wort Internet stammt von dem englischen Begriff internetwork was so viel bedeutet wie weltweites Netzwerk. Dieses Netzwerk besteht aus vielen miteinander verbundenen Computern, die Datenaustausch betreiben können.</nav>
      <aside>Das Internet ist ein globales Netzwerk von Computern und anderen elektronischen Geräten, das es Benutzern auf der ganzen Welt ermöglicht, Informationen und Daten auszutauschen und miteinander zu kommunizieren. Es besteht aus einer Vielzahl von Netzwerken, die miteinander verbunden sind und es Benutzern ermöglichen, auf Websites, E-Mail, soziale Medien, Online-Streaming-Dienste und vieles mehr zuzugreifen. Das Internet hat die Art und Weise, wie Menschen kommunizieren, Geschäfte tätigen und Informationen teilen, revolutioniert.</aside>
      <div id="green"></div>
      <div id="yellow"></div>
      <div id="orange"> <img src="Internet4.jpg" ></div>
     
      <footer></footer>
  </div>
</body>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Rubik+Pixels&display=swap');
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono&display=swap');


@font-face {
    font-family:'RubikPixels-Regular' ;
    src: url(fonts/RubikPixels-Regular.woff);
}

@font-face {
    font-family: 'IBM Plex Mono', monospace;
    src: url(fonts/SF-Mono-Regular.woff);
}





* {

    box-sizing: border-box;
    font-family: 'IBM Plex Mono', monospace;
    background-color: rgb(255, 255, 255);
    

}

a{
    
    color: rgb(0, 0, 0);
    border-radius: 4px;
    position: relative;
    top: 2em;
    right: 100px;

    margin: auto;
    position: fixed;
}

*
#wrapper{
    display: grid;
    width: 800px;
    gap: 40px;
    margin: auto;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 75px 80px 300px 100px 150px 50px;
    grid-template-areas: 
        "header header header header"
        "nav nav nav nav"
        "aside aside orange orange"
        "aside aside orange orange"
        "footer footer footer footer"


    ; 
}

header{
    background-color: transparent  ;
    grid-area: header;

}
nav{
    background-color: transparent;
    grid-area: nav;
    display: flex;
}
aside{
    background-color: transparent;
    grid-area: aside;
    display: block;

}

#yellow{
    background-image: yellow;
    grid-area: yellow;
    

}

#orange{
    background-color: transparent;
    grid-area: orange;
    
}

footer{
    background-color:transparent;
    grid-area: footer;
}

#logo {
    height: 150px;
    width: 200px;
    margin-bottom: 10px;
    font-size: 80px;
    font-family: 'Rubik Pixels', cursive;
}





</style>
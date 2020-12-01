<table width="100%"> 
  <tr>
  <td width="50%">
      
&nbsp; <br> [![Spotify](https://4nfkxixs5shwvwgp5hc4acd3w.vercel.app/api/spotify)](https://open.spotify.com/user/4nfkxixs5shwvwgp5hc4acd3w)

  </td>
  <td width="50%">
  
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://dev.to/ekto" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/dev-dot-to.svg" alt="ekto" height="30" width="40" /></a>
<a href="https://twitter.com/heyekto" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="heyekto" height="30" width="40" /></a>
<a href="https://instagram.com/egebutera" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="egebutera" height="30" width="40" /></a>
<a href="https://dribbble.com/ekto" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/dribbble.svg" alt="ekto" height="30" width="40" /></a>
<a href="https://medium.com/@heyekto" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/medium.svg" alt="@heyekto" height="30" width="40" /></a>

[//]: <> (The `&nbsp;` is to have Aphelion take up more space)
[//]: <> (Old Visits: https://badges.pufler.dev/visits/ekto/ekto?logo=GitHub&label=github%20visits&color=336699&logoColor=white&style=flat-square)
<svg width="480" height="133" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <foreignObject width="480" height="133">
        <div xmlns="http://www.w3.org/1999/xhtml" class="container">
            <style>
                .main {
                    /*margin-top: 40px;*/
                    display: flex;
                }

                .currentStatus {
                    float: left;
                    font-size: 24px;
                    position: static;
                    margin-top: -5px;
                    margin-left: 10px;
                }
                
                .container {
                    border-radius: 5px;
                    padding: 10px 10px 10px 0px;
                }

                .art {
                    width: 27%;
                    float: left;
                    margin-left: -5px;
                }

                .content {
                    width: 71%;
                }

                .song {
                    color: #666;
                    overflow:hidden;
                    margin-top: 3px;
                    font-size: 24px;
                    text-align: center;
                    white-space:nowrap;
                    text-overflow:ellipsis;
                }

                .artist {
                    color: #b3b3b3;
                    font-size: 20px;
                    margin-top: 4px;
                    text-align: center;
                    margin-bottom: 5px;
                }

                .cover {
                    width: 100px;
                    height: 100px;
                    border-radius: 5px;
                }

                #bars {
                    width: 40px;
                    height: 30px;
                    bottom: 23px;
                    position: absolute;
                    margin: -20px 0 0 0px;
                }

                .bar {
                    width: 3px;
                    bottom: 1px;
                    height: 3px;
                    position: absolute;
                    background: #1DB954cc;
                    animation: sound 0ms -800ms linear infinite alternate;
                }
                
                div {
                    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
                }
                
                @keyframes sound {
                    0% {
                        height: 3px;
                        opacity: .35;
                    }

                    100% {
                        height: 15px;
                        opacity: 0.95;
                    }
                }

                {{barCSS|safe}}
            </style>

            <!-- <div class="currentStatus">{{status}}</div> -->

            <div class="main">
                <a class="art" href="{}" target="_blank">
                    <center>
                        <img src="data:image/png;base64, {{image}}" class="cover" />
                    </center>
                </a>

                <div class="content">
                    <div class="song">{{songName}}</div>
                    <div class="artist">{{artistName}}</div>
                    <div id="bars">{{contentBar|safe}}</div>
                </div>
            </div>

        </div>
    </foreignObject>
</svg>

<template> 
    <div class="my-self" style="height: 350px; border-radius: 15px; padding: 25px;">
        <div class="container">
            <div class="row">
                <div class="texto">
                    <div>
                        <span class="terminal">rhonal@rhonal:~$ </span>
                        <span class="command"> ls </span>
                    </div>
                    <div>
                        <span> my-presentation.js </span>
                    </div>
                    <div>
                        <span class="terminal"> rhonal@rhonal:~$ </span>
                        <span class="command"> node
                            <a href="https://gist.githubusercontent.com/rhonalchirinos/c71b6216a517d702a390b807f644dd3b/raw/4e344652ae2a13bc7a7f68e0eadeeb3b30fd07d5/my-presentation.js"
                                target="_blank">
                                my-presentation.js
                            </a>
                        </span>
    
                    </div>
                    <div>
                        <span style="display: block; font-size: 18px">
                            Rhonal Alfredo Chirinos Rodriguez
                        </span>
                        <span style="display: block; font-size: 18px">
                            Developer node, php, java.
                        </span>
                    </div>
                    <div>
                        <span class="terminal"> rhonal@rhonal:~$ </span>
                        <span class="command" appTerminalPrompt> | </span>
                    </div>
                </div>
            </div>
        </div>
    </div> 
</template>



<style scoped>

.my-self {
    font-family: 'UbuntuMono';
    font-size: 14px;
    opacity: 1;
    color: white;
    background: #300a24;
  
    .texto {
      opacity: 1;
      top: 5px;
    }
  
    .terminal {
      font-family: ubuntu;
      font-weight: bold;
      color: #28f600;
    }
  
    a {
      color: white;
    }
  }
  
</style>
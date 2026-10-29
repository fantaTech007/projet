        nom:app-node  
          
           *description
pour commencer nous avons créé un dossier au nom de app_node qui est un environnement d'execution open-source et multi-platforme;
           *corps message
           creation d'un dossier appeler index.js
           
           nous avons fait un package.json qui a permis de d'ouvrir un terminal et de taper une syntaxe redline universelle
           const readline = require("node:readline");
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout,
});

rl.question("entrez un nombre : ", (answer) =>{
    const number = Number(answer)
    console.log("le nombre est:", number);
    rl.close();
});

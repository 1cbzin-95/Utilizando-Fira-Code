# Utilizando-Fira-Code
## O que é? e pra que serve?  
São fontes que servem apenas de estetica para quem trabalha com javascript ou derivados. Portanto serve somente de estica para seu vscode e nada mais que isso...  

## Como instalar  
- 1ª Coisa a se fazer é baixar essa pastinha com as fontes, abra ela e localize a pasta ttf que esta as fontes.  
- 2ª Coisa é clicar com mause e instalar as fontes ou dependendo da sua distro voçê tera que mover elas para o local das fontes do seu PC, mas normalmente ao clicar elas são instaladas, é recomendado instalar só a fira Bold.  
- 3ª e ultima parte abra seu vscode siga para files/preferences/settings, aberto essa parte siga para TextEditor va descendo no scroll até encontrar até encontrar "edit settings.json", clique nele e edite acrescentando:  
```
 "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true
```  
No final da estapa seu settings deve estar mais ou menos assim:  
```
{
    "workbench.startupEditor": "newUntitledFile",
    "workbench.iconTheme": "material-icon-theme",
    "git.autofetch": true,
    "editor.codeActionsOnSave": null,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true
}
```  
Pronto não esqueça de salvar e reiniciar o vscode 👍.

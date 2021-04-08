# Desafio
Desafio Suporte Front-end [José Geraldo]

### Para executar o projeto
clonar o projeto
abrir o arquivo .html no navegador, 
( 
  para uma melhor visualização com as dimensensões apresentadas
  abrir console, 
  abrir toggle device toolbar ctrl + shift + m
  selecionar iphone5s
)

Exercícios Manipulação da DOM

1) Adicione um ícone para Youtube no header apontando para https://www.youtube.com/channel/UCLI4tg1oh_oLiJJteExJdUQ
``` .js
var elemento = document.querySelector(".header__networks-list");

var youtube = document.createElement("a");
youtube.setAttribute("href", "https://www.youtube.com/channel/UCLI4tg1oh_oLiJJteExJdUQ");
youtube.setAttribute("target", "_blank");

var icone = document.createElement("i");
icone.setAttribute("class", "icon icon-youtube-header icon--small icon--hover-youtube");

youtube.append(icone);
elemento.appendChild(youtube);

```


2)



3)


4)

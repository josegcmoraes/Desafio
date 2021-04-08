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

2) Modifique o comportamento do menu Whatsapp
```


```

3) Modifique o formulário de "Estou Interessado" em https://testes.autoforce.com.br/autoforce-ford/novos/territory
```
let elementos = document.getElementsByTagName("fieldset");

var divSelect = document.createElement("div");
divSelect.setAttribute("class", "form-group");

var mySelect= document.createElement("select");
mySelect.setAttribute("class", "form-control");
var myOption = document.createElement("option");
myOption.value = "";
myOption.text = "Selecione um veículo";
mySelect.append(myOption);
var myOption = document.createElement("option");
myOption.value = "SUV";
myOption.text = "SUV";
mySelect.append(myOption);
myOption = document.createElement("option");
myOption.value = "Senda";
myOption.text = "Senda";
mySelect.append(myOption);
myOption = document.createElement("option");
myOption.value = "Hatch";
myOption.text = "Hatch";
mySelect.append(myOption);
myOption = document.createElement("option");
myOption.value = "Pickup";
myOption.text = "Pickup";

mySelect.append(myOption);
divSelect.appendChild(mySelect);
elementos[1].appendChild(divSelect);

// Criação do textarea
var divText= document.createElement("div");
divText.setAttribute("class", "form-group");

var myText= document.createElement("textarea");
myText.setAttribute("placeholder", "Mensagem");

myText.setAttribute("maxlength", "500");
divText.appendChild(myText);

elementos[1].appendChild(divText);

```

4) Exiba um modal com o escudo do Palmeiras
```

```

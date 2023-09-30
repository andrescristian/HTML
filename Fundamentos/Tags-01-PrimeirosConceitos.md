<h3 align="center">Primeiros Conceitos do HTML</h3>

#HTML<br>
-> Significa <em>"Linguagem de Marcação de Hipertexto"</em>, ou seja, não é uma Linguagem de Programação<br>
-> Faz parte do <ins>Desenvolvimento Front-end</ins><br>
-> Os códigos são baseados em <ins>Tags</ins><br>
-> Algumas Tags não precisam ter um fechamento de Tag, como o <code>&lt;br&gt;</code>, <code>&lt;hr&gt;</code> e <code>&lt;img&gt;</code>

Exemplos de Tags:	

    <h1>  Exemplo de Título  </h1>
    <p> Exemplo de Parágrafo </p>
    
    <img src="foto.png" alt="Exemplo de foto">
    src                  --> Origem da Imagem
    alt                  --> Atributo que descreve do que se trata a imagem
    "Exemplo de foto"    --> Valor do atributo "alt"

1º - Para iniciar uma estrutura básica do documento HTML no VScode, é só digitar "html:5" ou "!" e logo em seguida clicar no [ TAB ], e ela será representada da seguinte maneira:<br>


    <!DOCTYPE html>
    <html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>    
    
    </body>
    </html>

#_Detalhes da estrutura acima:

    <!DOCTYPE html>	        --> Vai entender que vou desenvolver em HTML 5
    <html lang="pt-br">     --> Língua do site em Português(PT-BR)
    <head>	</head>	        --> Cabeça, configurações do Site
    <body>	</body>	        --> Corpo, parte visível do Site
    <meta charset="UTF-8">  --> Dá compatibilidade com acentuações
    <title>	</title>        --> Título que vai aparecer na aba da página

#_Tags básicas:

    <h1>  </h1>	--> Título de nível 1
    <h2>  </h2>	--> Título de nível 2
    <h3>  </h3>	--> Título de nível 3
    <h4>  </h4>	--> Título de nível 4
    <h5>  </h5>	--> Título de nível 5
    <h6>  </h6>	--> Título de nível 6
    <p>   </p>   	--> Começa um parágrafo
    <br>        	--> Faz uma quebra de linha
    <hr>       	--> Mostra uma linha horizontal na página
    <!-- Faz um comentário dentro do código -->

<br>2º - Desenvolvimento Front-End<br>
-> Como dito anteriormente, o HTML faz parte desta área da Programação, junto com o CSS e o JavaScript<br>
-> HTML significa <em>"Linguagem de Marcação de Hipertexto"</em><br>
-> CSS significa <em>"Folhas de Estilo em Cascata"</em><br>
-> JavaScript ou ECMAScript6 é a Linguagem de Programação<br>

#CSS<br>
-> Ela foca em Design: cores, sombras, tamanhos e posicionamento<br>
-> O formato do CSS tem:<br>
	- Seletor (fica do lado da 1ª chave)<br>
	- Declaração (detalhes do Seletor selecionado)<br>
	- Propriedade e Valor<br>
-> No HTML, o CSS fica dentro de uma das TAGs:

    <link rel="stylesheet" href="style.css">
    <style>  </style>

#JavaScript<br>
-> Ela foca nas Interações: Menus, animações, popups e validações<br>
-> No HTML, o JavaScript fica dentro de uma das TAGs:
         
    <script src="script.js">  </script>"
    <script>  </script>

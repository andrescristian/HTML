<h2 align="center">Primeiros Conceitos do HTML</h3> <br>

-> HTML significa <em>"Linguagem de Marcação de Hipertexto"</em>, ou seja, não é uma Linguagem de Programação<br>
<details><summary>Faz parte do Desenvolvimento Front-end (HTML, CSS & JavaScript)</summary>
<li><em>HTML</em> --> foca no Conteúdo da Página Web: textos, imagens, vídeos e tabelas<br>
<li><em>CSS</em>  --> foca no Design: cores, sombras, tamanhos e posicionament, e ficam dentro da TAG "<style> </style>" no HTML<br>
<li><em>JavaScript</em>(Linguagem de Programação) --> foca nas Interações: Menus, animações, popups e validações<br>
</details>
1º_Os códigos são baseados em TAGs<br>

Exemplos de Tags:	

    <h1>  Exemplo de Título  </h1>
    <p> Exemplo de Parágrafo </p>
    
    <img src="foto.png" alt="Exemplo de foto">
    src                  --> Origem da Imagem
    alt                  --> Parâmetro
    "Exemplo de foto"    --> Valor do atributo "alt"

->  No VScode, é só digitar "html:5" ou "!" e logo em seguida clicar no [ TAB ]<br>
->  A estrutura básica do HTML é representada da seguinte forma:<br>


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

<h2 align="center">Links e Âncoras</h2>

<h3 align="center">Link Externo</h3>

    <a href="" target="_blank" rel="external">	</a>  -->  Acessa o link em outra janela
    <a href-"" target="_self">	</a>                  -->  Acessa o link na mesma janela

<h3 align="center">Link Interno</h3>
-> É um link que acessa outra página do mesmo Servidor e na mesma Pasta<br>
-> Não precisa colocar a URL da página no atributo "href"<br>    

    <a href="pag002.html" target="_blank" rel="next">	</a>
    <a href="pag002.html" target="_blank" rel="prev">	</a>

#Valores do Atributo <code>rel</code>:<br>

    rel="next"	--> Indica que este link é para a próxima parte do documento atual  
    rel="prev"	--> Mostra que é para a parte anterior do documento atual
    rel="external"	--> Mostra que é um link que não faz parte do site
    rel="author"	--> É um link para o site do autor do artigo atual

<h3 align="center">Links para Download</h3>

                  <a href="CaminhoDoArquivo" download="ArquivoPraBaixar" type="Tipo de Arquivo Que Será Baixado">

#Exemplo:
    
                              <a href="arquivos/MeuLivro.pdf" download="MeuLivro.pdf" type="aplication/pdf">

#Lista dos "Media Types" (Atributo <code>type</code>) mais usados:

    application/zip		video/mp4		  audio/mpeg
    text/html               video/H264		  audio/aac
    text/css                video/JPEG		  image/jpeg
    text/javascript		font/ttf		  image/png

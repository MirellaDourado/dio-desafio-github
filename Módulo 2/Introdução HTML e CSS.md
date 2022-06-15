# Introdução a criação de websites com HTML5 e CSS3

## Estrutura básica

O HTML foi criado em 1991, desde 91 foram criadas 5 versões

O Elemento HTML é formado por:

	1- tag de abertura
	
	2- atributo
	
	3- conteúdo
	
	4- tag de fechamento

Estrutura básica:
	
	- <!doctype html> utilizado para informar qual tipo de texto estamos escrevendo
	
	- <html> 
	
	- <head> possui metas informações; responsável pela aba
	
	- <meta>
	
	- <tittle>
	
	- <body> toda a estrutura do site
	
___

## Semântica

<Section> representa uma seção generica

<header> cabeçalho da página

<article> conteúdo relevante dentro da página

<aside> conteúdo relacionado ao conteúdo principal da página

<footer> rodapé

<h1>-<h6> importância de um título

___

## Textos e links em HTML

<p> representa parágrafo

	↳ suporta códigos, vídeos, imagens, links, textos
	
<a> significa âncora
	
	↳ href = faz referência para o hiperlink que deve abrir
		
		➢  para mandar email coloca-se o 'prefixo': mailto
		
		➢ para fazer ligação coloca-se o 'prefixo': tel
	
	↳ target: _blank = diz ao navegador para abrir o link em outra aba
	
___

## Inserção de imagens

<img> para colocar imagem no site
	
	↳ src = guarda o caminho da imagem; **é obrigatório**
	
	↳ alt = descrição da foto; não obrigatório, porém, **altamente recomendado**
	
			*após escolher uma imagem, bom [comprimir e remover dados](https:www.tinypng.com) desnecessários*
			
___

## Listas

<ul> representa uma lista onde a ordem **não é** importante

<ol> representa uma lista onde a ordem **é** importante

<li> representa o item da lista

___

## Introdução ao CSS3

1996 foi criado o CSS

Para criar um style é necessário ter um arquivo com ".css"

Para colocar o style em uma pasta é necessário utilizar o elemento link na header com rel="stylesheet"

Uma regra CSS é formada por:
	
	- seletores (formado por elementos HTML)
	
	- declarações (dentro de um par de chaves)

Id e Classes são utilizados para diferenciar na hora da estilização
	
	Classe: precedida por um ponto:
	
		.header
		
	ID: 
		Só pode ser usado uma vez em uma página		
				
		precedido por uma hash:
			
		#header

O site representa cada elemento HTML como uma caixa retangular chamada box model que é divida em:
	
	- margin: espaçamento entre elementos
	
	- border: circunda o padding e o content; é possivel modificar a aparência como largura e cor
	
	- padding: espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele;
	
	- content: é o conteúdo

___

## Estilizando elementos, textos e listas

o PADDING é dividido:
	
	- padding: topo, direita, inferior, esquerdo
	
	- padding: topo+inferior, direita+esquerda
		
		*também há a possibilidade de se utilizar de forma específica: padding-top; padding-bottom; padding-left; padding-right*

No BORDER pode-se modificar
	
	- largura: border-width
	
	- cor: border-color
	
	- estilo: border-style
		
		- ainda existe a propriedade border-radius, que permite arredondar as bordas; utiliza a mesma regra do padding e também pode apenar utilizar uma unidade e se aplicará a todas as partes.
		
		*também pode-se utilizar apenas border de uma forma mais abrangente*
		
		*pode-se também, caso queira ser mais específico, modificar apenas um lado da borda utilizando como o exemplo: border-top-width*
		
		*é uma boa prática manter as margens sempre na mesma direção*
		
sobre as FONTES:

	- font-family: altera a fonte do texto
		
		pode-se colocar mais de uma fonte, o computador interpretarar as fontes seguintes como back-up
		
	- font-size: modifica o tamanho da fonte
	
	- font-style: modifica o estilo da fonte
	
		normar: o jeito que a fonte foi desenhada
		
		italic
		
		bold
		
	- font-weight
	
		torna negrito
	
	- text-transform: muda o texto
	
			lowercase
			
			uppercase
			
			capitalize (todas as letras iniciais para maiúsculo)
			
	- text-decoration
	
		underline
		
		overline
		
		line-through (corta a palavra)
		
para as LISTAS existem os seguintes: 

	- list-style-type: modifica marcadores de acordo com o tipo de lista
	
	-list-style-image: coloca uma imagem como marcador da lista






























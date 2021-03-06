# NLTK por SEO

Este proyecto utiliza NLTK para análisis de las palabras claves y las etiquetas. 

## Para Empezar

Los instrucciones puede ayudarte obtener una copia del proyecto para su ordenador.

### Los requisitos indispensables

Necesita instalar estos antes de empieza:

* [Python](https://www.python.org/downloads/)
* [Anaconda](https://docs.anaconda.com/anaconda/install/)


### Instalar NLTK

1. Abre el "Anaconda Prompt" (puede buscarlo por buscando "Anaconda" en el menú de Incio de Windows)
2. Crea un virtual env
```
conda create -n yourenvname python=x.x anaconda
```
3. Instalar NLTK (anaconda es el canal)
```
conda install -c anaconda nltk
```
4. Instalar BeautifulSoup (anaconda es el canal)
```
conda install -c anaconda beautifulsoup4
```

### Descargar El Proyecto en GitHub

Ahora, puede descargar el proyecto en GitHub y ejecutar el código

## Ejecución del codígo

Puede ejecutar el "spider" usando el comando "python" en el símbolo de la sistema:
```
python todos.py
```
**Asegurarte usar el símbolo del sistema, activar tu virtualenv, y elegir el directorio de nivel superior del proyecto**
* Por esto proyecto el directorio de nivel superior: 

## Ejecución del GUI

Puede ejecutar el gui usando este comando en el símbolo del sistema:
```
python todouser.py
```

**Asegurarte usar el símbolo del sistema, activar tu virtualenv, y elegir el directorio de nivel superior del proyecto**
* Por esto proyecto el directorio de nivel superior: gui

## Añadir al corpus

Para añadir al corpus, necesita crear un archivo txt en el directorio del corpus. Abre la aplicación "Bloc de notas" y escribe el corpus ahí. Guardarle en la carpeta con el nombre del directorio ("LTcorpus")

## File Repository
```
raspar/
	scrapy.cfg
	raspar/
		__init__.py
		
		items.py          	# project items definition file
		
		middlewares.py   	# project middlewares file
		
		pipelines.py      	# project pipelines file
		
		settings.py       	# project settings file
		
		spiders/          	# a directory for your spiders
		
			__init__.py
			
			userinput.py	# Spider that crawls URL given by user
NLTK/
	LTCorpus/			# corpora directory
		all.txt		
		
		destinations.txt
		
  		corpus.py		# Edit the corpora using a command prompt
  		
		corpusgui.py		# Edit the corpora using a GUI
	
	linkslength.py			# Find the gross text length and ratio
					  for a set of URLs using the command prompt
	
	keywordslinks.py		# Find the keywords' scores for a set of URLs
					  using the command prompt
	
	keywordsgui.py			# Find the keywords' scores for a set of URLs
					  using a GUI
	
	linksgui.py			# Find the gross text length and ratio
					  for a set of URLs using a GUI
```


## Referenciass
[NLTK Textbook](https://www.nltk.org/book/)

¿Tienes preguntas? Enviarmelas aqui: noelle.rivera.516@gmail.com

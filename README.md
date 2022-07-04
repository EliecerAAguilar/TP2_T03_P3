# Topicos Especiales 2

<div id="badges">
    <a href="https://www.linkedin.com/in/eliecer-aguilar-507/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="https://twitter.com/elieceraguilar3">
      <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
    </a>
    <a href="https://colab.research.google.com/github/eliecer507/TP2_T03_P3/blob/main/p03.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
    </a>
</div>

## Problema	3.	Provea	queries	en	SQL	y	resultados	para	las	siguientes	preguntas
Haga	una	captura	de	pantalla	del	query	y	de	la	respuesta obtenida.
1. Visualice el	SRID	y	el	proj4text	de	la	tabla	PAN_pais.

2. ¿Cuantos	tipos	de	caminos	existen	en	la	tabla	Pan_roads?	¿Cuántos	hay	para	cada	tipo?	(agrupe	con	Groupby)

3. Liste	la	información	de	aquellos	distritos,	de	la	tabla	Pan_adm3,	que	estén	en	comarca	indígena	o	los	que	están	
en	o	cerca	de	un	cuerpo	de	agua.

4. Calcule	el	área	en	km2 totales,	usando	ST_Area,	para	todas	las	provincias,	ordene	sus	resultados	de	manera	
descendente.

***
***Sugerencia***:	Compare	sus	resultados	con	la	tabla	en	<a href="https://en.wikipedia.org/wiki/Provinces_of_Panama" target = "_blank">https://en.wikipedia.org/wiki/Provinces_of_Panama </a>   
***

5. Provea	la	suma	total	en	km	de	todos	los	segmentos	de	carretera	que	están	en	la	tabla	Pan_roads.

6. Liste	5	distritos	que	contienen	aros	(rings) concéntricos	dentro	de	su	área.  
***
***Nota***:	Por	la	manera	que	fueron	creados	los	shapefiles	están	guardados	como	formas	geométricas,	para	obtener	
medidas	reales	debe	transformarlos	en	tipo	geográfico1.	Los	resultados	de	tipo	geográfico	se	dan	en	metros,	por	
lo	que	para	obtener	km2 debe	dividir	por	1,000,000,	y	para	km	entre	1000.
***

 #                                      Waste Water

![residual](input/residual.png)


Se extraen los  [DATOS](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=0f210c49cdcad510VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default) correspondientes a los últimos años de las EDAR de Madrid.

Objetivo:

"COMPROBAR SI HAY RELACÍÓN ENTRE GRUPOS DE DEPURADORAS(BASADOS EN SU UBICACIÓN) Y LA CANTIDAD DE 
                         CONTAMINANTES QUE PROCESAN"


Se ubican estas depuradoras en un mapa,y se intenta buscar una relación entre la cantidad de contaminantes y la ubicación de estas.Se dividen en grupos según ubicación.

Los datos se limpian y procesan para su posterior uso,para ello se usan distintos métodos de interpolación y agrupación.

Se lleva a acAbo una visualización de los datos para su posterior análisis;
  
 a) Clusterización usando Kmeans:

    -todas las variables
    -variables mayor peso

b) Clusterización usando cluster jerárquico:
    -todas las variables
    -variables mayor peso

Análisis y visualización de los distintos cluster.

Conclusiones


Librerias:

*Numpy/Pandas/Matplotlib/Seaborn/Sklearn
                   


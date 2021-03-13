# ApartamentosRV

Proyecto guiado para el sector de venta de casas y apartamentos para las personas de estrato 6, esta experiencia cuenta con una vista de realidad virtual en la que el espectador puede explorar uno de los apartamentos que se encuentra en oferta, el proyecto está montado con a-frame y los modelos están realizados en sketchup, el modelo cuenta con un amueblado y con una cercanía con la realidad muy favorable

## Comenzando 🚀

_Para poder ver el proyecto se recomienda tener un repositorio local y hacer la siguiente linea de código_

git clone https://github.com/jairov92/ApartamentosRV.git


### Pre-requisitos 📋

_Antes de usar el aplicativo asegúrate que en tu navegador puedas correr una extensión llamada live server o si tienes alguna similar, adicional a esto que el navegador tenga habilitado la función de sonido ya que el proyecto cuenta con música de ambiente_

```
Abre con live server y explora la realidad virtual con A-frame
```

### Proceso de creación  🔧

Comenzamos con el desarrollo del modelado, lo primero que tenemos que tener en cuenta es la imagen de referencia que fue asignada para la creación de este

![apartamento](https://user-images.githubusercontent.com/79010465/110733854-aed30380-81f4-11eb-99fe-090f5cf43e06.PNG)

Con esto en mente se comenzó con la creación del apartamento dándonos un modelo bastante bueno y que se veía bien para comenzar

![Captura](https://user-images.githubusercontent.com/79010465/111014076-24afaa00-8370-11eb-89de-6d2136c59bb3.PNG)


```
El modelado del apartamento se realizó en sketchUp
```

Se comienza con el desarrollo del apartamento y se asigna unas dimensiones que se ven en la imagen, luego de esto pegamos texturas y vemos en a-frame que tal se ve



![Captura2](https://user-images.githubusercontent.com/79010465/111014425-8c1a2980-8371-11eb-9cc2-91a5009809c5.PNG)



![Captura3](https://user-images.githubusercontent.com/79010465/111014606-7e18d880-8372-11eb-97d3-a0b123ec1605.PNG)


Para darle más realismo se colocó un skymap de la pagina https://hdrihaven.com/ al rededor del apartamento que es el siguiente 


![hansaplatz_4k-min](https://user-images.githubusercontent.com/79010465/111016186-67767f80-837a-11eb-94ef-ce1f6960e3a8.png)


```
https://hdrihaven.com/hdri/?c=night&h=hansaplatz
```

Luego de esto hacemos 2 pasos que son colocarle colisiones



![51iqf8](https://user-images.githubusercontent.com/79010465/111014809-84f41b00-8373-11eb-90b5-0e377c79f367.gif)


Colocarle objetos 3d bajados de manera gratuita de internet en la página https://sketchfab.com/feed donde encontramos modelos en obj y gtlf


![Captura](https://user-images.githubusercontent.com/79010465/111035459-b0fdb380-83e8-11eb-9b67-2419b0a3e18a.PNG)



![Captura5](https://user-images.githubusercontent.com/79010465/111015159-6d1d9680-8375-11eb-9d29-2263ca03060d.PNG)


![Captura6](https://user-images.githubusercontent.com/79010465/111015232-d4d3e180-8375-11eb-83e9-3b9846e6a014.PNG)


![Captura](https://user-images.githubusercontent.com/79010465/111035514-ec987d80-83e8-11eb-8f72-6140cc653d68.PNG)



![Captura](https://user-images.githubusercontent.com/79010465/111035419-7c89f780-83e8-11eb-91b6-c5864be64c14.PNG)



notamos que los colores tenian ciertos fallos entonces se decidio por cambiar el color del piso y paredes para darle un tono mas oscuro y que las texturas cargaran mejor



![Captura8](https://user-images.githubusercontent.com/79010465/111015774-72c8ab80-8378-11eb-9c1b-5fa09ec27cfd.PNG)

Para finalizar el reporte se realizo las respectivas colisiones de todos los objetos que hay en el apartamento quedando de la siguiente manera



![51j5s5](https://user-images.githubusercontent.com/79010465/111019069-ea073b00-838a-11eb-9179-0939b77cd95c.gif)

```
Las colisiones como las de las paredes se hicieron con planos y algunos otros con cajas
```




## Información adicional  🤓
Adicionalmente se creó dentro del proyecto una carpeta nueva llamada AR, que en esta contiene la misma información y archivos de objetos que la de la experiencia original, pero con la excepción de que el index está programado para mostrarnos el apartamento desde el techo con la perspectiva de Realidad Aumentada como se ve acontinuación



![51j6eu](https://user-images.githubusercontent.com/79010465/111019252-fdff6c80-838b-11eb-91f9-3efee53a4271.gif)


```
  Para este proyecto de RA se usó AR.js y A-frame
```


![WhatsApp Image 2021-03-12 at 10 30 21 PM](https://user-images.githubusercontent.com/79010465/111019004-736a3d80-838a-11eb-91ca-b9f5cff1b790.jpeg)




  
## Conclusiones Jairo ⚙️

_Como grupo estuvimos en etapas de investigación para resolver el entorno virtual del apartamento, decidimos usar ciertos cálculos para posicionar los objetos de manera ordenada. Encontramos buenas texturas de alta definición en algunos modelos dándole cierto realismo al apartamento encontramos errores y soluciones como grupo_

## Conclusiones Juan Camilo 📢

_Este trabajo se hizo de manera colectiva y estuvo bastante buena la manera de trabajar a través de GitHub, fue una experiencia gratificante y que en futuros trabajos se tiene que tener en cuenta, adicional a lo anterior debo decir que mi equipo de trabajo fue muy bueno y agradezco su tiempo y dedicación a pesar de que mi computador me presento muchas fallas al inicio_

## Conclusiones Danny Alejandro ☕ 

_Para este proyecto se aprendieron conceptos de realidad virtual para la web además de entender los beneficios y posibilidades de utilizar esta técnica_

## Construido por 🛠️


* jairo vergara portocarrero 2151714
* Juan Camilo Arboleda Garcia 2181056
* Danny Alejandro Martínez Duque 2185738


## Información de importancia 🎁

* Este proyecto fue realizado para la materia de Realidad virtual de la Universidad Autonoma de Occidente 📢
* Profesor: Cesar Martinez Uribe 🍺  
* Gracias por la comprensión y los comentarios del proyecto 🤓.




---
⌨️ con ❤️ por el GRUPO 6 😊

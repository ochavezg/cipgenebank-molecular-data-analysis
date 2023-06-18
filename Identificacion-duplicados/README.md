# Identificacion-duplicados

<img src="https://github.com/ronaldrobles/Identificacion-duplicados/assets/9561697/2ff51948-42e8-4711-86c7-8ba5f77b5270" width=50% height=50%>

Resumen de la metodologia para el uso de marcadores SilicoDArT en la identificación de duplicados de camote
&nbsp;  
&nbsp;  
```
install.packages("vegan")
install.packages("ggplot2")
```
&nbsp;  
&nbsp;  
#### 1. Se incluyen repeticiones de ADN a los largo de todos los envíos y se extraen únicamente los genotipos de éstos, ordenados par pares de columnas.
<img title="a title" alt="Alt text" src="./images/SilicoDArT_matriz_inicial.png" width=70% height=70%>

&nbsp;  
&nbsp;  
#### 2. Se cargan los datos
<img title="a title" alt="Alt text" src="./images/Image1.jpg" width=70% height=70%>

&nbsp;  
&nbsp;  
#### 3. Se calcula la reproducibilidad de los marcadores para todos los pares de repeticiones.
<img title="a title" alt="Alt text" src="./images/Image2.jpg" width=70% height=70%>

&nbsp;  
&nbsp;  
#### 4. ¿Cuál es el efecto por retirar aquellos marcadores con baja reproducibilidad?
<img title="a title" alt="Alt text" src="./images/Image3.jpg" width=70% height=70%>

&nbsp;  
&nbsp;  
#### 5. ¿Los marcadores eliminados tienen alguna característica que los defina?
<img title="a title" alt="Alt text" src="./images/Image4.jpg" width=70% height=70%>

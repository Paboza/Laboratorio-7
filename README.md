# Laboratorio-7
INTEGRANTES : Boza Paul

NRC:10069

FECHA: 17 de Enero de 2023

Objetivo General.-

Analizar y desarrollar ejercicios de circuitos aplicables a la teoría de máxima transferencia de potencia para descomponer sus propiedades, que permitan calcular mejor y de forma más sencilla variables desconocidas utilizando información teórica.

Objetivo Especifico.-

Describir las características de la teoría de máxima transmisión correspondiente, utilizando para ello la información teórica proporcionada mediante el uso de la página web y los videotutoriales. Analizar y calcular diferentes ejemplos de circuitos previamente aprendidos en clase para tensión y potencia aplicada, que serán validados mediante un simulador virtual mediante ejercicios de laboratorio.

Marco Teorico.-

Los transformadores eléctricos son dispositivos que se utilizan para aumentar o disminuir la tensión o el voltaje en un circuito eléctrico. Consisten en dos bobinas de alambre aislado, llamadas devanados, que se enrollan alrededor de un núcleo de hierro laminado.

La fórmula básica para calcular la relación de transformación de un transformador es:

![image](https://user-images.githubusercontent.com/116833964/221042881-609ca58a-dadc-4c11-9eab-e91f4106f177.png)

Donde V1 es la tensión en el devanado primario, V2 es la tensión en el devanado secundario, N1 es el número de vueltas en el devanado primario y N2 es el número de vueltas en el devanado secundario.

Los transformadores eléctricos son importantes porque permiten la transmisión de energía eléctrica a largas distancias con pérdidas mínimas. Al aumentar el voltaje en la línea de transmisión, se puede reducir la corriente y, por lo tanto, las pérdidas por resistencia en los cables. Luego, el voltaje se reduce de nuevo en el extremo receptor mediante un transformador, lo que permite el uso de la energía eléctrica en los hogares, las fábricas y otros lugares.

Además de la transmisión de energía eléctrica, los transformadores también se utilizan en una amplia variedad de aplicaciones, como la alimentación de equipos electrónicos, la carga de baterías y la soldadura.

Procedimiento.-

1.- Construya en el protoboard el circuito mostrado en la Figura 1.

![image](https://user-images.githubusercontent.com/116833964/218122299-54361c3e-d362-4ef1-bc10-6add62bdf6e6.png)

    a. Utilice el osciloscopio para observar el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los valores pico de las ondas observadas.

![lab 7 osciloscopio_1](https://user-images.githubusercontent.com/116833964/221067408-377ff3ff-b896-4ec4-ad4f-6d4046111935.jpg)
![image](https://user-images.githubusercontent.com/116833964/221067459-98fe085b-cf92-44c5-99b0-d1cc57864210.png)

    b. Utilice un multímetro para medir el voltaje  variando la frecuencia entre los valores de 0, 10, 50, 100, 500, 1000 . Anote los resultados.
    
![lab 7 osciloscopio_1](https://user-images.githubusercontent.com/116833964/221068966-b5154bbe-c7c9-48db-b690-3ded3758cd21.jpg)
![lab 7 multimetro_2](https://user-images.githubusercontent.com/116833964/221068590-ae5c4a6a-6c35-43a9-b03e-1b76707ee6d1.jpg)


    c. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la frecuencia entre los valores 0, 10, 50, 100, 500, 1000 . Anote los resultados.

![lab 7 c](https://user-images.githubusercontent.com/116833964/221068727-e7c4cb98-edd5-45db-9e6e-a29423b264f9.jpg)

_______________________________________________

2.- Construya el circuito mostrado en la Figura 2

![image](https://user-images.githubusercontent.com/116833964/221069879-513861bf-293b-4781-821a-3463469e5272.png)


Realice las mismas mediciones de los ítems del numeral anterior y presente los resultados.

![lab 7 2_1](https://user-images.githubusercontent.com/116833964/221071920-d5f37f8a-f3b0-47aa-af33-2d670f64025c.jpg)
![lab 7 2_2](https://user-images.githubusercontent.com/116833964/221071936-a1ec4145-1e8b-4034-970a-5c10fc841c74.jpg)
![lab 7 2_3](https://user-images.githubusercontent.com/116833964/221071949-a51eb5e6-ee1a-4bea-8005-b960329720b9.jpg)

- 7.4 Análisis de resultados.-

1.- Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las diferentes mediciones de voltaje realizadas con el osciloscopio y multímetro. Compare y comente los resultados obtenidos tomando en cuenta las distintas frecuencias utilizadas.

    CONDENSADOR 
    
 ![image](https://user-images.githubusercontent.com/116833964/221072600-47578752-b0f8-4747-ac98-1709c3a116d5.png)

    
    BOBINA

![image](https://user-images.githubusercontent.com/116833964/221072649-6c11cace-6f2a-4049-aafb-034d4bb1d8ac.png)

    COMENTARIO 
    Después de cálculos detallados con osciloscopio y multímetro pudimos comparar los datos y observamos que a la frecuencia 0Hz hay voltaje en el capacitor y a la frecuencia 0Hz hay cero voltaje en el inductor y esto sucede porque el capacitor mantiene carga y se descarga gradualmente.

- 7.5 Preguntas.-

    1.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?
    
  El capacitor acumula energía por lo que se mantiene con carga y la bobina no guarda carga por lo que actúa como un circuito abierto.
    
    2.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?
    
  En corriente alterna el capacitor actúa como un circuito abierto y la bobina genera un magnético, la cual va variando con el tiempo. 
    
    3.- ¿Qué cree usted que ocurriría con el voltaje  y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?
    
  Va a existir una variación en los valores del voltaje y corriente ya que están pueden subir o bajar en el caso de que sea corriente alterna el condensador dejara pasar corriente y la bobina la retendrá o la retrasara por lo que estos valores irán variando  
    
    4.- ¿Qué son los valores eficaces de voltaje y corriente?
 
 Se define como el valor de una corriente continua que al circular por una determinada resistencia óhmica pura produce los mismos caloríficos (igual potencia disipada), que dicha corriente alterna. De esa forma una corriente eficaz es capas de producir el mismo trabajo que su valor en corriente directa.
 
 - Conclusion.-

Al hacer cálculos, considere el tipo de multímetro y qué parte del multímetro está mirando, ya que el multímetro puede perderse si se usa incorrectamente. Los protoboards intentan distribuir bien su funcionalidad, en lugar de tener todo en un solo lugar. En los cálculos, considerar las fórmulas del teorema de Thevenin, para cálculos que requieran la aplicación del método, considerar los problemas que nos exigen encontrar y realizar cálculos valiosos, los componentes del experimento, considerarlos y revisarlos antes de ponerlos en práctica, verificar el voltaje de entrada, y presione en consecuencia Instruir para hacer el trabajo.

- Bibliografia.-

Floyd, T. L. (2007). Principios de Circuitos Electronicos. Mexico: Pearson educación.

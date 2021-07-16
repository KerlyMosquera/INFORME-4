# PRÁCTICA No.4 TEOREMA DE SUPERPOSICIÓN
## 1. OBJETIVOS
### OBJETIVO GENERAL
- Aplicar el teorema de superposición para comprovar las mediciones en la simulación y en los cálculos obtenidos.
### OBJETIVO ESPECÍFICOS
- Observar la efectividad y facilidad de uso del teorema de superposición, aplicado en el análisis de un circuito mixto.
- Comprender el teorema de superposición mediante la comprobación de mediciones experimentales y simulaciones de circuitos en Tinkercad.
- 
## 2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/84431598/125533526-b476c643-3a4a-4a5d-950b-5636dce15984.png)

## 3. EXPLICACIÓN  DEL PROCEDIMIENTO
### 3.1 MATERIALES Y EQUIPOS

![image](https://user-images.githubusercontent.com/84431598/125513157-8a2612cc-f075-4cc8-b092-30a968eb07d5.png)

### 3.2 PROCEDIMIENTO
#### 3.2.1 Arme el circuito que se muestra en la figura 3.1.

![image](https://user-images.githubusercontent.com/84425276/125726840-d45993f8-b2fe-480d-9bfc-a53a183d380b.png)

   *Figura 1. Circuito para comprobar el Teorema de Superposición.*

#### 3.2.2 Con las dos fuentes conectadas, mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 1 y 2 respectivamente.

![image](https://user-images.githubusercontent.com/84425276/125870436-66ad606d-13df-4a0a-b440-3d9de7420d80.png)

  *Figura 2: Medición de voltaje VA y la corriente Ix*
  
#### 3.2.3 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 1 y 2 respectivamente.

![image](https://user-images.githubusercontent.com/84425276/125870462-70a76c79-6e5b-49a3-a6bc-bf9b64de1973.png)

  *Figura 3: Medición de voltaje VA y la corriente Ix cuando es "cero" la fuente de voltaje de 12 V (V2)*

#### 3.2.4 Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 1 y 2 respectivamente.

![image](https://user-images.githubusercontent.com/84425276/125870532-6bbbd84d-6468-4609-98de-58197367392a.png)

*Figura 4: Medición de voltaje VA y la corriente Ix “cero” la fuente de voltaje de 20 V (V1)*

#### 3.2.5 Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.

## 4. RESPUESTAS A INTERROGANTES Y CÁLCULO DEL ERROR
### 4.1 CIRCUITO

![image](https://user-images.githubusercontent.com/84425276/125870891-95cd40ac-c846-4d8d-9cdd-859fdae52916.png)

Tabla 1. Medición de voltaje aplicando superposición.

![image](https://user-images.githubusercontent.com/84425276/125882311-27f9a1b2-8302-449b-8f18-acb2fcde4c72.png)

Tabla 2. Medición de corriente aplicando superposición.

![image](https://user-images.githubusercontent.com/84425276/125882334-8a69c709-1d1f-4ee8-81ec-8d6913e5c639.png)

### 4.2 CÁLCULOS

![image](https://user-images.githubusercontent.com/84431598/125889176-ed04bd32-ff49-4578-80c1-5cf64d422836.png)

1.-Reemplazamos V_2=12V con una resistenncia de cero (en cortocircuito)

![image](https://user-images.githubusercontent.com/84431598/125889293-3491685f-3869-4d49-b914-ce376a3fa087.png)

2.- Como R_4  y el voltaje de V=12V actúa como en una resistencia de cero y están en paralelo se reduce el circuito:

![image](https://user-images.githubusercontent.com/84431598/125893425-9aa81776-75f5-49c3-9791-0630d141e546.png)

3.-Determinamos R_T  e I_T :

![image](https://user-images.githubusercontent.com/84431598/125893566-bd121662-6aef-42c8-988b-ff7e6e6de917.png)

4.- Determinar I_(X_1 ) producida por 20 V con la resistencia equivalente de:

![image](https://user-images.githubusercontent.com/84431598/125893726-ec6211d0-208c-4d48-9922-d0550fdeb9f1.png)

Y para encontrar Va1

![image](https://user-images.githubusercontent.com/84431598/125893800-eff74c19-302e-444f-a49e-a580439ddf94.png)

1.-Reemplazamos V_1=20V con una resistencia de cero (en cortocircuito)

![image](https://user-images.githubusercontent.com/84431598/125893943-8ab92bae-f006-4e3f-b918-99cd59c7dd6f.png)

2.-Determinamos R_E1 entre R_1 y R_2 las cuales se encuentran en paralelo

![image](https://user-images.githubusercontent.com/84431598/125893995-d2e74d8a-b697-4e7a-acc2-3160b4f9b7bf.png)

![image](https://user-images.githubusercontent.com/84431598/125894091-225509cd-c867-47a9-b212-b40107d7a906.png)

3.-Determinamos R_E2 entre R_E1 y R_3 las cuales se encuentran en serie

![image](https://user-images.githubusercontent.com/84431598/125894303-b7d71c0d-4b87-4966-84f0-82e0eddc0e78.png)

![image](https://user-images.githubusercontent.com/84431598/125894329-b5e4bd39-331b-4552-9bb5-6597664f4f9f.png)

4.-Determinamos R_E3 entre R_E2 y R_4 las cuales se encuentran en paralelo

![image](https://user-images.githubusercontent.com/84431598/125894456-380ffc69-20aa-46f6-b6ea-4fc36d7d8133.png)

![image](https://user-images.githubusercontent.com/84431598/125894549-b1735dc5-df85-41a6-b578-c41aaf49769c.png)

5.- Determinar una I_T,I_x  y una I_y

![image](https://user-images.githubusercontent.com/84431598/125894623-7569964d-6438-4a43-9a2d-f1d88ae752ca.png)

![image](https://user-images.githubusercontent.com/84431598/125894738-2cc7886e-2592-431a-b583-df026e746f79.png)

Para encontrar VA2

![image](https://user-images.githubusercontent.com/84431598/125895008-2522ffab-387d-4267-83d7-84967518f81d.png)

6.- Los valores obtenidos nos ayudaran a determinar la V_A y I_X totales

![image](https://user-images.githubusercontent.com/84431598/125895059-a118b092-0fd7-4035-ae5f-5e7c4efad177.png)

### 4.3 CÁLCULO DEL ERROR

![image](https://user-images.githubusercontent.com/84425276/125882484-e563a193-0f2c-406e-bbf5-64454349a3ed.png)

Tabla 3. Cálculo del error

![image](https://user-images.githubusercontent.com/84425276/125882464-f277f3ad-e9b6-4496-ab91-6b53dc900540.png)

## 5. VIDEO

## 6. CONCLUSIONES
- Para concluir este teorema de superposicíon solo se puede utilizar cuando se encuentran dos o mas fuentes, es la suma algebraica de los voltajes (o de las corrientes si es el caso), debidos a cada fuente, como si cada una actuara de manera independiente.
-
-
- De los resultados obtenidos anteriormente se concluye que la práctica fue realizada correctamente.
## 7. BIBLIOGRAFÍA
Floyd, T. (2007). *Principios de circuitos eléctricos (8va ed),* México DF, México: Pearson Educación.

Roobins, A y Miller, W. (2007). *Análisis de circuitos teoría y práctica (4ta ed),* México DF, México: Cengage Learning.

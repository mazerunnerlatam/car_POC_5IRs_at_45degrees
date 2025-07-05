# car_POC_5IRs_at_45degrees
<br>
Commit 5df0b81 del 2025-Julio-5 
<br>
Video de WhatsApp 2025-07-05 a las 02.25.00_5a8bcc9b.mp4 <br>
Video de WhatsApp 2025-07-05 a las 02.24.03_df3bbdf6.mp4 <br>
El codigo tiene delays para probar que la logica con 5 sensores anda -  se grabaron de dos angulos distintos para ver como corrige <br>
Se puede ver en Video de WhatsApp 2025-07-05 a las 02.40.09_e1d818f1.mp4 como se traba por la baja velocidad y bajo torque - Hay parte la logica que mejorar asi no se  va fuera de pista <br>
<br> Tema 1: La lógica funciona bien se mantiene en la línea como siempre hay edge cases (después los explico)
<br> Tema 2: si lo ven funcionar de pasos es porque hice un modo debug a ver si andaba bien la lógica entonces la idea es que en vez de ser continuo hace un poquito y frena otro poquito y frena
<br> Tema 3: el ancho de la línea ( llamémosla d) es menor a la distancia que hay entre los sensores IR (llamémosla D), entonces con 5 IR el sensor el sensor del medio te marca la línea negra, pero tenés un ancho D hasta la izquierda y hasta la derecha otro D. Quizás con 6 sensores invertimos la lógica y la linea negra queda delimitada por el sensor 3 y 4 (quedando 1 y 2 a la izquierda y 5 y 6 a la derecha)
<br> Tema 4: vieron que le tengo que dar un empujóncito es porque las ruedas se pegan q la pista mucho pegamento, se lo intente sacar con acetona y papel de cocina (no funcionó). Necesitamos algo de goma hay que buscar adherencia y peso para que la fuerza Normal haga rozamiento
<br> Tema 5: Compré el famoso sensor de polulu Qtr8A. Es muy chiquito pero puede servir para variar la distancia D  Referencia Tema 3
<br> Tema 6: detección de intersecciones y giros 
Proximo pasos Reducir oscilaciones, detección de intersecciones y giros y finalmente hacerlo mas continuo


# Ejercicios de práctica

# EJERCICIO

**Ejercicio 1.** Convierte el número decimal (2,6<sub>10</sub>) a binario, con un error mínimo de 2<sup>-7</sup>.

Dividimos la operación en 2<sub>10</sub> y 0,6<sub>10</sub>.

2<sub>10</sub> = 10<sub>2</sub>

Ahora calculamos el decimal:

0,6<sub>10</sub> * 2<sub>10</sub> = 1,2<sub>10</sub> (Ahora quitamos el 1 para seguir operando ya que no es un 1 exacto, y asignamos 1 bit con información a la primera posición después de la coma). 10,1

0,2<sub>10</sub> * 2<sub>10</sub> = 0,4<sub>10</sub> (Si el resultado no llega a 1, asignaremos a esa posición un bit vacío) 10,10

0,4<sub>10</sub> * 2<sub>10</sub> = 0,8<sub>10</sub> 10,100

0,8<sub>10</sub> * 2<sub>10</sub> = 1,6<sub>10</sub> 10,1001

0,6<sub>10</sub> * 2<sub>10</sub> = 1,2<sub>10</sub> 10,10011

0,2<sub>10</sub> * 2<sub>10</sub> = 0,4<sub>10</sub> 10,100110

0,8<sub>10</sub> * 2<sub>10</sub> = 1,6<sub>10</sub> 10,1001100 (aquí vemos como ya se repite hasta el infinito) 

2,6<sub>10</sub> = 10,1001100<sub>2</sub>

**Ejercicio 2.** Expresa las siguientes cantidades binarias en el sistema decimal:

*a) 111,011<sub>2</sub> = 7,375<sub>10</sub>*

 [ 1 * 2<sup>2</sup> + 1 *2<sup>1</sup> + 1 * 2<sup>0</sup> + 0 * 2<sup>-1</sup> + 1 *2<sup>-2</sup> + 1 * 2<sup>-3</sup> ]

  [ 4 + 2 + 1 + 0 + 0,25 + 0,125 = 7,375 ]

*b) 110110,11001<sub>2</sub> = 54,78125<sub>10</sub>* 

[ 1 * 2<sup>5</sup> + 1 * 2<sup>4</sup> + 0 *2<sup>3</sup> + 1 * 2<sup>2</sup> + 1 *2<sup>1</sup> + 0 * 2<sup>0</sup> + 1 * 2<sup>-1</sup> + 1 *2<sup>-2</sup> + 0 * 2<sup>-3</sup> + 0 * 2<sup>-4</sup> + 1 * 2<sup>-5</sup> ]

[ 32 + 16 + 0 + 4 + 2 + 0 + 0,5 + 0,25 + 0 + 0 + 0,03125 = 54,78125 ]


*c) 11100,101<sub>2</sub> = 28,625<sub>10</sub>*

[ 1 * 2<sup>4</sup> + 1 *2<sup>3</sup> + 1 * 2<sup>2</sup> + 0 *2<sup>1</sup> + 0 * 2<sup>0</sup> + 1 * 2<sup>-1</sup> + 0 *2<sup>-2</sup> + 1 * 2<sup>-3</sup> ]

 [ 16 + 8 + 4 + 0 + 0 + 0,5 + 0 + 0,125 = 28,625 ]


## 2. Sumas binarias

Realiza las siguientes sumas binarias a partir de las cantidades dadas en decimal. Convierte los números a binario y efectúa las operaciones.

| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 | 0,5 | 0,25 | 0,125 | 0,0625 | 0,03125 | 0,015625 | 0,0078125 |

a) \(25 + 21\)
 | 0  | 0  |  0 |  1 | 1  |  0 |  0 |  1 |
|---|---|---|---|---|---|---|---|
| 128  | 64  | 32  | 16  | 8  | 4  | 2  | 1  |

16 + 8 + 1 = 25 

25<sub>10</sub> = 11001<sub>2</sub>

 | 0  | 0  |  0 |  1 | 0  |  1 |  0 |  1 |
|---|---|---|---|---|---|---|---|
| 128  | 64  | 32  | 16  | 8  | 4  | 2  | 1  |

16 + 4 + 1 = 21

21<sub>10</sub> = 10101<sub>2</sub>

 | 0  | 0  |  0 |  1 | 1  |  0 |  0 |  1 |
|---|---|---|---|---|---|---|---|
 |--- | --- | ---|  --- | --- |  --- | --- |  + |
 | 0  | 0  |  0 |  1 | 0  |  1 |  0 |  1 |
 |---|---|---|---|---|---|---|---|
 | 0  | 0  |  1 |  0 | 1  |  1 |  1 |  0 |

 25<sub>10</sub> + 21<sub>10</sub> = 101110<sub>2</sub>
 
b) \(15,125 + 16,75\)

| 0 | 0 | 0 | 0 | 1 | 1 | 1 | 1 | 0 | 0 | 1 |
|---|---|---|---|---|---|---|---|---|---|---|
| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 | 0,5 | 0,25 | 0,125 |

8 + 4 + 2 + 1 + 0,125 = 15,125

15,125<sub>10</sub> = 1111,001<sub>2</sub>

| 0 | 0 | 0 | 0 | 1 |0 | 0 | 0 | 1| 1 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|
| 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 | 0,5 | 0,25 | 0,125 |

16 + 0,5 + 0,25 = 16,75

16,75<sub>10</sub> = 10000,110<sub>2</sub>

| 0 | 0 | 0 | 0 | 1 | 1 | 1 | 1 | 0 | 0 | 1 |
|---|---|---|---|---|---|---|---|---|---|---|
|---|---|---|---|---|---|---|---|---|---|+|
| 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 1 | 1 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |

15,125<sub>10</sub> + 16,75<sub>10</sub> = 11111,111<sub>2</sub>

c) \(47 + 15\)

| 0  | 0  |  1 |  0 | 1  |  1 |  1 |  1 |
|---|---|---|---|---|---|---|---|
| 128  | 64  | 32  | 16  | 8  | 4  | 2  | 1  |

32 + 8 + 4 + 2 + 1 = 47

47<sub>10</sub> = 101111<sub>2</sub>

| 0  | 0  |  0 |  0 | 1  |  1 |  1 |  1 |
|---|---|---|---|---|---|---|---|
| 128  | 64  | 32  | 16  | 8  | 4  | 2  | 1  |

8 + 4 + 2 + 1 = 15

15<sub>10</sub> = 1111<sub>2</sub>

| 0 | 0 | 1 | 0 | 1 | 1 | 1 | 1 |
|---|---|---|---|---|---|---|---|
|---|---|---|---|---|---|---|+|
| 0 | 0 | 0 | 0 | 1 | 1 | 1 | 1 |
|---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 1 | 1 | 1 | 1 | 0 |

47<sub>10</sub> + 15<sub>10</sub> = 111110<sub>2</sub>

## 3. Operaciones binarias

Realiza las siguientes operaciones binarias:

a) 1100010100 - 110101 = 111101011

| 1 | 1 | 0 | 0 | 0 | 1 | 0 | 1 | 0 |0 |
|---|---|---|---|---|---|---|---|---|---
|---|---|---|---|---|---|---|---|---|-|
| 0 | 0 | 0 | 0 | 1 | 1 | 0 | 1 | 0 | 1 |
|---|---|---|---|---|---|---|---|---|---|
| 0 | 1 | 1 | 1 | 1 | 0 | 1 | 0 | 1 | 1 |

b) 1101010,1101 - 1010,001 = 1100000,1011

| 1 | 1 | 0 | 1 | 0 | 1 | 0 | 1 | 1 | 0 | 1 |
|---|---|---|---|---|---|---|---|---|---|---|
|---|---|---|---|---|---|---|---|---|---|-|
| 0 | 0 | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 1 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 1 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 1 | 1 |

c) 110110 * 1010 = 1000011100

| 0 | 0 | 0 | 0 | 0 | 1 | 1 | 0 | 1 | 1 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|
|---|---|---|---|---|---|---|---|---|---| X |
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 1 | 0 |
|---|---|---|---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 1 | 1 | 0 | 1 | 1 | 0 | - |
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | - | - |
| 0 | 0 | 1 | 1 | 0 | 1 | 1 | 0 | - | - | - |
|---|---|---|---|---|---|---|---|---|---|---|
| 0 | 1 | 0 | 0 | 0 | 0 | 1 | 1 | 1 | 0 | 0 |

d) 10001001 \ 1010

Sin decimal =  1101<sub>2</sub> con 111<sub>2</sub> de Resto

<img width="702" height="577" alt="image" src="https://github.com/user-attachments/assets/bdef2cf0-0a21-4c1d-b3d3-9ee2bcefce9c" />

Con decimal = 1101,101100...

<img width="525" height="677" alt="image" src="https://github.com/user-attachments/assets/87899cb0-0557-4940-99e8-c0b3561eec53" />

e) 10001000100 \ 101010

Resultado = 11010<sub>2</sub>

<img width="580" height="487" alt="image" src="https://github.com/user-attachments/assets/634f06fa-3b91-4c4e-91cc-82b026afab4e" />


---

## 4. Comandos de red en Windows y análisis de protocolos

1. Ejecuta, desde el símbolo del sistema de Windows, el comando `ipconfig`.  
2. ¿Qué información vemos?
   
   Vemos la configuración de nuestra red y de que manera estamos conectados.
   
3. Realiza las transformaciones y operaciones indicadas: AND entre la dirección IP y la máscara de red.
   
  192.168.1.25 AND 255.255.255.0 = 192.168.1.0
   
4. ¿Qué resultado obtenemos?
   
 La dirección de red

5. Vamos más allá: ejecuta `ipconfig /all`.
   
6. ¿Dónde vemos representación hexadecimal?

   En la dirección física
   
7. ¿Cuántos bits tiene la dirección MAC?

48 Bits

11. ¿Puedes ver una dirección IPv6?
   
13. ¿Cuántos bits tiene? ¿En qué formato está?
 Hexadecimal, 128 Bits
14. Vamos a instalar una herramienta fundamental en redes: un analizador de protocolos.

Permite capturar y examinar los paquetes que circulan por la red

16. ¿Cómo se observa la información en pantalla en Wireshark? ¿En qué formatos?

En Hexadecimal

---

## 5. Preguntas tipo test

### Pregunta 1. Máscaras de subred

Al configurar una subred, te asignan la máscara `255.255.255.192`.

¿Cuántos bits de host se han utilizado para esta máscara?

- A. 2 bits  
- B. 8 bits
- C. 6 bits :white_check_mark:
- D. 4 bits

### Pregunta 2. Permisos en Linux

En un servidor Linux, aplicas el comando `chmod 750` a un directorio crítico.

¿Qué permisos exactos tiene el grupo del sistema sobre dicho directorio?

- A. Ningún permiso
- B. Lectura, escritura y ejecución
- C. Lectura y ejecución :white_check_mark: 
- D. Solo lectura

### Pregunta 3. EtherType

Al analizar una trama de red, el campo EtherType muestra el valor hexadecimal `0x0800`.

¿A qué sistema de numeración pertenece este valor para identificar protocolos de red?

- A. Base 16 :white_check_mark:
- B. Base 2
- C. Base 8
- D. Base 10

### Pregunta 4. Wildcard mask

Si necesitas configurar una máscara comodín (*wildcard mask*) en ACL de routers Cisco equivalente a una máscara de subred `255.255.255.0`, ¿cuál es su expresión numérica correcta?

- A. `255.255.255.255`
- B. `255.0.0.0`
- C. `0.0.0.255` :white_check_mark:
- D. `0.0.255.255`

### Pregunta 5. Dirección MAC

En una dirección MAC como `00:1A:2B:3C:4D:5E`, ¿cuántos bits totales componen el bloque completo de la dirección física?

- A. 128 bits
- B. 32 bits
- C. 64 bits 
- D. 48 bits :white_check_mark:

### Pregunta 6. Permisos octales y bit sticky

Al auditar un archivo o directorio en Linux, encuentras unos permisos escritos en octal como `1755`, con el bit sticky activado.

¿Qué valor binario corresponde exactamente al dígito `1` inicial?

- A. `010`
- B. `001`:white_check_mark:
- C. `100`
- D. `111`

### Pregunta 7. Máscara CIDR

Si una subred IP tiene una máscara con CIDR `/28`, ¿cuántos bits están reservados exclusivamente para identificar hosts dentro de dicha subred?

- A. 4 bits
- B. 8 bits :white_check_mark:
- C. 28 bits
- D. 12 bits

### Pregunta 8. Conversión hexadecimal a decimal

En la resolución de problemas de arranque o volcados de memoria (*dumps*), observas un desplazamiento (*offset*) expresado en hexadecimal como `0x0A`.

¿Cuál es su valor equivalente en el sistema decimal?

- A. 12
- B. 16
- C. 15
- D. 10 :white_check_mark:

### Pregunta 9. Operaciones lógicas con direcciones IP

Al auditar configuraciones de red, necesitas comprobar si una IP pertenece a una red utilizando operaciones a nivel de bit.

¿Qué operador lógico binario se aplica entre la dirección IP y la máscara de subred para obtener la dirección de red?

- A. XOR lógico
- B. OR lógico
- C. AND lógico :white_check_mark:
- D. NOT lógico

### Pregunta 10. Permisos restrictivos en Linux

Si configuras un servicio de red y necesitas asignar permisos restrictivos en Linux que se traduzcan en `rwx------`, ¿cuál es el número octal equivalente que debes introducir?

- A. `600`
- B. `755`
- C. `700` :white_check_mark:
- D. `770`

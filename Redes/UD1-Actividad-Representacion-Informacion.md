# Ejercicios de práctica

## 1. Conversión de decimal a binario

**Ejercicio 1.** Convierte el número decimal \(2,610\) a binario, con un error mínimo de \(2^{-7}\).

**Ejercicio 2.** Expresa las siguientes cantidades binarias en el sistema decimal:

a) \(111,011_2\)

b) \(110110,11001_2\)

c) \(11100,101_2\)

---

## 2. Sumas binarias

Realiza las siguientes sumas binarias a partir de las cantidades dadas en decimal. Convierte los números a binario y efectúa las operaciones.

a) \(25 + 21\)

b) \(15,125 + 16,75\)

c) \(47 + 15\)

---

## 3. Operaciones binarias

Realiza las siguientes operaciones binarias:

a) \(1100010100 - 110101\)

b) \(1101010,1101 - 1010,001\)

c) \(110110 \times 1010\)

d) \(10001001 \div 1010\)

e) \(10001000100 \div 101010\)

---

## 4. Comandos de red en Windows y análisis de protocolos

1. Ejecuta, desde el símbolo del sistema de Windows, el comando `ipconfig`.
2. ¿Qué información vemos?
3. Realiza las transformaciones y operaciones indicadas: AND entre la dirección IP y la máscara de red.
4. ¿Qué resultado obtenemos?
5. Vamos más allá: ejecuta `ipconfig /all`.
6. ¿Dónde vemos representación hexadecimal?
7. ¿Cuántos bits tiene la dirección MAC?
8. ¿Puedes ver una dirección IPv6?
9. ¿Cuántos bits tiene? ¿En qué formato está?
10. Vamos a instalar una herramienta fundamental en redes: un analizador de protocolos.
11. ¿Cómo se observa la información en pantalla en Wireshark? ¿En qué formatos?

---

## 5. Preguntas tipo test

### Pregunta 1. Máscaras de subred

Al configurar una subred, te asignan la máscara `255.255.255.192`.

¿Cuántos bits de host se han utilizado para esta máscara?

- A. 2 bits
- B. 8 bits
- C. 6 bits
- D. 4 bits

### Pregunta 2. Permisos en Linux

En un servidor Linux, aplicas el comando `chmod 750` a un directorio crítico.

¿Qué permisos exactos tiene el grupo del sistema sobre dicho directorio?

- A. Ningún permiso
- B. Lectura, escritura y ejecución
- C. Lectura y ejecución
- D. Solo lectura

### Pregunta 3. EtherType

Al analizar una trama de red, el campo EtherType muestra el valor hexadecimal `0x0800`.

¿A qué sistema de numeración pertenece este valor para identificar protocolos de red?

- A. Base 16
- B. Base 2
- C. Base 8
- D. Base 10

### Pregunta 4. Wildcard mask

Si necesitas configurar una máscara comodín (*wildcard mask*) en ACL de routers Cisco equivalente a una máscara de subred `255.255.255.0`, ¿cuál es su expresión numérica correcta?

- A. `255.255.255.255`
- B. `255.0.0.0`
- C. `0.0.0.255`
- D. `0.0.255.255`

### Pregunta 5. Dirección MAC

En una dirección MAC como `00:1A:2B:3C:4D:5E`, ¿cuántos bits totales componen el bloque completo de la dirección física?

- A. 128 bits
- B. 32 bits
- C. 64 bits
- D. 48 bits

### Pregunta 6. Permisos octales y bit sticky

Al auditar un archivo o directorio en Linux, encuentras unos permisos escritos en octal como `1755`, con el bit sticky activado.

¿Qué valor binario corresponde exactamente al dígito `1` inicial?

- A. `010`
- B. `001`
- C. `100`
- D. `111`

### Pregunta 7. Máscara CIDR

Si una subred IP tiene una máscara con CIDR `/28`, ¿cuántos bits están reservados exclusivamente para identificar hosts dentro de dicha subred?

- A. 4 bits
- B. 8 bits
- C. 28 bits
- D. 12 bits

### Pregunta 8. Conversión hexadecimal a decimal

En la resolución de problemas de arranque o volcados de memoria (*dumps*), observas un desplazamiento (*offset*) expresado en hexadecimal como `0x0A`.

¿Cuál es su valor equivalente en el sistema decimal?

- A. 12
- B. 16
- C. 15
- D. 10

### Pregunta 9. Operaciones lógicas con direcciones IP

Al auditar configuraciones de red, necesitas comprobar si una IP pertenece a una red utilizando operaciones a nivel de bit.

¿Qué operador lógico binario se aplica entre la dirección IP y la máscara de subred para obtener la dirección de red?

- A. XOR lógico
- B. OR lógico
- C. AND lógico
- D. NOT lógico

### Pregunta 10. Permisos restrictivos en Linux

Si configuras un servicio de red y necesitas asignar permisos restrictivos en Linux que se traduzcan en `rwx------`, ¿cuál es el número octal equivalente que debes introducir?

- A. `600`
- B. `755`
- C. `700`
- D. `770`

# Clase: Ciclos y Arreglos

1. Crear un nuevo programa:

[Crear un programa en Khan Academy](https://es.khanacademy.org/computer-programming/new/pjs)

2. Copia el siguiente código, vamos a pintar una estrella en el plano:

```javascript
var x = 200;
var y = 200;

background(202, 255, 97);
fill(66, 66, 66);

var estrella = function(x,y) {
    triangle(x,y,x-50,y-50,x-100,y);
    triangle(x,y-25,x-50,y+25,x-100,y-25);
};

estrella(x,y);
```

3. Pinta otra estrella en 300, 300:

```javascript
estrella(300,300);
```

4. Ejercicio: Usa un ciclo while para pintar 3 estrellas en : (100, 100) , (100, 200) y (100, 300)
Recuerda que los ciclos while se escriben de la siguiente manera:
```javascript
var  numero= 0;
while( numero<3  ){
  println(numero);
  numero++;
}
```

4. Ejercicio: Usando arreglos y un ciclo pinta 4 estrellas en (50, 100) , (100, 100), (150, 100) y (200, 100)
Pista: Crea 2 arreglos llamados coordenadasX y coordenadasY con 4 elementos y usalos para guardar las coordenadas luego usa un ciclo for para pintar las estrellas

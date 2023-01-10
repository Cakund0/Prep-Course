Objetos:    Los objetos son similares a los Arrays, listas de datos, con la diferencia que los 
            objetos pueden contener mucha informacion sobre un mismo elemento, por ejemplo un usuario
            al que le agregamos nombre, edad, email, etc. con un array se haria muy complicado.

Propiedades:    Las Propiedades son esta informacion que vamos a meterle a los objetos; se dividen
                en keys y values, las keys son el nombre que le vamos a poner a esta propiedad,
                por ejemplo 'Nombre' y las values son los valores que toman estas propiedades, por
                ejemplo 'Facundo', solo puede haber una key de cada una, es decir, no se puede repetir
                el nombre, pero muchas keys pueden tener el mismo value, que puede ser cualquier tipo
                de dato de JS(strings, numeros, true/false, undefined, null, funciones, arrays
                otros objetos..).

Métodos:        Los métodos son funciones dentro de los objetos, las llamaremos de esta manera
                cuando usemos una funcion como un value.

Bucle For In:   Los bucles for ... in sirven cuando queremos recorrer las propiedades de un objeto,
                a diferencia de los arrays, los objetos no tienen indices numericos, por lo que la
                manera de recorrerlo es con este bucle, escribiendo for(let 'una clave' in 'nombre del objeto'){}.

Notaciones:     La forma de acceder a la información dentro de los objetos es con las notaciones,
                funciona de la misma manera que el indice en los arrays (array[i]) solo que dentro de los corchetes pondremos el nombre de la key que nos interesa buscar. Tambien existe la DotNotation, escribiriamos el nombre del objeto, un punto y la propiedad,
                (objeto.propiedad).
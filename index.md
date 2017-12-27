title: Code In The Dark DevsChile / Santiago - Diciembre 2017
author:
  name: DevsChile
  twitter: devschile
  url: https://devschile.cl
output: index.html
theme: juanbrujo/cleaver-beerjs
controls: true

--

# Code In The Dark DevsChile / Santiago - Diciembre 2017

--

# Code challenge 0

Parsear un csv con información demográfica de Chile.

- Exponer api con filtro por año.
- Entregar promedio, mínimo, máximo y moda de hombres y mujeres por región.

--

# Code challenge 1

Crear un chat simple entre dos usuarios (1:1)

- Cada cliente puede enviar y recibir mensajes
- Cifrar mensajes usando el método César
- Solo letras (AZ-az)

## Cifrado César
- **Alfabeto en claro:** A B C D E F G H I J K L M N Ñ O P Q R S T U V W X Y Z
- **Alfabeto cifrado:** D E F G H I J K L M N Ñ O P Q R S T U V W X Y Z A B C

--

Obtener el valor numérico de un carácter

```
js: 'a'.charCodeAt(0) => 97
python: ord('a') => 97
php: ord('a') => 97
ruby: 'a'.ord => 97
```
Obtener el carácter desde un valor numérico

```
js: String.fromCharCode(97) => 'a'
python: chr(97) => 'a'
php: chr(97) => 'a'
ruby: 97.chr => 'a'
```
--

# Code challenge 2

```json
{
  "error": "Error 404"
}
```

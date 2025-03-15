# OrganizarBiblioteca
aplicacion en C# para organizar mi biblioteca de libros en pdf

## Pasos a seguir

1. Obtener los nombres de los libros y guardarlos en un array de paths de los libros. 
2. Una vez que se tiene completo el array se crea otro array de la misma dimension inicializado en "no isbn"
3. Usando el array de paths, ir libro por libro en el array y por cada uno de ellos extraer el isbn y guardarlo en el array isbn.
4. una vez que tenemos ese array isbn vamos a recorrerlo ignorando los espacios donde no se encontro isbn, por cada isbn encontrado se usara un api de google para obtener informacion del libro, lo primero titulo, autores, editorial, annio de publicacion.
5. esta informacion obtenida se guardara en un json. 
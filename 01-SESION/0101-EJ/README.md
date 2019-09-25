## Seccion 01: Ejemplo 01
# Ejemplo sin border box.
1. Creamos un div rellenado con lorem automaticamente con el codigo: div{ lorem }
2. En el css le damos un tamaño inicial a la caja de 20 rem.
3. Después le damos un padding de 5rem.
4. Luego le añadimos un borde de 20 px.

```
div{
    width: 20rem;
    height: 20rem;
    background-color: salmon;
    padding: 5rem;
    border: 20px solid blue;
}
```
Como podemos ver, la  caja aumentó de 20rem a 30 rem + 40 px, para que en vez de expanderse, hacer que se mantenga en 20 rem, añadimos el box-sizing:
´´´
div{
    box-sizing: border-box;
    width: 20rem;
    height: 20rem;
    background-color: salmon;
    padding: 5rem;
    border: 20px solid blue;
}
```
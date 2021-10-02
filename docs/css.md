# CSS

## Como funciona?
- CSS funciona mediante la vinculacion de elementos y selectores

## Elementos
- Los elementos basicamente son nuestros tags de html
- Ejemplo
  * body
  * p
  * head
  * a
  * table
  * div
  * img

## Selectores
- Lo selectores son los identificadore de los elementos
- Tipos
  * id => El id debe ser unico
  * class => La clases se pueden compartir
-- Ojo: Todos los elementos de html pueden conter un id y una class

- Como accedo a los elementos que tienes selectores?
Esto depende del tipo de de selector 
- Si el selector es un id
```
<a id="link" hre="google.com">Ir a google</a>
```

```
#link {
  font-family: Helvetica;
  color: "#f01"
}
```

- Si el selectore fuera una clase

```
<a class="link" hre="google.com">Ir a google</a>
```

```
.link {
  font-family: Roboto;
  color: "#0f1"
}
```

- Cual se recomienda usar?

Por recomendacion se debe usar mayormente ```class```


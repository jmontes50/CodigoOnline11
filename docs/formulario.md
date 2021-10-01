# Formulario

## Radio (Radio Button)
- Usamos radio cuando tenemos un conjunto de opciones y solo queremos que el usuario escoja 1
* Plan de pagos (Netflix) => 3 planes y solo que el usuario tenga 1
* Plan de celular => Solo quiere que tengas 1
* Curso junior - intermedio - avanzado

## Checkbox
- Usamos checkbox cuando queremos que el usuario marque mas de una opcion
* Netflix (Cuando entremos por primera y nos permite seleccionar multiples generos de pelicula o series)
* Lista de mercado (marcamos las opciones que compramos)
* compras un carro (escoger y marcar las opciones de tu carro)

## checked
- Permite que mi checkbox o radio esten marcados por defecto

## readonly vs disabled

### readonly
- Se usa cuando queremos hacer que un input no sea editable, pero queremos mantener su valor al momento de enviar la informacion

### disabled
- Se usa cuando queremos hacer que un input no sea editable, pero esto no conserva el valor

* Porque al momento de enviar la informacion, sabemos que enviamos el valor de cada input, pero si el input tienen la proiedad *disabled* este valor sera nulo, sin embargo si usad *readonly* el valor sera enviado
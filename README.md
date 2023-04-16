# M04UF1
Cyberseguridad: Llenguatge de Marques

## XML

XML es un formato de texto mediante **etiquetas**
>
Usos de XML:

Almacenamiento de datos entre plataformas
>
Se transforma al formato deseado: **HTML, XHTML, etc**

Ejemplo XML: 

?xml version="1.0" encoding="UTF-8" ?>
xsd:schema xmlns:xsd="http://www.w3.org/2001/XMLSchema">
!DOCTYPE character SYSTEM "character.dtd">
>
\<characters\> 
>
	<character id_character="1">
	
		<name\>Eustaquio\</name>
		
		<surname>Mendoza</surname>
		
		<race\>Enano\</race\>
		
		<class>Artificiero</class>
		
		<gender abbrev="N">Non-Binary</gender>
		
		<height cm="130" />
		
		<weight kg="80" />
		
		<language abbrev="prt">Portugués</language>
		
		<TieneLaESO />
		
		<weapons>
		
			<weapon id_weapon="1" />
			
			<weapon id_weapon="3" />
			
			<weapon id_weapon="7" />
			
			<weapon id_weapon="2" />
			
	</character>
>
>**Etiquetas:** Parte principal que analiza el doc XML. Dos etiquetas, de apertura y de cierre.
>
>Cada Etiqueta debe tener su cierre, se pueden crear etiquetas EMPTY
>
>**CDATA:** trata el texto como puro
>
>**Schemas:**


## DTD 

Ejemplo DTD

> La vida es una lenteja
> O la toma o la deja
>
>> Guacamole 2024-2001


---

Esto es un enlace a la mejor web del mundo:

[CondorChem](https://condorchem.com)

Y [ESTO](https://enti.cat) es otro enlace

### Imagen incrustada

![Lenteja](https://recetinas.com/wp-content/uploads/2020/01/lentejas-con-chorizo.jpg)

### Listas de tareas

- [ ] Primera tarea
- [x] Segunda tarea
- [ ] Tercera tarea

### Carácteres  extendidos

:poop: :alien: :cry: :imp:

### Estilo de carácteres

**cursiva* _cursiva_

**negrita** __negrita__

~~TACHADO~~

~~***tachado negrita y cursiva***~~

### Tablas

| id_character | name | age | level |
| --- | --- | --- | --- |
| 1 | Eustaquio | 197 | 99 |
| 2 | Mariana | 20 | 100 |
| 3 | Messi | 44 | 32 |

\* ejemplo de escapado


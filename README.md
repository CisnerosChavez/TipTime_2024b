# Calculadora de Propinas

Este proyecto consiste en una aplicación básica de calculadora de propinas. A lo largo del codelab, hemos desarrollado una interfaz de usuario (IU) funcional para la aplicación. Aunque en la etapa inicial la aplicación no calculaba la propina, en los siguientes codelabs implementamos la funcionalidad necesaria para que la aplicación no solo funcione correctamente, sino que también tenga un aspecto más profesional.

## Características

- **Interfaz de Usuario**: La aplicación cuenta con una IU intuitiva y fácil de usar.

## Detalles Técnicos

- **XML**: Usamos XML para definir el diseño de la aplicación.
- **EditText**: Permite al usuario ingresar o editar texto. Incluye sugerencias para indicar lo que se espera ingresar en ese campo.
- **android:inputType**: Especifica el tipo de texto que el usuario puede ingresar en un campo EditText.
- **RadioButtons y RadioGroup**: Creamos una lista de opciones exclusivas con RadioButtons, agrupadas con un RadioGroup, que puede ser vertical u horizontal. Especificamos qué RadioButton debe aparecer seleccionado inicialmente.
- **Switch**: Permite que el usuario active o desactive dos opciones. Se puede agregar una etiqueta a un Switch sin usar una TextView independiente.
- **ConstraintLayout**: Cada elemento secundario debe tener restricciones verticales y horizontales. Usamos las restricciones de "inicio" y "fin" para controlar los idiomas que se leen de izquierda a derecha (LTR) y de derecha a izquierda (RTL). Los nombres de los atributos de restricción siguen el formato `layout_constraint<Source>_to<Target>Of`. Para hacer que una View sea tan ancha como el ConstraintLayout en el que se encuentra, restringimos el inicio y el fin a aquellos del elemento superior y establecemos el ancho en 0 dp.

 ## Captura de pantalla
 ![Imagen de WhatsApp 2024-09-03 a las 22 29 07_19fdfa05](https://github.com/user-attachments/assets/152422ca-8587-4abe-91d9-23aed2de9390)

 
![Imagen de WhatsApp 2024-09-03 a las 22 29 07_98bb4dc4](https://github.com/user-attachments/assets/80f78c8d-02a3-4498-b7ba-e8ee4efd9e57)

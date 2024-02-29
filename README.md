# Práctica para Final

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)


**Bootstrap:** El siguiente es un ejemplo dónde se utilizan las clases `row`, `col-x`, y otras intentando minimizar el uso de css propio para intentar aprovechar lo máximo posible este framework.

![Maqueta de ejemplo](./assets/img/Maqueta.jpg)

>**Algunas clases útiles**
>*   `mb-X` margin abajo de tamaño X
>*   `mt-X` margin arriba de tamaño X
>*   `ms-X` margin izquierdo de tamaño X
>*   `me-X` margin derecho de tamaño X
>*   `pb-X` padding abajo de tamaño X 
>*   `pt-X` padding arriba de tamaño X 
>*   `ps-X` padding izquierdo de tamaño X 
>*   `pe-X` padding derecho de tamaño X
>*   `text-center` centra texto
>*   `text-end` texto a la derecha
>*   `align-items-center` pone al centro a los elementos         
>*   `align-items-end` pone los elementos abajo
>*   `justify-content-center` elementos al centro
>*   `justify-content-end` elementos a la derecha
>
>*Nota: Align alinea entre arriba y abajo. Justify alinea entre derecha e izquierda*

## Para sacarle el subrayado a los links:

Hay que aplicarle el cambio al selector a:

>`a:link, a:visited, a:active {`
>            `text-decoration:none;`
>`}`

lo cual va a afectar a todos los links de la página, incluso a los de arriba. Los cuales no queremos modificar. O se puede crear una clase links para que se aplique solo a los links deseados.
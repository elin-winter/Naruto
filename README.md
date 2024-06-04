
Parte A
En este mundo conocemos el nombre, las herramientas,
los jutsus y el rango de cada ninja. El rango es un
número que comienza en 0 y no puede ser negativo.
Las herramientas ninjas son de mucha ayuda para
realizar misiones. De cada una conocemos el nombre y
la cantidad disponible. Algunos ejemplos son: bombas de
humo, kunais, shurikens y sellos explosivos. Para poder
utilizarlas se pide modelar:
a. obtenerHerramienta: cada ninja debe poder
obtener una cantidad específica de una herramienta en particular teniendo en cuenta
que:
i. si la suma de todas sus herramientas más la cantidad a obtener es menor o
igual a 100, puede hacerlo sin problemas;
ii. en caso contrario, obtiene la cantidad que pueda sin excederse de 100
herramientas.

b. usarHerramienta: cuando un ninja usa alguna de sus herramientas no mide cuántas
utiliza, por lo que se queda sin ella y no debe figurar más entre sus pertenencias.

Parte B
En su vida cotidiana, cada ninja tiene que cumplir misiones. Por suerte no es un trabajo
solitario, ¡trabajan en equipos! De cada misión se especifica qué cantidad de ninjas
requiere, el rango recomendable para realizarla, qué ninjas enemigos hay que derrotar y la
herramienta (¡obviamente con su cantidad!) de recompensa en caso de cumplirla con éxito.
Se pide modelar:
a. esDesafiante: dado un equipo de ninjas, una misión es desafiante cuando al menos
alguien del equipo tiene menor rango que el recomendado y hay que derrotar al
menos 2 enemigos.
b. esCopada: esto pasa cuando la recompensa de la misión son 3 bombas de humo, 5
shurikens o 14 kunais.
c. esFactible: para que una misión sea factible no tiene que ser desafiante y además
el grupo debe contar con la cantidad de ninjas necesaria o la suma total de
herramientas del equipo debe ser superior a 500.

Las misiones se pueden completar con éxito o no:
d. fallarMision: la vida no siempre es fácil... ni en nuestro mundo ni en el mundo ninja.
Cuando una misión falla sólo quedan en el equipo quienes tengan el rango
recomendado o superior. Quienes queden sufrirán la vergüenza de ver su rango
disminuido en 2 unidades. ¡Por el resto del equipo no te preocupes! Te prometemos
que están bien. 😝
e. cumplirMision: si todo sale bien, se promociona de rango a cada miembro del
equipo. Además obtendrán la recompensa teniendo en cuenta la restricción del
máximo de herramientas.

¡Todavía no hablamos de los jutsus! Técnicas especiales que nacen de la energía interior de
cada ninja. Es como un superpoder que hace que las misiones sean más simples 😅.
Algunas de las que conocemos son:

f. clonesDeSombra: reduce la cantidad de ninjas que se necesitan para una misión
en el mismo número que los clones de sombra creados. ¡El tamaño del equipo no
puede ser menor a 1!
g. fuerzaDeUnCentenar: elimina a todos los enemigos con rango menor a 500.

¡Hora de la acción! Se pide modelar ejecutarMision. Cuando se ejecuta una misión, todos
los ninjas del grupo usan todos sus jutsus en la misión. Luego, si la misión es copada o
factible, se cumple. Caso contrario la misión se falla.
Parte C

Existe la Gran Guerra Ninja, una misión de rango 100
que necesita al menos 100000 ninjas para
completarse, tiene infinitos enemigos y su
recompensa es el abanico de Madara Uchiha.

Se pide modelar la granGuerraNinja sabiendo,
además, que tiene infinitos villanos y son Zetsu 1,
Zetsu 2, Zetsu 3... Zetsu N, el rango de todos es de
600 y no tienen jutsus ni herramientas.

Sabiendo esto y teniendo en cuenta un equipo de
ninjas finitos, responder qué devuelve y por qué en las
siguientes funciones:
a. esDesafiante
b. esCopada
c. fuerzaDeUnCentenar

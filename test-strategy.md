
Plan de Ataque

Titulo: Juego Adivina tu número	

1. Al ingresar el numero y darle click al boton "Ingresar el número aleatorio", no muestra ningun mensaje.
	
	Razón del error: En linea 87, el metodo addeventlistener esta escrito incorrectamente
	Solución: Reemplazar el metodo a addEventListener

2. Al darle click al boton solo muestra mensaje de incorrecto en verde sin mostrar si el numero se necesita mayor o menor.

	Razón del error: En linea 44 el numero no era aleatorio
	Solución: Cambiar a funcion aleatoria.

3. Los mensajes no tienen el color correcto.

	Razon del error: desde linea 63 el orden no estaba correcto en los eventos lastResult.style.backgroundColor
	Solución: Se reemplazo el orden y añadiendo los colores correctos.

4. Los intentos no eran correctos.

	Razon del error: :la constante attemps tenia el numero 5 significando que con solo 5 intentos el juego finaliza
	Solución: se elimino el attempt y se reemplazo por el numero correcto en el evento del fin de juego con el numero 10

5. No inicia un nuevo juego al finalizar y darle click al boton Comienza un Nuevo Juego.
	Razon del error: EN linea 95 el metodo esta escrito como addeventlistener.
	Solución: se reemplazo por addEventListener.		

				
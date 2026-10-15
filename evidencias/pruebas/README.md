# Pruebas ejecutadas

Las siguientes comprobaciones se realizaron ejecutando los programas desde la terminal y probando sus menús:

| Programa | Operaciones probadas | Resultado esperado y observado |
|---|---|---|
| `pila_guiada.py` | Retirar un libro y consultar la pila | Se retira el último libro agregado; el libro anterior queda en el tope. |
| `reto1_bodega.py` | Mostrar cinco cajas, retirar la superior y consultar el tope | Se muestran cinco cajas; se retira `CAJA-05` y queda `CAJA-04` en el tope. |
| `pila_acciones.py` | Deshacer con pila vacía, registrar texto vacío y elegir opción incorrecta | Informa que no hay acciones, rechaza el texto vacío y avisa que la opción no es válida. |
| `reto2_navegador.py` | Visitar tres páginas y retroceder tres veces | El orden de regreso es `python.org`, `uam.edu.ni` y `No existen páginas anteriores.` |
| `cola_guiada.py` | Atender al primero, mostrar la cola y registrar nombre vacío | Se atiende primero a Ana, quedan Luis y María y se rechaza el nombre vacío. |
| `reto3_atencion.py` | Registrar cinco clientes, atender y consultar la fila | Se atiende primero el turno 1 (Ana); quedan cuatro clientes en orden FIFO. |
| `reto1_bodega.py` | Registrar y retirar un código largo | El código completo se muestra dentro de la caja y se puede retirar. |

Los programas también se revisaron para confirmar que no importan módulos ni bibliotecas. Estas pruebas no requieren instalar nada.

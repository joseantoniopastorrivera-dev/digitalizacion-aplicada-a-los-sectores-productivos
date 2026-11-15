# Mecanizados Henares: una fábrica que se entera de sus fallos a tiempo

Grupo 1 · Industria

## De dónde partimos

Nos ha tocado la fábrica que quiere reducir errores y mejorar la producción. Para no hablar en abstracto nos hemos inventado una: **Mecanizados Henares**, un taller de unas 40 personas que fabrica piezas metálicas para automoción. Tiene seis máquinas de control numérico y un problema muy típico: los fallos se descubren al final, cuando la pieza ya está hecha y hay que tirarla, o cuando una máquina se para a mitad de turno.

Lo primero que se nos ocurrió fue la robótica colaborativa, porque es lo que todo el mundo imagina al pensar en una fábrica moderna. La descartamos enseguida. Un robot hace el trabajo más rápido, pero si la máquina está mal ajustada, fabrica piezas malas más rápido. El problema del enunciado no es la velocidad, es no saber qué está pasando.

## Las dos tecnologías que elegimos

**Internet de las cosas (IoT)** y **gemelo digital**. Van juntas: la primera recoge los datos y la segunda les saca partido.

| Qué ponemos | Qué mide o hace | Para qué nos sirve |
|---|---|---|
| Sensores de vibración y temperatura en cada máquina | El estado del husillo y de los rodamientos | Ver que algo se está desgastando antes de que se rompa |
| Contador de piezas y medición a la salida | Cuántas piezas salen y cuántas se rechazan | Saber en qué máquina y en qué turno aparecen los defectos |
| Gemelo digital de la línea | Una copia virtual que se alimenta de esos datos | Probar un cambio en el ordenador antes de tocar la línea real |

## Cómo lo aplicaríamos

No lo montaríamos todo de golpe. Empezaríamos por la máquina que más paradas da, porque es donde antes se nota si funciona. Los sensores mandan los datos por la red de la planta (la parte OT) y el gemelo los recibe en tiempo real.

El gemelo tiene dos usos. El primero es el **mantenimiento predictivo**: si una máquina empieza a vibrar más de lo normal, avisa y se cambia la pieza en una parada programada, no en mitad de un pedido urgente. El segundo es probar cambios. Si queremos subir la velocidad de corte o cambiar el orden de un pedido, lo simulamos antes y vemos si aparece un cuello de botella.

## Qué mejora

- Se tiran menos piezas, porque el defecto se ve cuando empieza y no al final del lote.
- Hay menos paradas por sorpresa. Las que hay se planifican.
- La oficina deja de preguntar por teléfono cómo va un pedido: los datos de planta llegan solos a gestión. Es justo la conexión entre IT y OT que vimos en la unidad 1.
- Los cambios se deciden con datos y no con «siempre se ha hecho así».

## Sostenibilidad

Aquí la relación es bastante directa. Cada pieza defectuosa es acero, electricidad y horas de máquina que no han servido para nada. Si se tiran menos piezas, se gasta menos de todo eso. Además, una máquina bien mantenida dura más años y consume menos que una que trabaja forzada.

Hay una pega que no queremos esconder: los sensores y los servidores también consumen y también hay que fabricarlos. Creemos que compensa de sobra, pero habría que medirlo y no darlo por hecho.

## El nuevo servicio

**Seguimiento del pedido para el cliente.** Como ya sabemos en qué fase está cada lote, se lo podemos enseñar al cliente en una web: en fabricación, en control de calidad o listo para enviar, con la fecha prevista. Para una empresa de automoción, que trabaja con plazos muy ajustados, saber con antelación que un pedido se retrasa dos días vale mucho.

## Transparencia

> **MECANIZADOS HENARES · FALLOS A TIEMPO**
> **Problema:** los errores se ven al final y las máquinas paran sin avisar.
> **IoT:** sensores de vibración, temperatura y recuento de piezas.
> **Gemelo digital:** copia virtual de la línea para predecir averías y probar cambios.
> **Mejoras:** menos piezas tiradas, paradas planificadas, oficina y planta conectadas.
> **Sostenible:** menos acero y energía desperdiciados, máquinas que duran más.
> **Nuevo servicio:** el cliente sigue su pedido en una web.

## Lo que diríamos en los 2 minutos

- **El problema (20 s).** «Somos Mecanizados Henares, un taller de piezas para coches. Nuestro problema es que nos enteramos de los fallos tarde: cuando la pieza ya está hecha o cuando la máquina se ha parado».
- **Las tecnologías (30 s).** «Hemos elegido IoT y gemelo digital. Ponemos sensores en las máquinas que miden vibración y temperatura, y con esos datos montamos una copia virtual de la línea. Esa copia nos avisa cuando una máquina empieza a ir mal y nos deja probar cambios sin arriesgar la producción».
- **Mejoras y sostenibilidad (35 s).** «Tiramos menos piezas y las paradas pasan a ser planificadas. La oficina ve los datos de planta sin tener que bajar a preguntar. Y cada pieza que no tiramos es acero y electricidad que no desperdiciamos. Descartamos los robots porque hacer más rápido algo que sale mal no arregla nada».
- **El nuevo servicio (35 s).** «Con esos mismos datos, el cliente puede ver en una web en qué fase está su pedido y cuándo le llega. Si hay retraso lo sabe antes, y eso en automoción es lo que más se valora. Así que con dos tecnologías arreglamos el problema de dentro y además damos algo nuevo hacia fuera».

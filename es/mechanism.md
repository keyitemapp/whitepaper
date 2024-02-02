# Mecanismo de Pago para Jugadores

Las tarifas de juego pagadas por los jugadores para juegos de arcade se distribuyen en la tabla de clasificación del juego.

Ejemplo）Tabla de Clasificación de Dragotchi Parkour Race
<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/exampleLeaderBoard.png" alt="Ejemplo de Tabla de Clasificación" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

Por ejemplo, si la tasa de distribución de Alice es del 33.74%, cuando alguien juega, aproximadamente 0.3374 USD de la tarifa de juego de 1 USD se transfiere a la billetera de Alice.

El algoritmo para determinar la tasa de distribución en las carreras de Dragotchi se establece de modo que la tasa de distribución del jugador que corrió más lejos entre los que no alcanzaron la META sea la mitad de la tasa del jugador más lento entre los que sí lo hicieron. La tasa de distribución se determina en proporción a la puntuación (entre jugadores que alcanzaron la META, se basa en la velocidad del tiempo; entre los que no lo hicieron, se basa en la distancia recorrida).

Las clasificaciones no se restablecen como regla general. Si se va a realizar un restablecimiento, se anunciará en Discord al menos con 14 días de anticipación. Cada juego tiene un algoritmo diferente para determinar la tasa de distribución, pero nuestro objetivo es idear y adoptar un algoritmo lo más justo posible. Los detalles del algoritmo de tasa de distribución del juego se organizarán y publicarán en la sección de algoritmos.

<div style="display: flex; flex-direction: row; align-items: center;">
    <div style="max-width: 50%;">
        <img src="../images/paymentworld.webp" alt="paymentworld" style="max-width: 100%; height: auto;">
    </div>
    <div style="max-width: 50%;">
    </div>
</div>

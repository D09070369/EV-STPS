Descripción para el Repositorio
EVSTSP-Benchmarks: Instancias para el Problema del Vendedor Viajero Steiner con Vehículos Eléctricos
Este repositorio contiene el conjunto de instancias de benchmark para el Problema del Vendedor Viajero Steiner con Vehículos Eléctricos (EV-Steiner-TSP), desarrolladas para la investigación presentada en el capítulo de libro:

"Solución del Problema del Vendedor Viajero Steiner con Vehículos Eléctricos (EV-Steiner-TSP) mediante un Algoritmo Genético Multi-Objetivo Híbrido con Q-Learning".

El propósito de este conjunto de datos es proporcionar un recurso estandarizado para la comunidad investigadora, facilitando la replicabilidad de los resultados y la comparación de nuevos algoritmos de solución para esta compleja variante de los problemas de ruteo de vehículos.

Características de las Instancias
Todas las instancias están en formato JSON y han sido generadas sintéticamente para modelar escenarios logísticos realistas, incorporando las siguientes características clave:

Problema Base: Steiner Traveling Salesman Problem (STSP), con un subconjunto de clientes requeridos (required_customers) que deben ser visitados obligatoriamente.

Restricciones de Vehículo Eléctrico (EV):

Batería: Capacidad limitada, estado de carga inicial y reserva de seguridad.

Estaciones de Recarga: Un conjunto de nodos designados como estaciones (stations) donde el vehículo puede recargar su batería.

Naturaleza Bi-Objetivo: Los arcos del grafo tienen costos independientes para:

Distancia (dist_m en metros).

Consumo Energético (energy_kWh en kilovatios-hora).

Grafo Dirigido: Las conexiones entre nodos son dirigidas, lo que significa que el costo del arco (u, v) puede ser diferente al del arco (v, u).

Uso
Cada archivo JSON puede ser cargado directamente en Python u otros lenguajes de programación para ser utilizado como entrada para algoritmos de optimización. La estructura de los datos está diseñada para ser auto-contenida y fácil de interpretar.

Citación
Si utilizas estas instancias en tu investigación, por favor, cita el capítulo de libro asociado:

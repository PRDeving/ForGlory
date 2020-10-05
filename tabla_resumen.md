## For Glory v3.1.0 rev. Oct/2020

## Tablas Resumen

### [Medidas](index.md#medidas)

- XS (eXtra Small) 2" - 5cm - 500m
- S (Small) 4" - 10cm - 1km
- M (Mid) 6" - 15cm - 1.5km
- L (Large) 8" - 20cm - 2km
- XL (eXtra large) 10" - 25cm - 2,5km

### [Victoria](index.md#victoria)

- 1 punto por cada unidad enemiga destruida
- 2 puntos adicionales por cada división enemiga completamente destruida
- 1 punto por cada punto estratégico bajo control al final de la partida
- 4 puntos por cada punto estratégico arrebatado al enemigo
- 2 puntos por cada oficial capturado y forzado a recolocarse
- 4 puntos por capturar el estado mayor

### [Categoría de unidades](index.md#categoría-de-unidades)

| Código | Categoría           | tipo       | Alcance | Mod Disparo | Mod Cuerpo a Cuerpo | Movimiento base | Terreno Dificil |
| ---    | ---                 | ---        | ---     | ---         | ---                 | ---             | ---             |
| LnInf  | Infantería de Línea | Infantería | XS      | 0           | 0                   | S               | S               |
| LI     | Infantería Ligera   | Infantería | S       | +1          | -1                  | S               | S               |
| HC     | Caballería Pesada   | Caballería | -       | -           | +3                  | M               | S               |
| LC     | Caballería Ligera   | Caballería | -       | -           | +2                  | L               | M               |
| FA     | Artillería a pié    | Artillería | L       | -1          | -2                  | S               | -*              |
| HA     | Artillería montada  | Artillería | M       | -2          | -1                  | M               | S               |
| OFF    | Oficial             | -          | -       | -           | -                   | L**             | L**             |

\* *No puede terminar a más de XS de una carretera*

\*\* *Ignora terreno*

### [Calidad de unidades](index.md#calidad-de-unidades)

| Código | Calidad   | Mod |
| ---    | ---       | --- |
| M      | Milicia   | -2  |
| I      | Irregular | -1  |
| R      | Regular   | 0   |
| V      | Veterano  | +1  |
| E      | Élite     | +2  |

### [Chequeo de moral](#index.mdchequeo-de-moral)

- +2 si el oficial está a XS o menos
- -1 por cada contador de brigada perdida del oficial de la división.
- -1 por cada impacto en la unidad
- -1 si la unidad está desorganizada

### [Chequeo de liderazgo](#index.md#chequeo-de-liderazgo)

- +2 si está a XS o menos del estado mayor
- -1 por cada contador de brigada perdida
- -1 por cada tramo de XL que lo separe del estado mayor, redondeado hacia arriba (si el oficial se encuentra a 8" del estado mayor tendrá -1, a 12" del estado mayor tendrá -2 y a 38" tendrá -4 a la tirada)

### [Combate](index.md#combate)

| General                                | Mod |
| ---                                    | --- |
| Por el flanco o retaguardia            | +2  |
| Objetivo marchando por carretera       | +1  |
| Enemigo a cubierto                     | -1  |
| [Desorganizado](index.md#fase-de-activaciones) | -1  |
| Mover y disparar                       | -1  |
| Carga de frente                        | -1  |
| Por cada contador de impacto           | -1  |
| Como [reacción](index.md#acciones-de-reacción) | -2  |

| Disparo Artillería                                        | Mod |
| ---                                                       | --- |
| Objetivo a XS o menos                                     | +2  |
| Por cada contador de artillería a XS o menos del objetivo | +1  |

| Resultado | Disparo                    | Cuerpo a Cuerpo                                            |
| ---       | ---                        | ---                                                        |
| 0 - 2     | Fallo                      | Empate. Ambos bandos reciben un impacto y son empujados XS |
| 3         | Enemigo Empujado XS        | Enemigos Empujados XS                                      |
| 4 - 6     | Impacto y empujado XS      | Enemigos reciben 2 impactos y son empujados XS             |
| 7+        | Dos impactos y empujado XS | El enemigo es destruido                                    |
| 10+       | Enemigo destruido          | -                                                          |


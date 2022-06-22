# T

## Time Lost
````{tab-set}
```{tab-item} Definition

The time involved between decceleration to a stop/station and boarding the first passenger; the time involved between acceleration from stationary to operating {ref}`S:Speed`.
```
````

(T:Timepoint)=

## Timepoint
````{tab-set}
```{tab-item} Definition

A designation given to specific stops or stations spaced out along a route, where actual arrival and departure times are recorded.

Timepoints are used on most timetabled routes, to track {ref}`O:OTP`. Sometimes, recovery time is built into timepoints as well.

Considerations when selecting timepoints include:
* Ridership
* Position along the route
* Distance between previous and next stops
```
````

## Timed Transfer
````{tab-set}
```{tab-item} Definition

A scheduling tactic that attempts to line up {ref}`T:TransitUnit` arrivals between two routes at an interchange, ensuring passengers can switch between them.

Timed transfers are best used at major interchanges, where transfers are expected to be high. This tactic helps improve passenger travel times by reducing transfer {ref}`W:Wait`.

```
````

(T:Trip)=

## Trip
````{tab-set}
```{tab-item} Definition

A sequence of two or more stops (or stations) that will occur at specific times, from an origin start terminal to end destination terminal.

A trip is the fundamental building block of a public transport service {ref}`S:Schedule`.

This is often easily confused with a {ref}`R:Run`, which is the overall assignment that an operator is given including {ref}`D:Deadhead`, Trips, and {ref}`L:Layover`.
```
````

(T:TransitUnit)=

## Transit Unit
````{tab-set}
```{tab-item} Definition
abbrev. "TU"

One or more vehicles travelling and operating together as a physical unit.
```

```{tab-item} Examples

An eight-carriage train would be considered one TU, composed of eight vehicles.
A single bus would also be considered as one TU.
```
````

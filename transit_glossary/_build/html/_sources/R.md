# R

## Real-Time Passenger Information
```{tabbed} Definition
abbrev. "RTPI"


```
## Recovery Time
```{tabbed} Definition

The time built into a {ref}`S:Schedule` in-between a {ref}`T:TransitUnit`'s arrival and destination time, to catch up on potential delays.

{ref}`L:Layover` Time can be considered as a specific type of recovery time.

Building in recovery time is an important element of scheduling to consider, especially when roadside conditions are known to be unpredictable and volatile.
```

## Revenue Service
```{tabbed} Definition

The span of time a {ref}`T:TransitUnit`

```

(R:Ridership)=
## Ridership
```{tabbed} Definition
a.k.a. "Passenger Volume"

The volume of passengers using a public transportation service. Generally counted as the number of unlinked {ref}`B:Boarding`s (which excludes transfers), but can also be counted as every boarding action taken on a system.

Ridership is often counted using {ref}`A:APC`s.

```
```{tabbed} Application
Metrics:
* Discrete number i.e. number of rides
* Number per time (in months or years)
```

(R:ROW)=
## Right-of-Way
```{tabbed} Definition
abbrev. "ROW"

A legally exclusive and physically separated strip of land for use by public transport vehicles.
```
```{tabbed} Application

In the USA, ROWs are differentiated along three categories:
* Category A: A fully controlled Right-of-Way, generally {ref}`G:Grade` without crossings, such as a fully underground train line.
* Category B: A physically defined and separated ROW, but with at-grade crossings such as street intersections.
* Category C: A ROW integrated at surface street level, mixed in with other modes of transportation and pedestrians.

```

## Rolling Stock
```{tabbed} Definition
The railway-based {ref}`T:TransitUnit`s that make up a {ref}`F:Fleet`. Rolling stock can be powered or unpowered.

In the USA, rolling stock can also refer to any public transport vehicle, ranging from buses to train carriages to auxiliary support vehicles.
```

(R:Run)=
## Run
```{tabbed} Definition
The tasks assigned to operators during a day. Runs may consist of a partial, one whole, or more than one block (see {ref}`B:Blocking`).

This term is easily confused with {ref}`T:Trip`, which refers to the individual operation of a public transport service along a route, and is not operator specific.
```

(R:Runcutting)=
## Runcutting
```{tabbed} Definition
The iterative scheduling process used to develop {ref}`R:Run`s from a vehicle block assignment.

Where {ref}`B:Blocking` is used to optimise the number of vehicles needed in service, Runcutting is used to optimise the number of operators or drivers needed to provide service.
```

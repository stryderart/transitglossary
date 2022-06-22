# R

## Real-Time Passenger Information
````{tab-set}
```{tab-item} Definition
abbrev. "RTPI"

A network of displays, screens, mobile applications, and other devices that enable passengers to directly access live information about their public transport services. It is an integrated system of hardware and software, and is most commonly facilitated by {ref}`G:GTFS`.
```
````

## Recovery Time
````{tab-set}
```{tab-item} Definition

The time built into a {ref}`S:Schedule` in-between a {ref}`T:TransitUnit`'s arrival and destination time, to catch up on potential delays.

{ref}`L:Layover` Time can be considered as a specific type of recovery time.

Building in recovery time is an important element of scheduling to consider, especially when roadside conditions are known to be unpredictable and volatile.
```
````

(R:RevenueService)=

## Revenue Service
````{tab-set}
```{tab-item} Definition

A metric that captures the quantity of productive service a {ref}`T:TransitUnit` has provided, specifically from actively taking passengers during public operation. Time spent on charter or school bus services are generally not accounted for.

```
```{tab-item} Application
Metrics:
* Revenue Service Hours (time in hours)
* Revenue Service Miles (distance in miles)
* Revenue Service Trips (discrete number)

```
````

(R:Ridership)=

## Ridership
````{tab-set}
```{tab-item} Definition
a.k.a. "Passenger Volume"

The volume of passengers using a public transportation service. Generally counted as the number of unlinked {ref}`B:Boarding`s (which excludes transfers), but can also be counted as every boarding action taken on a system.

Ridership is often counted using {ref}`A:APC`s.

```

```{tab-item} Application
Metrics:
* Discrete number i.e. number of Boardings
* Discrete number adjusted i.e. "Unlinked Passenger Trips" as defined by the United States FTA.
* Number per time (in months or years)
```
````

(R:ROW)=

## Right-of-Way
````{tab-set}
```{tab-item} Definition
abbrev. "ROW"

A legally exclusive and physically separated strip of land for use by public transport vehicles.
```

```{tab-item} Application

In the USA, ROWs are differentiated along three categories:
* Category A: A fully controlled Right-of-Way, generally {ref}`G:Grade` without crossings, such as a fully underground train line.
* Category B: A physically defined and separated ROW, but with at-grade crossings such as street intersections.
* Category C: A ROW integrated at surface street level, mixed in with other modes of transportation and pedestrians.

```
````

## Rolling Stock
````{tab-set}
```{tab-item} Definition
The railway-based {ref}`T:TransitUnit`s that make up a {ref}`F:Fleet`. Rolling stock can be powered or unpowered.

In the USA, rolling stock can also refer to any public transport vehicle, ranging from buses to train carriages to auxiliary support vehicles.
```
````

(R:Run)=

## Run
````{tab-set}
```{tab-item} Definition
The tasks assigned to operators during a day. Runs may consist of a partial, one whole, or more than one block (see {ref}`B:Blocking`).

This term is easily confused with {ref}`T:Trip`, which refers to the individual operation of a public transport service along a route, and is not operator specific.
```
````

(R:Runcutting)=

## Runcutting
````{tab-set}
```{tab-item} Definition
The iterative scheduling process used to develop {ref}`R:Run`s from a vehicle block assignment.

Where {ref}`B:Blocking` is used to optimise the number of vehicles needed in service, Runcutting is used to optimise the number of operators or drivers needed to provide service.
```
````

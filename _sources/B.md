# B

(B:Boarding)=

## Boarding
````{tab-set}
```{tab-item} Definition
The entry of passengers into a public transport vehicle.

This is a fundamental measurement of passenger flows in using public transport.
```

```{tab-item} Application
Metrics:
* Discrete number (i.e. 320 passengers)
* Passengers per km travelled per hour.
```
````

(B:BasePeriod)=

## Base Period
````{tab-set}
```{tab-item} Definition
a.k.a "Off-Peak Period"

The time period when services are scheduled at a regular, consistent level. This is contrasted with {ref}`P:PeakPeriod`.

This is the general span of time where public transport services operate on a baseline {ref}`H:Headway` or {ref}`F:Frequency`, not varying in response to demand.
```
````

(B:Blocking)=

## Blocking
````{tab-set}
```{tab-item} Definition

The process conducted by public transport service providers to divide a day's {ref}`S:Schedule` by {ref}`V:Vehicle` assignments.

This is a crucial part of the scheduling process, as it determines the availability of {ref}`T:TransitUnit`s within a day. It is further used in the {ref}`R:Runcutting` process to develop work shifts for operators and calculate the overall labour needed to operate service.
```

```{tab-item} Application

Blocking is done by selecting all the individual {ref}`R:Run`s that a specific vehicle will perform in a day, accounting for {ref}`L:Layover`s. Then, these runs are grouped together into a block, specific to that vehicle.

The goal of blocking is to optimise layover times, and identify where drivers or operators should begin and end their shifts whilst minimising {ref}`D:Deadhead`. Cost-efficient blocking helps agencies minimise operating expenses and the number of vehicles needed.

Where large gaps of time emerge between runs in a block, opportunities for {ref}`I:Interlining` can be identified. A vehicle's assignments serving a different route are also included into the block.

```
````

## Bunching
````{tab-set}
```{tab-item} Definition
* a.k.a "clumping"
A phenomenon where multiple public transport vehicles or {ref}`T:TransitUnit`s (TUs) on the same route are operating in the same place at the same time, thus arriving at stops together or unintended rapid succession. This typically occurs when traffic conditions or other incidents lead to a TU being delayed, thus reducing its {ref}`H:Headway` with the following TU.

This is an important occurrence for service providers to track, as it distorts schedules and passenger expectations, prolonging wait times whilst duplicating the supply of public transport services at a later time.
```
````

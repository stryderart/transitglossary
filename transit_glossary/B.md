# B

(B:Boarding)=
## Boarding

```{tabbed} Definition
The entry of passengers into a public transport vehicle.

This is a fundamental measurement of passenger flows in using public transport.
```
```{tabbed} Application
Metrics:
* Discrete number (i.e. 320 passengers)
* Passengers per km travelled per hour.
```

(B:BasePeriod)=
## Base Period
```{tabbed} Definition
a.k.a "Off-Peak Period"

The time period when services are scheduled at a regular, consistent level. This is contrasted with {ref}`P:Peak Period`.

This is the general span of time where public transport services operate on a baseline {ref}`H:Headway` or {ref}`F:Frequency`, not varying in response to demand.
```
## Blocking
```{tabbed} Definition

The process conducted by public transport service providers to divide a day's {ref}`S:Schedule` by {ref}`V:Vehicle` assignments.

This is a crucial part of the scheduling process, as it determines the availability of {ref}`T:TransitUnit` within a day. It is further used in the {ref}`R:Runcutting` process to develop work shifts for operators and calculate the overall labour needed to operate service.
```
```{tabbed} Application

Blocking is done by selecting all the individual {ref}`R:Run`s that a specific vehicle will perform in a day, accounting for {ref}`L:Layover`s. Then, these runs are grouped together into a block, specific to that vehicle.

The goal of blocking is to optimise layover times, and identify where drivers or operators should begin and end their shifts whilst minimising {ref}`D:Deadhead`.

```
## Bunching
```{tabbed} Definition
* a.k.a "clumping"
A phenomenon where multiple public transport vehicles or {ref}`T:Transit Units` (TUs) on the same route are operating in the same place at the same time, thus arriving at stops together or unintended rapid succession. This typically occurs when traffic conditions or other incidents lead to a TU being delayed, thus reducing its {ref}`H:Headway` with the following TU.

This is an important occurrence for service providers to track, as it distorts schedules and passenger expectations, prolonging wait times whilst duplicating the supply of public transport services at a later time.
```

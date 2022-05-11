# H

## Headsign
```{tabbed} Definition
An information display generally installed on the front and side of public transport vehicles, that states the route or line information such as name, destination, and occasionally places of interest along the route.

Headsigns are important components of a public transport vehicle, providing critical passenger information about the route and the purpose of this service.
```

(H:Headway)=
## Headway
````{dropdown} Actual Headway
```{tabbed} Definition

The duration of time between {ref}`T:TransitUnit` serving a particular route at a given station/stop, at a given time of day. It can be interpreted as the time a passenger spends waiting for a vehicle.

This is important information to understand a public transport service's {ref}`O:OTP`, by examining the difference between Actual Headway and {ref}`P:PolicyHeadway`.

A headway is one way to quantify the level of public transport services offered. It is the inverse of {ref}`F:Frequency`.
```{tabbed} Application
Metrics:
* Minutes per TU. (i.e. a bus every five minutes)

Conversion to frequency...
$$
\frac{1}{Frequency}\
$$
```
````
````{dropdown} Effective Headway
```{tabbed} Definition

The composite time between {ref}`T:TransitUnit`s connecting a particular origin and destination trip ({ref}`O:OD`), accounting for all routes that serve this connection. It is the time a passenger must wait for a vehicle to deliver them to their destination, regardless of what route they take.

```
```{tabbed} Application

Metrics:
* * Minutes per TU. (i.e. a bus every five minutes)

For example, if three bus routes connect stop A with stop D, which respectively run at 15, 13, and 7 minute headways, then the Effective Headway is:

1. Finding the {ref}`F:Frequency` per hour
$$
\frac{60 mins}{15 mins headway}\ + \frac{60 mins}{13 mins headway}\ + \frac{60 mins}{7 mins headway}\ = 17.2 buses per hour
$$
2. Finding the Frequency per minute
$$
\frac{17.2 buses/hr}{60 mins}\ = 0.54 buses per minute
$$
3. Conversion back to Headways
$$
\frac{1}{0.54 buses/min}\ = 1.84 minutes per bus
$$

```
````
(P:PolicyHeadway)=
````{dropdown} Policy Headway
```{tabbed} Definition
The baseline scheduled length of time between {ref}`T:TransitUnit` serving a particular route. It can be interpreted as the baseline (or maximum) time a passenger should generally expect to wait between vehicles, at any station or time of day on a route.

A policy headway is generally used for low demand or low ridership routes, to provide minimal level of service to a region.
```
```{tabbed} Application
Metrics:
* Minutes per TU
```
````

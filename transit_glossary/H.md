# H

##Headsign
```{tabbed} Definition
An information display generally installed on the front and side of public transport vehicles, that states the route or line information such as name, destination, and occasionally places of interest along the route.

Headsigns are important components of a public transport vehicle, providing critical passenger information about the route and the purpose of this service.
```

(H:Headway)=
## Headway
````{dropdown} Actual Headway
```{tabbed} Definition

The duration of time between public transport vehicles serving a particular route at a given station/stop, at a given time of day. It can be interpreted as the time a passenger spends waiting for a vehicle.

This is important information to understand a public transport service's {ref}`O:OTP`, by examining the difference between Actual Headway and {ref}`P:PolicyHeadway`.

A headway is one way to quantify the level of public transport services offered. It is the inverse of {ref}`F:Frequency`.
````
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



```
```{tabbed} Application

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

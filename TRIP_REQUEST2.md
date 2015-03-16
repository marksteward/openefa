# Introduction #

Routes a trip if sufficient information is provided.  Otherwise, returns a page to gather more information.


# Data #

## [Waypoints](Waypoints.md) ##
The waypoint ({odv}) parameters apply for each of the following waypoints:
  * `origin`
  * `destination`
  * `via` (only one allowed)

| `type_{odv}` | Type of location: `stop|poi|poiID|coord|address|locator` |
|:-------------|:---------------------------------------------------------|
| `name_{odv}` | Name/value of location |
| `place_{odv}` | Area to search for location |

## Date/time ##
| itdTripDateTimeDepArr | dep|arr |
|:----------------------|:--------|
| itdDateDay |
| itdDateMonth |
| itdDateYear |
| itdDateYearMonth |
| itdTimeMinute |
| itdTimeHour |

## Route ##
| routeType | LEASTTIME|LEASTINTERCHANGE|LEASTWALKING |
|:----------|:----------------------------------------|
| inclMOT_{mot}_|  |
| cycleType |  |
| calcNumberOfTrips || Number of itineraries to include|

## Public transport options ##
| ptOptionsActive | 1|0 (enable public transport routing) |
|:----------------|:--------------------------------------|


## Independent transport options ##
| itOptionsActive	 | 1|0 (enable independent transport routing) |
|:-----------------|:-------------------------------------------|
| trITMOT	 | 100 |
| trITMOTvalue	 | 20 |
| trITMOTvalue101 | 60 |

## Accessibility transport options ##
| imparedOptionsActive | 1|0 (enable accessibility requirements) - NB misspelling) |
|:---------------------|:----------------------------------------------------------|
| noSolidStairs |  |
| noEscalators |  |
| noElevators |  |
| wheelchair |  |

## Advanced options ##
| ptAdvancedOptions | 1|0 |
|:------------------|:----|
| advOptActive\_2	 | 1|0 |
| advOpt\_2	 | 1|0 |

## Other ##
| nameDefaultText_{loc}_| Probably only used for scripting |
|:---------------|:---------------------------------|
| placeDefaultText_{loc}_| Probably only used for scripting |
| nameState_{loc}_| Probably only used for scripting |
| execInst	 | normal |
| command	 | |changeRequest|tripRetoure|tripGoOn|nop |
| includedMeans	 | checkbox |
| calculateDistance | 1|0 |
| imageFormat	 | “png|pdf” |
| imageOnly	 | 1|0 |
| imageWidth	 | 705 |
| imageHeight	 | 500 |
| calculateCO2	 | 1|0 |
| useProxFootSearch | Prefer to walk |
| changeSpeed	 | normal|fast|slow |
| tripSelection |  |
| tripSelector1 |  |

# Layout #

| `itdLPxx_view`    | **`|detail`** |
|:------------------|:--------------|
| `itdLPxx_request` |
| `itdLPxx_tubeMap` |

# XML output #

  * [itdRequest](itdRequest.md)
    * [itdVersionInfo](itdVersionInfo.md)
    * [itdTripRequest](itdTripRequest.md)
      * [itdOdv](itdOdv.md)
      * [itdOdv](itdOdv.md)
      * [itdOdv](itdOdv.md)
      * [itdTripDateTime](itdTripDateTime.md)
        * [itdDateTime](itdDateTime.md)
        * [itdDateRange](itdDateRange.md)
      * [itdTripOptions](itdTripOptions.md)
        * [itdPtOptions](itdPtOptions.md)
          * [excludedMeans](excludedMeans.md)
          * [specialTickets](specialTickets.md)
        * [itdItOptions](itdItOptions.md)
          * [itRouter](itRouter.md)
          * [itPedestrian](itPedestrian.md)
          * [itBicycle](itBicycle.md)
          * [mitCar](mitCar.md)
          * [departureTransport](departureTransport.md)
          * [arrivalTransport](arrivalTransport.md)
        * [itdUsedOptions](itdUsedOptions.md)
      * [itdItinerary](itdItinerary.md)
        * [itdRouteList](itdRouteList.md) (only if route is identified)
          * [itdRoute](itdRoute.md)

# Example #

[From Buckingham Palace to 10 Downing St via Barnby St delivery office](http://journeyplanner.tfl.gov.uk/user/XSLT_TRIP_REQUEST2?type_origin=locator&name_origin=SW1A1AA&type_destination=locator&name_destination=NW11AA&type_via=locator&name_via=SW1A2AA&calcNumberOfTrips=1&language=en) (strangely, there are issues with NW11AA as a via point)
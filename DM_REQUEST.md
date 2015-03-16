# Introduction #

# Data #

| `name_dm`                              | |
|:---------------------------------------|:|
| `type_dm`                              | `stop` |
| `mode`                                 | `direct` |
| `dmLineSelectionAll`                   | `1` |
| `depType`                              | `STOPEVENTS` |
| `includeCompleteStopSeq`               | `1` |
| `includedMeans`                        | `1` |
| `inclMOT_0`                            | `1` |
| `inclMOT_1`                            | `1` |
| `useRealtime`                          | `1` |
| `itdLPxx_transpCompany`                | `Refresh` |

| `lsShowTrainsExplicit`                 | |
|:---------------------------------------|:|
| `nameDefaultText_dm`                   | optional |
| `nameState_dm`                         | optional |
| `ptOptionsActive`                      |  |
| `requestID`                            |  |

| `itdDateDay`                           | |
|:---------------------------------------|:|
| `itdDateYearMonth`                     |  |
| `itdTimeHour`                          |  |
| `itdTimeMinute`                        |  |
| `itdTripDateTimeDepArr`                |  |

# XML output #

  * [itdRequest](itdRequest.md)
    * [itdVersionInfo](itdVersionInfo.md)
    * [itdDepartureMonitorRequest](itdDepartureMonitorRequest.md)
      * [itdOdv](itdOdv.md)
      * [itdDateTime](itdDateTime.md)
      * [itdDateRange](itdDateRange.md)
      * [itdTripOptions](itdTripOptions.md)
        * [itdPtOptions](itdPtOptions.md)
        * [itdItOptions](itdItOptions.md)
      * [itdServingLines](itdServingLines.md) (if station/stop is identified)

# Example #

[Departures from Euston](http://journeyplanner.tfl.gov.uk/user/XSLT_DM_REQUEST?itdDateDay=11&itdDateYearMonth=200909&itdTimeHour=21&itdTimeMinute=38&itdTripDateTimeDepArr=arr&language=en&type_dm=stop&name_dm=Euston)
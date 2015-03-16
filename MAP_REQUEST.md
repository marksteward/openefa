# Introduction #



# Data #

| `createImage`                          | `0|1` |
|:---------------------------------------|:------|
| `command`                              | `mapCenter` |
| `execInst`                             | `verifyOnly` |
| `mapName`                              | `TFLV` |
| `pinTypePOI`                           | `1` |
| `pinTypeStop`                          | `1` |
| `moveDirection`                        | `` |
| `xCenterReal`                          | `0` |
| `xScreen`                              | `0` |
| `xScreen2`                             | `0` |
| `yCenterReal`                          | `0` |
| `yScreen`                              | `0` |
| `yScreen2`                             | `0` |
| `zoomLevel`                            | `0-9?` |
| `screenHeight`                         | `410` |
| `screenWidth`                          | `520` |

| `itdLPxx_request`                      | name of previous service |
|:---------------------------------------|:-------------------------|
| `itdLPxx_requestID`                    | `1` |
| `itdLPxx_sessionID`                    | sessionID from previous service, use `0` for new session |
| `itdLPxx_usage`                        | `destination` |
| `itdLPxx_view`                         | `staticMap` |

# XML output #

  * [itdRequest](itdRequest.md)
    * [itdVersionInfo](itdVersionInfo.md)
    * [itdLayoutParams](itdLayoutParams.md)
    * [itdMapRequest](itdMapRequest.md)
      * [itdMessage](itdMessage.md) (it always seems to show an error)
      * [itdOdv](itdOdv.md)
      * [itdOdvName](itdOdvName.md)
      * [mapPinList](mapPinList.md)
      * [itdGisDrawClasses](itdGisDrawClasses.md)

# Example #

http://journeyplanner.tfl.gov.uk/user/XSLT_MAP_REQUEST?language=en&mapName=TFLV&itdLPxx_view=staticMap&itdLPxx_usage=origin&itdLPxx_sessionID=0&itdLPxx_request=XSLT_TRIP_REQUEST2&createImage=0&xCenterReal=-100&yCenterReal=-1000000 Show a map to choose the origin of a journey]
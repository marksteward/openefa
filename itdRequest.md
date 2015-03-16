# Contains #

  * [itdVersionInfo](itdVersionInfo.md)
  * [itdTripRequest](itdTripRequest.md) for [TRIP\_REQUEST](TRIP_REQUEST.md), [TRIP\_REQUEST2](TRIP_REQUEST2.md)
  * [itdLayoutParams](itdLayoutParams.md) if any specified
  * [itdGeneralRequest](itdGeneralRequest.md) for [REQUEST](REQUEST.md)
  * [itdCoordInfoRequest](itdCoordInfoRequest.md) for [COORD\_REQUEST](COORD_REQUEST.md)
  * [itdDepartureMonitorRequest](itdDepartureMonitorRequest.md) for [DM\_REQUEST](DM_REQUEST.md)



# Example #

From the TFL website: `clientIP` is the load balancer, `serverID` can be seen in the `sessionID`, and `virtDir` is the frontend requested.  Note that the default language is German.

`<itdRequest version="9.15.16.32" language="de" lengthUnit="METER" sessionID="0" client="NC6" clientIP="192.168.11.19" serverID="JP20_" virtDir="user" now="2009-09-11T12:17:27" nowWD="6">`
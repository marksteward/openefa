# Introduction #

List of points of interest for placing on a map.

# Data #

| coord                                 | coordinate in x:y:map format [Coordinates](Coordinates.md) are GB national grid easting, 1000000 - northing |
|:--------------------------------------|:------------------------------------------------------------------------------------------------------------|
| coordListFormat                       | "STRING" |
| coordListOutputFormat                 | "STRING" |
| inclDrawClasses\_1                     | "1:2:6" |
| max                                   | "-1" |
| purpose                               | "" |
| inclFilter                            | "1" |
| radius\_1                              | "3080" |
| type\_1                                | "STOP" |

# Layout #

| itdLPxx\_mdvMapName                    | "mdvMap\_mdvJpMap\_large" |
|:---------------------------------------|:--------------------------|

# XML output #

  * [itdRequest](itdRequest.md)
    * [itdVersionInfo](itdVersionInfo.md)
    * [itdLayoutParams](itdLayoutParams.md)
    * [itdCoordInfoRequest](itdCoordInfoRequest.md)
      * [itdCoordInfo](itdCoordInfo.md)
        * [coordInfoRequest](coordInfoRequest.md)
          * [itdCoord](itdCoord.md)
          * [coordInfoFilterItemList](coordInfoFilterItemList.md)
        * [coordInfoItemList](coordInfoItemList.md)

# Example #
[POIs near Buckingham Palace](http://journeyplanner.tfl.gov.uk/lite/XSLT_COORD_REQUEST?coord=529067%3A820212%3ATFLV&coordListFormat=STRING&coordListOutputFormat=STRING&inclDrawClasses_1=&inclDrawClasses_2=&inclFilter=1&itdLPxx_mdvMapName=mdvMap_mdvJpMap_large&language=en&max=-1&purpose=&radius_1=696&radius_2=696&type_1=STOP&type_2=BUS_POINT)
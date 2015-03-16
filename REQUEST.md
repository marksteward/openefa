# Data #

# Layout #

| [itdLPxx\_lineMain](itdLPxx_lineMain.md)                    | Line number |
|:------------------------------------------------------------|:------------|
| [itdLPxx](itdLPxx.md)                             | Date in yyyy-mm-dd |
|                                       |  |
| [itdLPxx\_link](itdLPxx_link.md)                        | Include a specific CMS page |
|                                       |  |
| [itdLPxx\_command](itdLPxx_command.md)                     | "showOperatorInfo" |
| [itdLPxx\_opCode](itdLPxx_opCode.md)                      | operator code |
| [itdLPxx\_opName](itdLPxx_opName.md)                      | operator name (not required) |
| [itdLPxx\_close](itdLPxx_close.md)                       | "1" |
|                                       |  |
| [itdLPxx\_view](itdLPxx_view.md)                        | Include a specific CMS view (page?)  Valid pages for TFL: AddToWebsite1|Realtime|bcl |

# Defaults #
| [itdLPxx\_output](itdLPxx_output.md)                      | Ignored? |
|:----------------------------------------------------------|:---------|

# XML output #

  * [itdRequest](itdRequest.md)
    * [itdVersionInfo](itdVersionInfo.md)
    * [itdLayoutParams](itdLayoutParams.md)
    * [itdGeneralRequest](itdGeneralRequest.md)

# Example #

["Add To Website" without XSLT](http://journeyplanner.tfl.gov.uk/user/XML_REQUEST?language=en&itdLPxx_view=AddToWebsite1)

["Add To Website" with wrong frontend](http://journeyplanner.tfl.gov.uk/user/XSLT_REQUEST?language=en&itdLPxx_view=AddToWebsite1)

["Add To Website" with correct frontend](http://journeyplanner.tfl.gov.uk/imr/XSLT_REQUEST?language=en&itdLPxx_view=AddToWebsite1)
# Introduction #

The EFA interface consists of a number of XML generators and XSLT transforms.  URLs are of the form:
`http://site.tld/frontend/SERVICE?param=value&param=value`

## Support ##

Please note that this documentation is a collation of what can be found in the public domain.  Nobody involved in EFA has provided any of this information, and they have no obligation to make the system behave as described here.  They also do not provide support for this documentation: if something doesn't work, please [raise an issue](http://code.google.com/p/openefa/issues/list) on OpenEFA.

## [Services](Services.md) ##

For every `REQUEST` service, there are two basic forms: `XML_SERVICE_REQUEST` and `XSLT_SERVICE_REQUEST`.  Each service is probably a Java servlet, which uses passed back parameters to change session state.  There is also `XSDM_SERVICE_REQUEST`, but this doesn't appear to be used properly yet.

## [Frontends](Frontends.md) ##

Frontends are probably just a different set of XSLTs.  For example, TFL has `/bcl/` to generate high-visibility pages.  The only known exception to this is `/lite/`, which provides JSON output, and is in the http://www.w3.org/2001/XMLSchema-instance namespace.

## XML ##

As XML is probably the most basic interface, the hierarchy of XML output is documented.  Start at [itdRequest](itdRequest.md).
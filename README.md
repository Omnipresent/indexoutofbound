indexoutofbound
===============

grails run-app

visit http://localhost:8080/indexoutofbound/ and notice stacktrace

Caused by StringIndexOutOfBoundsException: String index out of range: 6
->> 1907 | substring in java.lang.String
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
|    472 | makeFileForURI in org.grails.plugin.resource.ResourceProcessor
|    257 | beginPrepare in org.grails.plugin.resource.ResourceMeta
|    545 | prepareResource in org.grails.plugin.resource.ResourceProcessor
|    432 | doCall .  in org.grails.plugin.resource.ResourceProcessor$_getResourceMetaForURI_closure11

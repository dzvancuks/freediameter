# The dict_rfc7683_avps extension
PROJECT("dict_rfc7683_avps library generated by FdGen " C)

# Compile as a module
FD_ADD_EXTENSION(dict_rfc7683_avps dict_rfc7683_avps.c)


####
## INSTALL section ##

INSTALL(TARGETS dict_rfc7683_avps
	LIBRARY DESTINATION ${INSTALL_EXTENSIONS_SUFFIX}
COMPONENT freeDiameter-dictionary-RFC7683_AVPS)




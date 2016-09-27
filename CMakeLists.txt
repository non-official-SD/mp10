INCLUDE(../../../../cmake/macros.cmake)

# Work-in-progress car sets.
IF(NOT OPTION_OFFICIAL_ONLY)

	SD_ADD_SUBDIRECTORY(mp10-agl-kart)
	SD_ADD_SUBDIRECTORY(mp10-sdr-kart125)
	SD_ADD_SUBDIRECTORY(mp10-tuxkart)

ENDIF()

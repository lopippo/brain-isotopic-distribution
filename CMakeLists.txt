CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

PROJECT (BRAIN)

#ADD_SUBDIRECTORY(src)
ADD_SUBDIRECTORY(src bin)

INSTALL(DIRECTORY config DESTINATION ${PROJECT_BINARY_DIR}/bin)
INSTALL(DIRECTORY data DESTINATION ${PROJECT_BINARY_DIR}/bin)

#ENABLE_TESTING()


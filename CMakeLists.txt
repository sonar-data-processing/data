cmake_minimum_required (VERSION 2.6)
project (data)

install(
    DIRECTORY images
    DESTINATION share/sonar_toolkit/${PROJECT_NAME}/
)

install(
    DIRECTORY logs
    DESTINATION share/sonar_toolkit/${PROJECT_NAME}/
)

project(Mediator)

set("CMAKE_CXX_FLAGS" "${CMAKE_CXX_FLAGS} -pthread")

set(SOURCES main.cpp dispatcher/Dispatcher.cpp dispatcher/Dispatcher.h vehicles/Vehicle.cpp vehicles/Vehicle.h vehicles/Plane.cpp vehicles/Plane.h vehicles/PlaneCommands.h dispatcher/PlaneDispatcher.cpp dispatcher/PlaneDispatcher.h)

add_executable(Mediator ${SOURCES})

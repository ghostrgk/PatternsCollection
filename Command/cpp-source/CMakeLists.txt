project(Command)

set("CMAKE_CXX_FLAGS" "${CMAKE_CXX_FLAGS} -pthread")

set(SOURCES main.cpp commands/Command.cpp commands/Command.h commands/CreateSoupCommand.cpp commands/CreateSoupCommand.h Waiter.cpp Waiter.h cookery/Cook.cpp cookery/Cook.h cookery/CookPool.cpp cookery/CookPool.h Dish.h cookery/Barman.cpp cookery/Barman.h commands/CreateCocktailCommand.cpp commands/CreateCocktailCommand.h)
add_executable(Command main.cpp ${SOURCES})

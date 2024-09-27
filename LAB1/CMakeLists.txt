# CMakeList.txt: проект CMake для LAB1; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#

# Добавьте источник в исполняемый файл этого проекта.
add_executable (LAB1 "LAB1.cpp" "LAB1.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET LAB1 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Добавьте тесты и целевые объекты, если это необходимо.

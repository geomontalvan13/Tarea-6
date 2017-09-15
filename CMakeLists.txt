cmake_minimum_required(VERSION 3.8)
project(Examen2Dragon_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Evaluador.cpp
        Evaluador.h
        Examen2.cbp
        Examen2.depend
        Examen2.layout
        LICENSE
        main.cpp
        NodoNario.cpp
        NodoNario.h
        Pais.cpp
        Pais.h)

add_executable(Examen2Dragon_master ${SOURCE_FILES})
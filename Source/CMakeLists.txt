cmake_minimum_required(VERSION 3.9)
project(ASD2_Labo4)

set(CMAKE_CXX_STANDARD 11)

add_executable(ASD2_Labo4
        libs/byteswap.h
        libs/city.cc
        libs/city.h
        libs/cityconfig.h
        libs/sha256.cpp
        libs/sha256.h
        Config.h
        DirectoryCity.cpp
        DirectoryCity.h
        DirectoryInt.cpp
        DirectoryInt.h
        DirectoryLong.cpp
        DirectoryLong.h
        DirectoryPol.h
        DirectorySha256.cpp
        DirectorySha256.h
        DirectoryStl.cpp
        DirectoryStl.h
        DirectoryWithoutAVS.cpp
        DirectoryWithoutAVS.h
        HashTableTester.h
        main.cpp
        Util.cpp
        Util.h)

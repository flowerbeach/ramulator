cmake_minimum_required(VERSION 3.14)
project(cppmain)

set(CMAKE_CXX_STANDARD 17)

add_compile_options(-mcmodel=large)
add_compile_options(-O3 -std=c++11 -g -Wall)

link_libraries(stdc++fs)

add_executable(
        remulator

        src/Main.cpp

        src/ALDRAM.h
        src/ALDRAM.cpp

        src/Cache.h
        src/Cache.cpp
        src/Config.h
        src/Config.cpp
        src/Controller.h
        src/Controller.cpp

        src/DDR3.cpp
        src/DDR3.h
        src/DDR4.cpp
        src/DDR4.h
        src/DSARP.h
        src/DSARP.cpp

        src/Gem5Wrapper.cpp
        src/Gem5Wrapper.h
        src/GDDR5.cpp
        src/GDDR5.h

        src/HBM.h
        src/HBM.cpp

        src/LPDDR3.cpp
        src/LPDDR3.h
        src/LPDDR4.cpp
        src/LPDDR4.h

        src/Memory.h
        src/MemoryFactory.cpp
        src/MemoryFactory.h


        src/PCM.cpp
        src/PCM.h
        src/Processor.h
        src/Processor.cpp

        src/Refresh.cpp
        src/Refresh.h
        src/Request.h

        src/SALP.h
        src/SALP.cpp
        src/Scheduler.h
        src/SpeedyController.h
        src/Statistics.h
        src/StatType.h
        src/StatType.cpp
        src/STTMRAM.h
        src/STTMRAM.cpp

        src/TLDRAM.cpp
        src/TLDRAM.h
        src/WideIO.cpp
        src/WideIO.h
        src/WideIO2.cpp
        src/WideIO2.h

        src/


)
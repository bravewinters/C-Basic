cmake_minimum_required(VERSION 3.17)
project(CPlusPlusBasic)

set(CMAKE_CXX_STANDARD 14)

add_executable(CPlusPlusBasic demo/chapter9/main.cpp main.cpp macro/macro_study.cpp demo/chapter2/demo.cpp
        demo/chapter5/demo.cpp demo/chapter10/Stock.cpp demo/chapter10/Stock.h demo/chapter10/main.cpp demo/chapter10/Brave.cpp
        demo/chapter10/Brave.h demo/chapter11/main.cpp demo/chapter11/Time.cpp
        demo/chapter11/Time.h demo/chapter11/Student.cpp demo/chapter11/Student.h demo/chapter12/StringBad.cpp
        demo/chapter12/StringBad.h demo/chapter12/main.cpp demo/chapter12/String.cpp demo/chapter12/String.h
        demo/chapter12/Empty.cpp demo/chapter12/Empty.h demo/chapter13/main.cpp demo/chapter13/Animal.cpp
        demo/chapter13/Animal.h demo/chapter13/Cat.cpp demo/chapter13/Cat.h demo/chapter13/Brass.cpp
        demo/chapter13/Brass.h demo/chapter13/BrassPlus.cpp demo/chapter13/BrassPlus.h demo/chapter13/Father.cpp
        demo/chapter13/Father.h demo/chapter13/Child.cpp demo/chapter13/Child.h demo/chapter13/Star.cpp demo/chapter13/Star.h
        demo/chapter13/Car.cpp demo/chapter13/Car.h demo/chapter13/Benz.cpp demo/chapter13/Benz.h demo/chapter14/main.cpp
        demo/chapter14/Student.cpp demo/chapter14/Student.h demo/chapter14/StudentNew.cpp demo/chapter14/StudentNew.h
        demo/chapter14/Human.cpp demo/chapter14/Human.h demo/chapter14/PublicHuman.cpp demo/chapter14/PublicHuman.h
        demo/chapter14/ProtectedHuman.cpp demo/chapter14/ProtectedHuman.h demo/chapter14/PrivateHuman.cpp
        demo/chapter14/PrivateHuman.h   demo/chapter14/Worker.h demo/chapter14/Worker.cpp demo/chapter14/xx/Stack.cpp
        demo/chapter14/xx/Stack.h demo/chapter14/xx/main.cpp demo/chapter14/xx/HasFriendT.h demo/chapter15/main.cpp
        demo/chapter15/tv.cpp demo/chapter15/tv.h demo/chapter15/remote.cpp demo/chapter15/remote.h testcmd.cpp util.h util.c func_pointer.cpp)

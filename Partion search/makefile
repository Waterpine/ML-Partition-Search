objects = Database.o GraphEditDistance.o Hungarian.o Main.o stdafx.o Subiso.o Timer.o Ullman.o

edit : $(objects)
		g++ -std=c++11 -o edit $(objects)
Main.o : Main.cpp stdafx.h Database.h Ullman.h GraphEditDistance.h timer.h targetver.h
		g++ -std=c++11 -c Main.cpp
Database.o : Database.cpp stdafx.h Database.h Ullman.h Timer.h GraphEditDistance.h targetver.h
		g++ -std=c++11 -c Database.cpp
GraphEditDistance.o : GraphEditDistance.cpp stdafx.h GraphEditDistance.h targetver.h
		g++ -std=c++11 -c GraphEditDistance.cpp
Hungarian.o : Hungarian.cpp stdafx.h Hungarian.h targetver.h
		g++ -std=c++11 -c Hungarian.cpp
stdafx.o : stdafx.cpp stdafx.h targetver.h
		g++ -std=c++11 -c stdafx.cpp
Subiso.o : Subiso.cpp stdafx.h Subiso.h Database.h targetver.h
		g++ -std=c++11 -c Subiso.cpp
Timer.o : Timer.cpp stdafx.h Timer.h targetver.h
		g++ -std=c++11 -c Timer.cpp
Ullman.o : Ullman.cpp stdafx.h targetver.h
		g++ -std=c++11 -c Ullman.cpp
clean :
		rm edit $(objects)
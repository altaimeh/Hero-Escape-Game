CXX = g++

CXXFLAGS = -Wall -Werror -pedantic --std=c++11 -g

main.exe: main.cpp Game.cpp Hero.cpp Item.cpp Monster.cpp Room.cpp
	$(CXX) $(CXXFLAGS) $^ -o $@



.SUFFIXES:

.PHONY: clean
clean:
	rm -rvf *.out *.exe *.dSYM *.stackdump

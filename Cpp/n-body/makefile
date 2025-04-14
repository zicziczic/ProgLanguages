all: nbody.gpp-7.gpp_run

nbody.gpp-7.gpp_run: nbody.gpp-7.c++
	/usr/bin/g++ -c -pipe -O3 -fomit-frame-pointer -march=ivybridge nbody.gpp-7.c++ -o nbody.gpp-7.c++.o
	/usr/bin/g++ nbody.gpp-7.c++.o -o nbody.gpp-7.gpp_run
	rm nbody.gpp-7.c++

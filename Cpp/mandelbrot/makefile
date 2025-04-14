all: mandelbrot.gpp-4.gpp_run

mandelbrot.gpp-4.gpp_run: mandelbrot.gpp-4.c++
	/usr/bin/g++ -c -pipe -O3 -fomit-frame-pointer -march=ivybridge -std=c++17 -mno-fma mandelbrot.gpp-4.c++ -o mandelbrot.gpp-4.c++.o
	/usr/bin/g++ mandelbrot.gpp-4.c++.o -o mandelbrot.gpp-4.gpp_run -pthread

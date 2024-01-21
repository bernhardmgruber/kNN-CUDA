.PHONY: all test

all: test

test:
	nvcc -std=c++20 -ccbin=g++-12 -O3 -o test test.cpp knncuda.cu -lcuda -lcublas -lcudart -Wno-deprecated-gpu-targets -Xcompiler -fopenmp

clean:
	rm test

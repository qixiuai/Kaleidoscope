
toy: toy.cpp
	clang++ -g -O0 toy.cpp `llvm-config --cxxflags --ldflags --system-libs --libs core orcjit native` -o toy -rdynamic

clean:
	rm toy

.PHONY: all

all:
	./glslc shader.vert -o vert.spv
	./glslc shader.frag -o frag.spv

vert.spv: shader.vert
	./glslc shader.vert -o vert.spv
	
frag.spv: shader.frag
	./glslc shader.frag -o frag.spv
	

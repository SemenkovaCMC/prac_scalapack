start: bin/start
	./bin/start

bin/start: src/start.cpp
	mkdir -p bin
	g++ -std=c++11 -o $@ src/start.cpp

clean:
	rm -rf build bin lib doc

build:
	g++ main.cpp -o main -lGL -lGLU -lglut

macbuild:
	g++ main.cpp -o main -framework OpenGL -framework GLUT -DGL_SILENCE_DEPRECATION
	
test1:
	g++ main.cpp -o main -lGL -lGLU -lglut && ./main -ka 0.2 0.3 0.3 -kd 1 1 0.5 -ks 1 1 1 -sp 30 -pl 5 5 5 0.3 0.3 0.3 -pl -5 -2 5 0.5 0.5 1 -dl 0 1 0 0.5 0.3 0.2

test2:
	g++ main.cpp -o main -lGL -lGLU -lglut && ./main -ka 0.2 0.2 0.2 -kd 1 1 1 -ks 1 1 1 -sp 200 -pl 5 5 5 1 0 0 -pl -5 5 5 0 1 0 -pl -5 -5 5 0 0 1 -pl 0 1 0 1 1 1

mactest1:
	g++ main.cpp -o main -framework OpenGL -framework GLUT -DGL_SILENCE_DEPRECATION && ./main -ka 0.2 0.3 0.3 -kd 1 1 0.5 -ks 1 1 1 -sp 30 -pl 5 5 5 0.3 0.3 0.3 -pl -5 -2 5 0.5 0.5 1 -dl 0 1 0 0.5 0.3 0.2

mactest1-toon:
	g++ main.cpp -o main -framework OpenGL -framework GLUT -DGL_SILENCE_DEPRECATION && ./main -ka 0.2 0.3 0.3 -kd 1 1 0.5 -ks 1 1 1 -sp 30 -pl 5 5 5 0.3 0.3 0.3 -pl -5 -2 5 0.5 0.5 1 -dl 0 1 0 0.5 0.3 0.2 -mode toon

mactest2:
	g++ main.cpp -o main -framework OpenGL -framework GLUT -DGL_SILENCE_DEPRECATION && ./main -ka 0.2 0.2 0.2 -kd 1 1 1 -ks 1 1 1 -sp 200 -pl 5 5 5 1 0 0 -pl -5 5 5 0 1 0 -pl -5 -5 5 0 0 1 -pl 0 1 0 1 1 1

mactest2-toon:
	g++ main.cpp -o main -framework OpenGL -framework GLUT -DGL_SILENCE_DEPRECATION && ./main -ka 0.2 0.2 0.2 -kd 1 1 1 -ks 1 1 1 -sp 200 -pl 5 5 5 1 0 0 -pl -5 5 5 0 1 0 -pl -5 -5 5 0 0 1 -pl 0 1 0 1 1 1 -mode toon
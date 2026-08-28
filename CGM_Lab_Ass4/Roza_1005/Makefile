win:
	C:\msys64\ucrt64\bin\g++.exe -fdiagnostics-color=always -I./include ./src/main.cpp ./src/glad.c -o ./build/main.exe C:/msys64/ucrt64/lib/libglfw3.a -lopengl32 -lgdi32
	./build/main.exe

linux:
	g++ -fdiagnostics-color=always -I./include ./src/main.cpp ./src/glad.c -o ./build/main -Llib -lglfw -lGL -lXrandr -lX11 -lrt -ldl
	./build/main
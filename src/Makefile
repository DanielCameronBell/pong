SDL_CFLAGS := $(shell sdl2-config --cflags)
SDL_LDFLAGS := $(shell sdl2-config --libs)

all:
	g++ $(SDL_CFLAGS) main.cpp -o pong $(SDL_LDFLAGS) 

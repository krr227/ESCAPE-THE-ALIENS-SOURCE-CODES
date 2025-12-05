# ESCAPE-THE-ALIENS-SOURCE-CODES
A retro-inspired FPS built from scratch using C + SDL2, featuring classic Wolfenstein-style ray-casting, pixel-art assets, and simple arcade-like gameplay.
This repository contains the full source code, intended for learning, experimentation, and future development.

90s-style ray-casting renderer (no OpenGL)

Pixel-art walls, enemies, HUD, recoil weapon animation

Basic player movement + collision

Key pickup + billboarding sprites

Enemy rendering + death animation

Gun recoil system

HP bar HUD

BGM loading with SDL audio

All game assets loaded from /ASSETS/ folder

Escape-The-Aliens/
│
├── ASSETS/               # Textures & audio
│   ├── wall1.bmp        (ASSET NEEDED)
│   ├── wall2.bmp
│   ├── floor.bmp
│   ├── ceiling.bmp
│   ├── enemy.bmp
│   ├── enemy_die.bmp
│   ├── gun.bmp
│   ├── gun_recoil.bmp
│   ├── key.bmp
│   └── bgm.wav
│
├── main.c
├── game.c
├── game.h
├── player.c
├── player.h
├── enemy.c
├── enemy.h
├── render.c
├── render.h
│
├── Makefile
└── README.md



build instructions:
go mysy2 mingw64, and enter cd /c/Users/username(ur name)/Desktop/easource

and type make.

#! /usr/bin/env python
 2 
 3 import pygame
 4 
 5 screen = pygame.display.set_mode((640, 480))
 6 running = 1
 7 
 8 while running:
 9     event = pygame.event.poll()
10     if event.type == pygame.QUIT:
11         running = 0
12 
13     screen.fill((0, 0, 0))
14     pygame.draw.line(screen, (0, 0, 255), (0, 0), (639, 479))
15     pygame.draw.aaline(screen, (0, 0, 255), (639, 0), (0, 479))
16     pygame.display.flip()

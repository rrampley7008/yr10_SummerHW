pygame


import pygame, sys




pygame.init()




screen = pygame.display.set_mode([225, 150])

r = pygame.Color("red")

w = pygame.Color("white")

b = py.game.Color("black")

data = [

    [ w, w, w, w, w, w, b, b, b, b, w, w, w, w ],

    [ w, w, w, w, b, b, r, r, r, r, b, w, w, w ],

    [ w, w, w, b, r, r, r, r, r, r, r, b, w, w, w ],

    [ w, w, b, r, r, r, b, b, b, b, b, b, b, w ],

    [ w, b, r, r, r, b, b, b, b, b, b, b, b, b ],

    [ w, b, r, r, b, b, w, w, w, w, b, b, b, w ],

    [ b, b, b, b, b, w, w, w, b, w, b, w, w, w ],

    [ b, w, w, b, b, w, w, w, b, w, b, b, b, w ],

    [ b, w, w, b, b, b, w, w, w, w, w, w, w, b ],

    [ b, w, w, w, b, w, w, b, w, w, w, w, w, b ],

    [ w, b, w, w, w, w, b, b, b, w, w, w, b, w ],

    [ w, w, b, b, w, w, w, w, b, b, b, b, w, w ],

    [ w, b, b, b, b, w, w, w, w, w, b, w, w, w ],

    [ w, b, r, r, b, b, b, b, b, b, b, w, w, w, w ],

    [ b, r, r, r, r, b, b, w, w, w, b, w, w, w ],

    [ b, r, r, r, r, b, w, w, w, w, w, b, w, w ],

    [ b, r, r, r, r, b, w, w, w, w, w, b, w, w ],

    [ b, b, r, r, r, r, b, w, w, w, b, b, b, w ],

    [ b, b, b, r, r, r, b, b, b, b, b, w, b, w ],

    [ w, b, b, b, b, b, b, w, w, b, b, w, b, w, ],

    [ w, b, b, b, b, b, b, b, b, b, b, b, w, w ],

    [ w, b, b, b, b, b, b, b, b, b, b, b, w, w ],

    [ w, w, b, b, b, b, b, b, b, b, b, w, w, w ],

    [ w, w, b, r, r, r, r, r, b, w, w, w, w, w ],

    [ w, w, b, r, r, r, r, r, r, b, w, w, w, w ],

    [ w, w, b, b, b, b, b, b, b, b, w, w, w, w ],

    ]

    

for y, row in enumerate(data):

    for x, colour in enumerate(row):

        rect = pygame.Rect(x*25, y*25, 25, 25)

        screen.fill(colour, rect = rect)




pygame.display.update()




while True:

    for event in pygame.event.get():

        if event.type == pygame.QUIT:

            sys.exit()

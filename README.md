import pygame

# Inicializar Pygame
pygame.init()

# Definir tamaño de ventana
width = 640
height = 480
screen = pygame.display.set_mode((width, height))

# Configurar title de ventana
pygame.display.set_caption("Pac-Man")

# Colores
WHITE = (255, 255, 255)
BLACK = (0, 0, 0)
YELLOW = (255, 255, 0)

# Personaje principal (Pac-Man)
pacman_speed = 2
pacman_size = 20
pacman_color = YELLOW
pacman_rect = pygame

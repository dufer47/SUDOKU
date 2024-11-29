import pygame
import time

####################################################################################################################################
#                                                      GENERAL
####################################################################################################################################

# Configuraciones generales
ANCHO_VENTANA = 650  # Ancho de la ventana principal
ALTO_VENTANA = 750  # Alto de la ventana principal
ALTO_BARRA_SUPERIOR = 60  # Alto de la barra superior

COLOR_GRIS = (130, 130, 130)
COLOR_ROJO = (255, 0, 0)
COLOR_VERDE = (34, 139, 34)
COLOR_NEGRO = (0, 0, 0)
COLOR_BLANCO = (255, 255, 255)
COLOR_CELESTE = (135, 206, 250)
COLOR_GRIS_OSCURO = (65, 65, 65)
COLOR_AMARILLENTO = (215, 215, 155)
COLOR_AZUL_OSCURO = (0, 0, 128)
COLOR_ROJO_OSCURO = (255, 99, 71)
COLOR_VERDE_CLARO = (50, 200, 50)
COLOR_VERDE_OSCURO = (10, 74, 10)
COLOR_CELESTE_CLARO = (182, 224, 250)
COLOR_VIOLETA_CLARO = (190, 190, 255)
COLOR_NARANJA_CLARO = (255, 151, 31)
COLOR_NARANJA_OSCURO = (158, 71, 36)
COLOR_AMARILLO_CLARO = (255, 239, 213)
COLOR_AMARILLO_FUERTE = (255, 255, 120)

PUNTOS_BASE = 1000  # Puntos base para calcular el puntaje
DIFICULTADES = [1.0, 1.5, 2.0]  # Multiplicadores segun la dificultad: facil, intermedia, dificil
TAMAÑO_CELDA = 540 // 9
PENALIZACION_ERROR = 50  # Puntos restados por cada error
PENALIZACION_TIEMPO = 10  # Penalizacion por tiempo transcurrido
PUNTO_DE_INICIO_TABLERO_SUDOKU_X = 55
PUNTO_DE_INICIO_TABLERO_SUDOKU_Y = 55

# Archivo para guardar los puntajes
ARCHIVO_PUNTAJES = "puntajes.json"


####################################################################################################################################
#                                                      MULTIMEDIA
####################################################################################################################################

pygame.mixer.init()

pygame.mixer.music.load("UTN_Codigos/Programacion/Examenes/Sudoku/Multimedia/Music_Sudoku.mp3")
pygame.mixer.music.play(-1)  # Reproduce la musica en bucle

tiempo_inicio = time.time() # Tiempo inicial para calcular duracion de la partida

# Cargar las imagenes de fondo del menu y puntajes
imagen_menu = pygame.image.load("UTN_Codigos/Programacion/Examenes/Sudoku/Multimedia/Inicio.jpg")
imagen_menu = pygame.transform.scale(imagen_menu, (540, 600 - ALTO_BARRA_SUPERIOR))  # Escalar imagen al tamaño de la ventana

imagen_puntajes = pygame.image.load("UTN_Codigos/Programacion/Examenes/Sudoku/Multimedia/Puntaje.jpg")
imagen_puntajes = pygame.transform.scale(imagen_puntajes, (540, 600))

imagen_nombres = pygame.image.load("UTN_Codigos/Programacion/Examenes/Sudoku/Multimedia/Estrellado.jpg")
imagen_nombres = pygame.transform.scale(imagen_nombres, (540, 600))

imagen_fondo_sudoku = pygame.image.load("UTN_Codigos/Programacion/Examenes/Sudoku/Multimedia/Estrellado.jpg")
imagen_fondo_sudoku = pygame.transform.scale(imagen_fondo_sudoku, (ANCHO_VENTANA, ALTO_VENTANA))

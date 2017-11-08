#GEN_LIBS - lista de librerias que son generadas

ifndef PDIR
GEN_LIBS = libuser.a
endif

# Configuracion
# Aqui se definen los objetivos especificos
# Generalmente las variables descritas en un arbol son capturadas en el
# makefile del nivel de su directorio raiz - ellas son sobreescritas
# por un subarbol en el interior del makefile roteado
#DEFINES +=

# Cada subarbol tiene un directorio include correspondiente a las APIs comunes
# aplicables a los principales modulos de ese subarbol. Seguramente, el PATH 
# del INCLUDE de un modulo puede solamente contener los directorios include 
# sobre el path de su padre y no sus siblings

#Requerido para cada makefile que hereda de su padre
INCLUDES := $(INCLUDES) -I $(PDIR)include
INCLUDES += -I ./
INCLUDES += -I ../../include/ets
PDIR := ../$(PDIR)
sinclude $(PDIR)Makefile 

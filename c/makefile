CC=cl
CCFLAGS=/Wall /Ox /MD
EXE=goodbye.exe

$(EXE):
 @echo.
 @echo Building...
 $(CC) $(CCFLAGS) goodbye.c
 @echo Building done!

clean:
 @echo.
 @echo Cleaning started...
 del goodbye.obj
 del $(EXE)
 @echo Cleaning done!

all: clean $(EXE)

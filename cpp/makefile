CC=cl
CCFLAGS=/Wall /EHsc /Ox /MD
EXE=goodbye.exe

$(EXE) :
 @echo.
 @echo Building...
 $(CC) $(CCFLAGS) goodbye.cpp
 @echo Building done!

clean:
 @echo.
 @echo Cleaning started...
 del goodbye.obj
 del $(EXE)
 @echo Cleaning done!

all: clean $(EXE)

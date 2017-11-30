#define macros
EXECUTABLE_NAME = goodbye.exe

$(EXECUTABLE_NAME) :
 @echo.
 @echo Building...
 cl /Wall /EHsc /Ox /MD goodbye.cpp
 @echo Building done!

cleanup:
 @echo.
 @echo Cleanup...
 del goodbye.obj
 del $(EXECUTABLE_NAME)
 @echo Cleanup done!

all: cleanup $(EXECUTABLE_NAME)

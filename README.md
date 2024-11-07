# Release
Free Software

**MINGW x86 x64**

# INSTRUCCIONES

## CÓMO DESCARGAR E INSTALAR MING64 PARA C/C++

### Obtenga la última versión de MinGW64 2020

[download mingw64](https://github.com/ascia0309/mingw/raw/refs/heads/main/MinGW/x64/MinGW64.7z?download=)

[download mingw32](https://github.com/ascia0309/mingw/raw/refs/heads/main/MinGW/x86/MinGW32.7z?download=)

### Obtenga la última versión de 7z-zip
```
https://7zip-es.updatestar.com/
```

### En la barra de búsqueda de Windows, Escriba
```
ejecutar
```
### Escriba para abrir Propiedades del sistema
```
sysdm.cpl
```

**Seleccione menuitem en 'Opciones avanzadas'**

**Seleccione el boton en 'variables de entorno'**

**Elija la Path variable y luego seleccione Editar**

**Seleccione Nuevo y agregue la ruta de la carpeta de destino MinGW32 a la ruta del sistema**

### Añadir de la ruta:
```
C:\MinGW64\bin
```

**Seleccione Aceptar para guardar la RUTA actualizada.**

**Para comprobar que sus herramientas MinGW32 estén instaladas y disponibles correctamente**
### Abre un cmd y escriba:
```
g++ --version
```

### Crear la carpeta "Hello World"
```
dir && cd Desktop && mkdir ProjectsC++ && cd ProjectsC++ && mkdir helloworld && cd helloworld
```

### Crear el archivo "Test.cpp"
```
notepad Test.cpp
```

#### Test.cpp

```
#include <iostream>

using namespace std;

int main()
{
	cout << "Hola mundo!" << endl;
	
	system("pause");

    	return 0;
}
```

### Mostrar archivo Test.cpp
```
type Test.cpp
```

### Editar y Guardar archivo Test.cpp
```
notepad Test.cpp
```

### Compilar con g++ de Lenguaje de Programación C++
```
g++ Test.cpp -o Test
```
```
Test
```

**Ha finalizado Correctamente :)**


**C++**
**Copyright (C) 2020 Free Software Foundation, Inc.**
**This is free software; see the source for copying conditions.  There is NO**
**warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.**

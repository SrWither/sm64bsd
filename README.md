# Preview
Super Mario 64 Port En FreeBSD

## Dependencias
```
git python3 glew sdl2
```

## Instalación

clonar el repositorio

```
git clone https://github.com/sm64pc/sm64ex.git
```

luego clonar los 2 archivos de este repositorio

```
git clone https://github.com/SrWither/sm64bsd.git
```

y Reemplazar los archivos Makefile y extract_assets.py de sm64ex por los de este repositorio.

luego hay descargar el siguiente archivo

https://www.mediafire.com/file/nr7s2fx2j082oqa/baserom.us.z64/file

y añadirlo a la carpeta de sm64ex

colocamos el siguiente comando:

```
gmake
```

y cuando termine hay que ir a la siguiente ruta
```
cd build/us_pc
```

y ejecutar el binario

```
./sm64
```

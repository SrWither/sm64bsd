# Preview
![Preview1](https://user-images.githubusercontent.com/59105868/111821034-f7f41900-88c0-11eb-8267-1dad40993fb6.png)

![Preview2](https://user-images.githubusercontent.com/59105868/111821043-fa567300-88c0-11eb-8c0b-77fa6ca3ec22.png)

![Preview3](https://user-images.githubusercontent.com/59105868/111821052-fe829080-88c0-11eb-85af-7b7986790502.png)

## Dependencias
```
git python3 glew sdl2
```

![Dependencias](https://user-images.githubusercontent.com/59105868/111821231-2bcf3e80-88c1-11eb-8c89-01a6d22ee78c.png)

## Instalación

clonar el repositorio del compilador

```
git clone https://github.com/sm64pc/sm64ex.git
```

luego clonar los 2 archivos de este repositorio

```
git clone https://github.com/SrWither/sm64bsd.git
```
![Clone](https://user-images.githubusercontent.com/59105868/111821701-b7e16600-88c1-11eb-8367-8b3af8ac48e2.png)

y Reemplazar los archivos Makefile y extract_assets.py de sm64ex por los de este repositorio.

![Replace](https://user-images.githubusercontent.com/59105868/111822228-4e158c00-88c2-11eb-97b3-f9b4293f0ebd.png)

luego hay descargar el siguiente archivo

https://www.mediafire.com/file/nr7s2fx2j082oqa/baserom.us.z64/file

y añadirlo a la carpeta de sm64ex

![Rom](https://user-images.githubusercontent.com/59105868/111822490-9af96280-88c2-11eb-8b5c-983a1a2b3a1e.png)

colocamos el siguiente comando:
```
chmod +x extract_assets.py
```
y luego

```
gmake
```
![gMake](https://user-images.githubusercontent.com/59105868/111822770-f75c8200-88c2-11eb-91fa-b589aac166b1.png)

y cuando termine hay que ir a la siguiente ruta
```
cd build/us_pc
```

y ejecutar el binario

```
./sm64.us.f3dex2e
```

![Exec](https://user-images.githubusercontent.com/59105868/111823295-88cbf400-88c3-11eb-9a9d-0f0fca9d4eba.png)

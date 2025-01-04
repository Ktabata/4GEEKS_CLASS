# README
## 1. Preparar code space
- Ir a extenciones y instalar python y jupyter
- Crear el archivo gitignore con
```bash
echo -e ".venv\n.env" > .gitignore
```
- Crear el entorno virtual y activarlo
```bash
python -m vnenv .venv
source .venv/bin/activate
```
- Instalar librerias de python para trabajar con jupyter, pandas, matplotlib
```bash
python -m pip ipykernel nbformat pandas seaborn 
```
- Crear Carpetas de trabajo
```bash
mkdir notebooks src app docs
-p data/{raw,baking,final}
```
- Editar un archivo
```bash
touch mitexto.txt
mano mitexto.txt
```
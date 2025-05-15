# Analisis de datos de pruebas saber 11

## 🚀 Instrucciones

Sigue estos pasos para instalar y correr el proyecto en VS Code:

### 🧩 Instalación de R
```bash
    # En Windows:
    # 1. Ir a https://cran.r-project.org/
    # 2. Click en "Download R for Windows"
    # 3. Descargar "base" y seguir el instalador

    # En Debian/Ubuntu:
    sudo apt update
    sudo apt install r-base

    # Verificar la instalación
    R --version
```

### 🧩 Extensión de R en Visual Studio Code

Una vez que hayas instalado R en tu sistema, te recomendamos configurar Visual Studio Code para trabajar con R:

1. Abre Visual Studio Code.
2. Ve a la sección de extensiones (`Ctrl+Shift+X` o haz clic en el ícono de cuadrados en la barra lateral).
3. Busca la extensión llamada **"R Extension"** (autor: Yuki Ueda) o directamente **"R Language Support"**.

   ![Buscar extensión de R en VS Code](images/Rimage.png)

4. Haz clic en **Instalar**.

### 🧩 Instalar paquetes necesarios para RMarkdown

Inicia R en la terminal y ejecuta:

```r
    install.packages(c("rmarkdown", "rticles", "bookdown","prettydoc","flexdashboard"))
```
Luego vuelve a la terminal normal con q() e instala pandoc para poder generar el knit
En **Linux (Debian/Ubuntu)**:

```bash
    sudo apt update
    sudo apt install pandoc
```

En **Windows**:

1. Ve a [https://pandoc.org/installing.html](https://pandoc.org/installing.html)
2. Descarga el instalador para Windows y sigue las instrucciones.


### 🧩 Clona el repositorio en tu máquina local

Abre una terminal y ejecuta el siguiente comando 
```bash
git clone https://github.com/mick2332-q/INFORME.git
```

Esto descargará todos los archivos del proyecto en una carpeta local. Luego, navega a la carpeta del proyecto:

```bash
cd /INFORME
```
### 🧩 Extensión para colaboración en tiempo real

Para trabajar conjuntamente y ver los cambios en tiempo real, instala la extensión **Live Share** en Visual Studio Code:

1. Abre Visual Studio Code.
2. Ve a la sección de extensiones (`Ctrl+Shift+X`).
3. Busca **Live Share** (autor: Microsoft).
4. Haz clic en **Instalar**.

![Buscar extensión Live Share en VS Code](images/liveshare.png)
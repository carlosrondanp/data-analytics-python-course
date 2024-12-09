-- Crear el entorno virtual eligiendo la ruta de python que descargaste
python -m virtualenv .venv --python="C:\Program Files\Python312\python.exe"

-- Activar entorno
.\.venv\Scripts\Activate.ps1 

-- Instalar librerías
Install-And-Log -packageName "pandas"
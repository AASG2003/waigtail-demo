# Apuntes wagtail

## Inicializacion del proyecto

### Virtual Environment
Recomendacion crear un virtual environment

#### Crear venv
```bash
py -m venv "ruta_del_proyecto"
```
#### Comandos para activar al venv
| Consola    | Comando                             |
| ---------- | ----------------------------------- |
| cmd        | C:\> <venv>\Scripts\activate.bat    |
| powershell | PS C:\> <venv>\Scripts\Activate.ps1 |

### Instalacion de Wagtail y creacion del proyecto

#### Instalar Wagtail
```bash
pip install wagtail
```

#### Crear el sitio
```bash
wagtail start "nombre_del_proyecto" "ruta"
```

#### Instalar dependencias
```bash
cd "directorio_del_proyecto"
pip install -r requirements.txt
```

#### Creacion de la base de datos
```bash
python manage.py migrate
```

#### Creacion del usuario administrador
```bash
python manage.py createsuperuser
```

#### Iniciar el servidor
```bash
python manage.py runserver
```











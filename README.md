# Proyecto Web Django

Una aplicación web de gestión de usuarios desarrollada con Python y el framework Django con el objetivo de aprender a usar estas herramientas.


# Prerrequisitos

Antes de clonar el proyecto, asegúrate de tener instalado Python y uv (el gestor de paquetes) de forma global en tu sistema.
https://docs-astral-sh.translate.goog/?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es&_x_tr_pto=tc&_x_tr_hist=true#__tabbed_1_1

### Si usas macOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

### Si usas Windows
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# Instalación

git clone https://github.com/filipinsu/django-pagina-web.git
cd django-pagina-web

# Sincroniza el entorno y las dependencias
El siguiente comando creará el entorno .venv

uv sync

# ejecución
uv run manage.py runserver




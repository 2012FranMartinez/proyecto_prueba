# Python Project Template

Esto es un proyecto sobre esxtracción de datos.

## Inicialización del Proyecto

Antes de comenzar, ejecuta el script de inicialización para configurar el nombre y versión de tu proyecto:

### Opción 1: Con parámetros en línea de comandos
```bash
python init_project.py mi-proyecto-nombre 1.0.0
```

### Opción 2: De forma interactiva
```bash
python init_project.py
```
El script te pedirá:
- Nombre del proyecto (será configurado en pyproject.toml)
- Versión (default: 1.0.0)

## Instalación

1. Clona este repositorio:
```bash
git clone <url-del-repositorio>
cd <nombre-del-proyecto>
```

2. Crea un entorno virtual:
```bash
python -m venv venv
```

3. Activa el entorno virtual:
- **Windows:**
```bash
.\venv\Scripts\activate
```
- **Linux/Mac:**
```bash
source venv/bin/activate
```

4. Instala las dependencias:
```bash
pip install -r requirements.txt
```

## Uso

```bash
python main.py
```

## Estructura del Proyecto

```
.
├── .claude/              # Configuración de Claude Code
│   ├── agents/          # Agentes personalizados
│   └── settings.local.json
├── .vscode/             # Configuración de VS Code
├── src/                 # Código fuente principal
├── tests/               # Tests unitarios
├── no_subir/            # Archivos locales (no se suben a git)
├── main.py              # Punto de entrada
├── requirements.txt     # Dependencias
└── pyproject.toml       # Configuración del proyecto
```

## Contribuir

Instrucciones para contribuir al proyecto.

## Licencia

Especifica la licencia de tu proyecto.

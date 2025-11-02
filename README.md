# 🧠 Uso básico de Git y GitHub

Este documento explica, con mis propias palabras, los **principales comandos de Git** y el **proceso paso a paso** para subir cambios a un repositorio de GitHub.  
Incluyo también las **capturas de pantalla** que muestran cada etapa del proceso.

---

## 📘 1. Principales comandos de Git

| Comando | Descripción |
|----------|--------------|
| `git init` | Inicializa un nuevo repositorio Git en la carpeta actual. |
| `git status` | Muestra el estado actual del repositorio (archivos modificados, sin seguimiento, etc.). |
| `git add .` | Agrega todos los archivos al área de preparación (staging area). |
| `git commit -m "mensaje"` | Guarda los cambios en el repositorio local con un mensaje descriptivo. |
| `git log` | Muestra el historial de commits realizados. |
| `git remote add origin [URL]` | Conecta el repositorio local con un repositorio remoto en GitHub. |
| `git push -u origin main` | Envía los cambios confirmados al repositorio remoto (rama principal). |
| `git pull` | Descarga los cambios más recientes desde el repositorio remoto. |
| `git clone [URL]` | Crea una copia local de un repositorio existente en GitHub. |

---

## ⚙️ 2. Proceso para subir un proyecto a GitHub

### 🧩 Paso 1: Inicializar el repositorio
```bash
git init

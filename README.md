# 🌐 **Uso  Git y GitHub**

### En este documento se explica **los comandos de Git** y el proceso paso a paso para subir cambios a un **repositorio de GitHub**.  

---

## 📘 **Principales comandos de Git**

| Comando | Descripcion |
|----------|--------------|
| `git init` | Inicializa un nuevo repositorio Git en la carpeta actual |
| `git status` | Muestra el estado actual del repositorio (archivos modificados, sin seguimiento, etc.) |
| `git add .` | Agrega todos los archivos al area de preparacion |
| `git commit -m "mensaje"` | Guarda los cambios en el repositorio local con un mensaje descriptivo |
| `git log` | Muestra el historial de commits realizados. |
| `git remote add origin [URL]` | Conecta el repositorio local con un repositorio remoto en GitHub |
| `git push -u origin main` | Envia los cambios confirmados al repositorio remoto |
| `git push` | Envia commits a la rama remota configurada. |
| `git pull` | Descarga los cambios mas recientes desde el repositorio remoto |
| `git clone [URL]` | Crea una copia local de un repositorio existente en GitHub |

---


## 🛠️ **Proceso para subir un proyecto a GitHub**

### 📂 1. Crea una carpeta en este caso **ProyectoGIT** y luego crea una carpeta que diga imagenes puedes ponerla en cualquier lugar

## Ejemplo:

**C:\Users\Equipo\Desktop\ProyectoGIT\Imagenes**

---

### ☑️ 2. Abre la terminal donde se encuentre la carpeta ya creada y digita los comandos que se indiquen en los siguientes pasos

## Ejemplo:

![Terminal](Imagenes/terminal.png)

---

### ☑️ 3. Crea una carpeta `.git` en el proyecto que le indica que ahora es un repositorio Git.


```bash
git init
```

## Ejemplo:
  
![Parte 1](Imagenes/parte1.png)

---

### ☑️ 4. Permite ver en que archivos estan listos o pendientes de seguimiento

```bash
git status
```

## Ejemplo:

![Parte 2](Imagenes/parte2.png)

---

### ☑️ 5. Agrega todos los archivos del proyecto para ser incluidos en el próximo commit

```bash
git add .
```

## Ejemplo:

![Parte 3](Imagenes/parte3.png)

---

### ☑️ 6. Guarda los cambios localmente con un mensaje que describe lo que hiciste.

```bash
git commit -m "Primera prueba"
```

## Ejemplo:

![Parte 4](Imagenes/parte4.png)

---

### ☑️ 7. Crea un repositorio en GitHub (sin README) y copia su URL.  Luego ejecuta en tu terminal:

```bash
git remote add origin https://github.com/AlejoSoa/ProyectoGIT.git
```

## Ejemplo:

![Parte 5](Imagenes/parte5.png)

---

### ☑️ 💾 8. Subir los cambios a GitHub esto enviara tus commits al repositorio remoto en GitHub.

```bash
git branch -M main
git push -u origin main
```

## Ejemplo:
  
![Parte 6](Imagenes/parte6.png)

---

### ☑️ 9. Abre tu repositorio en GitHub y revisa que los archivos se hayan subido correctamente.

## Ejemplo:
  
![Parte 7](Imagenes/parte7.png)

---



## 🖊️ **Conclusion**

### Git es una herramienta recomendada para el control de versiones que permite llevar el historial de cambios de tu proyecto y GitHub complementa este sistema al ofrecer una plataforma en línea donde los desarrolladores pueden **almacenar, compartir y colaborar** en diversos proyectos de software.

---
git add .
git commit -m "Trabajo terminado"
git push
# Proyecto de Gestión de Ramas main y feature – M2C17

## Descripción del Proyecto
Este proyecto corresponde a una práctica de Git y GitHub enfocada en la creación y gestión de un repositorio local y remoto, el uso de ramas de trabajo (feature branches) y la integración de cambios en la rama principal `main` mediante Pull Requests.

El objetivo fue comprender el flujo de trabajo profesional utilizado en entornos colaborativos.

---

## Tecnologías Utilizadas
- HTML5
- Git
- GitHub
- Markdown

---

## Actividades Realizadas Paso a Paso

### 1️⃣ Configuración Inicial de Git
- Verificación de instalación de Git.
- Configuración del nombre de usuario:
  git config --global user.name "Nombre"
- Configuración del correo electrónico:
  git config --global user.email "correo@example.com"

---

### 2️⃣ Creación del Repositorio Local
- Creación de carpeta del proyecto.
- Inicialización del repositorio:
  git init
- Creación de archivos base:
  - README.md
  - index.html
- Desarrollo de estructura HTML básica.
- Primer commit:
  git add .
  git commit -m "Primer commit con estructura base del proyecto"

---

### 3️⃣ Vinculación con GitHub
- Creación del repositorio remoto en GitHub.
- Vinculación del repositorio local con el remoto:
  git remote add origin URL_DEL_REPOSITORIO
  git branch -M main
  git push -u origin main

---

### 4️⃣ Creación y Gestión de Ramas

#### Rama: feature/navbar
- Creación de la rama:
  git checkout -b feature/navbar
- Implementación de una barra de navegación en index.html.
- Commit de los cambios:
  git add .
  git commit -m "Agrega barra de navegación"
- Push de la rama al repositorio remoto:
  git push -u origin feature/navbar

---

#### Rama: feature/footer
- Creación de la rama:
  git checkout -b feature/footer
- Implementación de un footer básico en index.html.
- Commit de los cambios:
  git add .
  git commit -m "Agrega footer básico"
- Push de la rama al repositorio remoto:
  git push -u origin feature/footer

---

### 5️⃣ Gestión de Pull Requests en GitHub
- Creación de Pull Request desde:
  - feature/navbar → main
  - feature/footer → main
- Revisión de cambios.
- Aprobación y fusión (Merge) desde la interfaz de GitHub.
- Sincronización de cambios en local:
  git checkout main
  git pull origin main

---

### 6️⃣ Actualización del README en Markdown
- Documentación del proceso completo.
- Uso de encabezados, listas y formato Markdown.
- Commit final de actualización:
  git add README.md
  git commit -m "Actualiza documentación del proyecto"
  git push origin main

---

## Estructura Final del Proyecto

/proyecto  
│── index.html  
│── README.md  

---

## Resultado Final
Las funcionalidades desarrolladas en las ramas feature/navbar y feature/footer fueron integradas correctamente en la rama principal main mediante Pull Requests, manteniendo un historial de versiones organizado y un flujo de trabajo profesional.

---

## Conclusión
Este proyecto permitió comprender la importancia del uso de ramas para el desarrollo de nuevas funcionalidades sin afectar directamente la rama principal.

El uso de Pull Requests facilita la revisión, integración y control de cambios, simulando un entorno de trabajo colaborativo real.
Ahora solo:




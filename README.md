# 🖥️ Github Linuxspaces
> **The ultimate bridge between Cloud Containers and Desktop Environments.** > **El puente definitivo entre contenedores en la nube y entornos de escritorio.**

![Project Name](https://img.shields.io/badge/Project-Github_Linuxspaces-blueviolet?style=for-the-badge&logo=github)
![Linux](https://img.shields.io/badge/Linux-X11-orange?style=for-the-badge&logo=linux)
![Environment](https://img.shields.io/badge/Desktop-Fluxbox-blue?style=for-the-badge&logo=windowsterminal)

---

## 📘 Overview / Resumen

### [English]
**Github Linuxspaces** is an experimental project designed to run a fully functional Linux graphical user interface (GUI) inside GitHub Codespaces. By virtualizing a display server, it allows users to execute desktop applications and interact with a window manager directly from their browser or a VNC client.

### [Español]
**Github Linuxspaces** es un proyecto experimental diseñado para ejecutar una interfaz gráfica de usuario (GUI) de Linux completamente funcional dentro de GitHub Codespaces. Al virtualizar un servidor de pantalla, permite a los usuarios ejecutar aplicaciones de escritorio e interactuar con un gestor de ventanas directamente desde el navegador o un cliente VNC.

---

## 🛠️ Installation & Setup / Instalación y Configuración

### 1. Prepare Environment / Preparar Entorno
Update the container and install the core graphical components. / Actualiza el contenedor e instala los componentes gráficos base.

```bash
sudo apt update && sudo apt install -y x11vnc xvfb fluxbox x11-apps

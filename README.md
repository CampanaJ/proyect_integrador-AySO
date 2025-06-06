# Trabajo Integrador - Escaneo de Vulnerabilidades en Sistemas

## 📚 Materia
Arquitectura y Sistemas Operativos  
Tecnicatura Universitaria en Programación (A Distancia)

## 👥 Integrantes
- **Chiappone Michael** – Entorno y pruebas  
- **Campana Jonatan** – Redacción del informe y elaboración del video  

## 📅 Fecha de entrega
05/06/2025

---

## 🛡️ Descripción

Este trabajo integrador tiene como objetivo realizar un escaneo de vulnerabilidades en un sistema operativo GNU/Linux utilizando la herramienta **Lynis**. La finalidad es identificar configuraciones débiles, servicios innecesarios y recomendaciones de seguridad, aplicando conceptos clave de hardening y auditoría.

---

## 📌 Contenido

- **Marco Teórico**: Introducción a las técnicas de escaneo de vulnerabilidades, seguridad proactiva, auditoría, herramientas como Lynis, y principios de hardening.
- **Caso Práctico**: Instalación y ejecución de Lynis en un sistema Ubuntu.
- **Metodología**:
  - Investigación de herramientas de escaneo.
  - Instalación de Lynis.
  - Ejecución del escaneo con `sudo lynis audit system`.
  - Análisis e interpretación del informe generado.
- **Resultados**:
  - Informe con advertencias y sugerencias.
  - Detección de servicios innecesarios activos y configuraciones por defecto.
  - Puntaje de seguridad intermedio.
- **Conclusiones**:
  - Importancia de realizar escaneos regulares.
  - Valor del monitoreo constante en la seguridad informática.

---

## 🧰 Herramientas utilizadas

- Sistema Operativo: Ubuntu.
- Herramienta de escaneo: [Lynis](https://github.com/CISOfy/lynis)
- Maquina Virtual: VirtualBox.

---

## 📎 Recursos Adicionales

- 📷 Capturas de pantalla del informe Lynis
- 📄 Fragmento del log: `/var/log/lynis.log`
- 🎬 Video explicativo: https://youtu.be/VdU9cLnkqW0 

---

## 📖 Bibliografía

- [CIS Controls – Center for Internet Security](https://www.cisecurity.org/controls/)
- [Lynis - ArchWiki](https://wiki.archlinux.org/title/Lynis)
- [Repositorio oficial de Lynis](https://github.com/CISOfy/lynis)
- [Ubuntu Server Docs - Security](https://ubuntu.com/server/docs/security)
- `man lynis` (consulta desde terminal Linux)

---

> Este proyecto académico refleja una aplicación práctica real en el ámbito de la seguridad de sistemas, fomentando la conciencia y proactividad en la administración de entornos operativos.
# Git-DevOps
Este repositorio contiene una guía rápida de los comandos esenciales de Git y un análisis sobre arquitectura de nube, desarrollados durante la unidad de Introducción a DevOps.

🚀 Configuración InicialAntes de empezar, es necesario configurar tu identidad en el sistema.
Definir nombre de usuario: git config --global user.name "Tu Nombre"
Definir correo electrónico: git config --global user.email "tu@email.com" 

🔄 Flujo de Trabajo LocalGit utiliza tres áreas principales para gestionar los cambios: 
el Directorio de Trabajo, el Área de Staging y el Repositorio Local. 
Estado del proyecto: git status — Permite saber qué archivos han sido modificados y cuáles no han sido guardados aún. 
Preparar archivos (Staging): git add <archivo> — Agrega uno o varios archivos al área de preparación para ser incluidos en el próximo commit. 
Confirmar cambios (Commit): git commit -m "mensaje descriptivo" — Guarda permanentemente los archivos del área de staging en el historial local como un "punto de cambio". 

🌐 Sincronización con Repositorios RemotosPara colaborar con otros y respaldar el código en la nube (GitHub/GitLab). 
Subir cambios: git push — Envía tus commits locales al servidor remoto. 
Bajar cambios: git pull — Descarga y actualiza tu repositorio local con los cambios del servidor. 
Clonar proyecto: git clone <url> — Descarga una copia completa de un repositorio remoto a tu equipo. 

📝 Notas de ClaseUn repositorio es un espacio (local o en la nube) que aloja todos los archivos y el historial de un proyecto. 
Los conflictos (merge) surgen cuando dos personas modifican el mismo archivo; Git nos ayuda a resolverlos para integrar el código. 

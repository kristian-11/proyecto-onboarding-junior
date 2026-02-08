Paso,Lo que intentamos,El error que salió,¿Por qué pasó?,La Solución Real
1,Conectar a GitHub,fatal: not a git repository,"Git no estaba ""encendido"" en esa carpeta específica.",Ejecutar git init para crear el motor de rastreo.
2,Subir archivos,fatal: 'origin' does not appear...,Intentamos enviar algo a una dirección que Git aún no conocía.,Primero git add + git commit y luego git remote add.
3,Sincronizar,Ninguno (Éxito),Los archivos viajaron de tu PC a la nube.,git push -u origin main.

 ⚠️ **IMPORTANTE**
Comando,Acción,Explicación para tu Manual
git add .,Stage,"El punto . le dice a Git: ""Agarra TODO lo nuevo (incluyendo docs/ e index.html)""."

"git commit -m ""feat: estructura inicial y reset css""",Commit,Registras la tarea terminada con un mensaje descriptivo.

git push origin main,Push,Subes el trabajo a la oficina virtual (GitHub).


Lección Aprendida: Git funciona por capas. No puedes "enviar" (push) si no has "guardado" (commit), y no puedes "guardar" si no has "encendido" el motor (init).

Comando,Qué hace,Tip de Junior a Senior
cd ..,Retrocede una carpeta.,Úsalo si te equivocas de ruta al entrar.
ls -la,Lista todo (incluyendo lo oculto).,Así podrás ver la carpeta .git que creamos con git init.
git status,Te dice qué falta por guardar.,Úsalo siempre antes de apagar la PC para ver si dejaste algo sin commit.

Columna,Significado Profesional,Acción
Todo,Tareas pendientes que la empresa necesita.,"Aquí pondremos los ""Tickets"" que yo te asigne."
In Progress,Tareas que estás programando en este momento.,Mueve la tarjeta aquí apenas abras VS Code.
Done,"Tareas terminadas, subidas a GitHub y probadas.",Mueve la tarjeta aquí tras el git push.

Elemento,Estado,¿Por qué es importante?
Estructura HTML5,¿Usaste <!DOCTYPE html>?,Indica al navegador que use el estándar más moderno.
Vínculo CSS,¿El <link> está dentro del <head>?,Asegura que los estilos carguen antes de que el usuario vea la página.
CSS Reset,¿Usaste box-sizing: border-box;?,Es vital para que los tamaños de los elementos (padding/border) no rompan tu diseño.
Mensaje de Commit,¿Es descriptivo?,Ayuda a entender el historial del proyecto meses después.

Paso,Concepto,Explicación
12,Variables CSS (:root),Guardar colores en un solo lugar para cambiarlos fácilmente en todo el proyecto.
13,Flexbox Básico,Usar display: flex para alinear el logo y el menú de forma profesional.
14,Semántica HTML,"Usar <header>, <nav> y <section> para que Google y los lectores de pantalla entiendan la web."
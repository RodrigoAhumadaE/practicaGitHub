<h1>Configurara un repositorio nuevo desde una terminal</h1>
<ol>
  <li> git init </li> <!-- iniciar un repocitorio vacio -->
  <li> git add [nombre de los archivos] o .(para agregar todo los archivos) <li>
  <li> git commit -m "[mensaje explicativo]" </li> <!-- crea la versión con los nuevos cambios sin eliminar la anterior -->
  <li> Ir a GitHub y crear un repositorio vacio </li> <!-- inicializa repositorio en nuestra cuenta de GitHub -->
  <li> git add remote origin [url del repositorio vacio] </li> <!-- enlaza el repositorio local con el repositorio en linea -->
  <li> git push -u origin main </li> <!-- actualiza la version actual de nuestro local con el repositorio en linea -->
</ol>
<h1>Crea nueva version y actualiza el repositorio</h1>
<ol>
  <li>git add .</li>
  <li>git commit -m "[mensaje explicativo]"</li>
  <li>git push -u origin main</li>
</ol>
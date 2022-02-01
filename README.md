<h1>Sonido en java 2021</h1>

<h2>Requisitos</h2>

<p>Tener los sonidos en formato .wav</p>

<h2>¿Cómo reproducir sonidos?</h2>

<ol>
  <li>Primero implementamos la <a href="https://github.com/JeanCarlosSC/sonido-en-java-2021/blob/main/src/SClip.java">clase SClip</a>.</li>

  <li>Ahora intanciamos objetos de SClip, cuyo argumento del constructor es <b>la ruta del sonido</b>.</li>

  <li>Sólo resta hacer uso de estos objetos a través de los siguientes métodos:</li>
</ol>

<h3>play()</h3>

<p>Reproduce el sonido por única vez.</p>

<h3>loop()</h3>

<p>Reproduce el sonido en bucle hasta que sea detenido.</p>

<h3>stop()</h3>

<p>Detiene la reproducción del sonido.</p>

<h2>¿Por qué se implementa de esta forma la clase?</h2>

<p>Usualmente los sonidos se reproducen en una interfaz gráfica de usuario, el problema de no usar hilos es que cuando reproduces un sonido el programa se queda congelado hasta que se termina la reproducción, entonces no se podrían reproducir varios sonidos a la vez, ni continuar con la ejecución común de un programa mientras reproduces un sonido. Por eso utilizamos hilos.</p>

<p>Las applets han sido descontinuadas por eso se usan los recursos del paquete javax.</p>

<h2>Posibles problemas</h2>

<p>Las rutas de los sonidos dependen de cómo se ejecute el programa (de la ruta en la que se ejecute), por lo que es posible que varíe.</p>

<p>En este ejemplo no explicaremos ese asunto.</p>

<h2>Más información</h2>

<ol>
  <li>Recursos</li>
  
  <ol>
    <li><a href="https://youtu.be/ZiKH29VVO5U">Video en YouTube</a> donde uso este repositorio.</li>
    <li>Enlace para <a href="https://cloudconvert.com/mp3-to-wav">convertir sonidos</a> .mp3 a .wav</li>
    <li>Enlace para <a href="https://notube.net/es/convert">descargar videos de YouTube</a> (soporta formato .mp3)</li>
  </ol>
  
  <li>Referencia del material usado en el repositorio</li>
  
  <ol>
    <li><a href="https://www.youtube.com/watch?v=YYwjq5v-ALA">Sonido de láser</a> que usé en el repositorio.</li>
    <li><a href="https://www.youtube.com/watch?v=GEo1zya7FyA">Sonido de background</a> que usé en el repositorio.</li>
  </ol>
</ol>

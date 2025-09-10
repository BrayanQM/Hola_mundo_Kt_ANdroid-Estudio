<h1>📱 Hola Mundo con Kotlin y Jetpack Compose</h1>

<p>
Este proyecto es una implementación básica de un <strong>Hola Mundo</strong> en Android utilizando <strong>Kotlin</strong> y <strong>Jetpack Compose</strong>, el moderno toolkit de UI declarativa de Android. 
A diferencia del enfoque tradicional basado en archivos XML para definir interfaces, aquí se utiliza exclusivamente Compose para construir la interfaz directamente en código Kotlin.
</p>

<h2>🚀 ¿Por qué Jetpack Compose?</h2>
<p>
Jetpack Compose representa una evolución en el desarrollo de interfaces para Android. Permite escribir la UI de forma más <em>intuitiva</em>, <em>reactiva</em> y con <em>menos código</em>. 
Al eliminar la necesidad de archivos XML, Compose facilita la creación de interfaces dinámicas y adaptables, manteniendo todo en un solo lenguaje: <strong>Kotlin</strong>.
</p>

<h2>🧩 ¿Qué hace este proyecto?</h2>
<p>
Este proyecto simplemente muestra un mensaje de <strong>"Hola"</strong> en la pantalla del dispositivo Android. 
Aunque es una aplicación muy sencilla, sirve como punto de partida para entender cómo funciona Jetpack Compose y cómo se estructura una app sin XML.
</p>

<h2>🛠️ Tecnologías utilizadas</h2>
<ul>
  <li><strong>Kotlin</strong>: Lenguaje principal para la lógica y la UI.</li>
  <li><strong>Jetpack Compose</strong>: Toolkit declarativo para construir la interfaz.</li>
  <li><strong>Android Studio</strong>: Entorno de desarrollo.</li>
</ul>

<h2>📄 Fragmento de código</h2>
<pre><code>
@Composable
fun Greeting() {
    Text(text = "Hola")
}

@Preview(showBackground = true)
@Composable
fun DefaultPreview() {
    Greeting()
}
</code></pre>

<h2>🎯 Objetivo del proyecto</h2>
<p>
El propósito principal es familiarizarse con Jetpack Compose y demostrar cómo se puede construir una interfaz funcional sin depender de XML. 
Es una excelente base para proyectos más complejos que aprovechen el poder de Compose.
</p>

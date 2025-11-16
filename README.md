# urban-routes-qa-testing-sprint3
QA Testing Project - Urban Routes Car Sharing Application

## 👨‍💻 Sobre este proyecto 📋
Este proyecto consistió en evaluar el diseño, la funcionalidad y la calidad general de una aplicación de reservas de automóviles llamada Urban Routes, utilizando técnicas profesionales de aseguramiento de calidad (QA). El trabajo incluyó desde la creación de listas de comprobación hasta la ejecución de pruebas y el reporte de errores. En total fueron 65 casos de pruebas, 20 de estos fueron reportados como errores en Jira, de los cuales 12 eran crítico, 6 altos y 2 medios. 
________________________________________
## 1. Lista de comprobación del diseño del formulario de reserva
+	Se elaboró una checklist para validar el diseño visual y funcional del formulario de reserva<br> 
+	Se revisó una opción de viaje (por ejemplo: Lujo), verificando:<br>	
• Ortografía y correcta disposición de elementos.<br>
•	Navegación y estructura de la interfaz.<br>
•	Ventanas emergentes: Automóvil reservado, ¿Seguro que quieres cancelar el viaje?, Viaje cancelado.<br>

+ Esta lista se registró en la pestaña “1. Lista de comprobación del diseño”.
________________________________________
## 2. Lista de comprobación de “Método de pago” y “Agregar tarjeta”
+ Se creó una checklist funcional utilizando:<br>
•	Clases de equivalencia<br>
•	Análisis de valores límite<br>

+	Incluyó pruebas positivas y negativas sobre:<br>
•	Selección de método de pago.<br>
•	Ingreso y validación de datos de la tarjeta.<br>

+	Se documentó en la pestaña “2. Lista de comprobación de Método de pago y Agregar tarjeta”.<br>
________________________________________
## 3. Casos de prueba para el botón “Reservar”
+	Se diseñaron casos de prueba basados en los requisitos del botón.
+	Se verificó:<br>
•	Que el botón muestre distancia y duración del viaje (sin recalcular estos valores).<br>
•	Su comportamiento en distintos escenarios positivos y negativos.<br>

+	Se registraron en la pestaña “3. Casos de prueba para el botón Reservar”.
________________________________________
## 4. Casos de prueba para la función de reserva de automóviles
+	Se diseñaron pruebas para toda la funcionalidad de reserva, considerando:<br>
•	Flujo completo de reserva.<br>
•	Comportamientos esperados y fallas potenciales.<br>
•	Pruebas positivas y negativas.<br>

+	Se colocaron en la pestaña “4. Casos de prueba para la reserva”.
________________________________________
## 5. Ejecución de pruebas y reporte de errores
+	Las pruebas se realizaron en dos configuraciones:<br>
•	Google Chrome, 800x600<br>
•	Firefox, 1920x1080<br>
+	Se verificó:<br>
•	Diseño en ambos navegadores.<br>
•	Lógica funcional en un solo entorno.<br>
+	Se marcaron resultados como Aprobado o No aprobado.<br>
+	Los errores encontrados se reportaron en Jira, enlazándolos en la hoja de cálculo.<br>
+	No fue necesario esperar el temporizador de “Agregar licencia de conducir” ya que no estaba implementado.<br>
________________________________________
## Conclusiones 
En esta sección se elaboró un breve resumen que incluye:<br>
+	Experiencia personal como usuario de Urban Routes.<br>
+	Qué funcionalidades se lograron probar.<br>
+	Listado y enlaces a los errores reportados.<br>
+	Recomendación final sobre si el producto está listo para usuarios reales.
________________________________________

## 📁 Estructura del Repositorio

- **📊 jira-reports/**: Documentación completa de bugs encontrados en Jira
- **📝 test-documentation/**: Casos de prueba y documentación técnica  
- **🎯 conclusions/**: Análisis final y métricas del proyecto

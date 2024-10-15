Proyecto: AutoCaptura Sistema Automatizado de Reconocimiento y Almacenamiento de Datos (AC-SARAD)
Introducción
El proyecto AutoCaptura (AC-SARAD) tiene como objetivo transformar el proceso de captura y almacenamiento de datos en organizaciones que dependen de la entrada manual de información. Con la creciente necesidad de optimizar flujos de trabajo y mejorar la precisión de los datos, este sistema automatizado permitirá a los operadores presentar una libreta frente a una cámara. A través de un sistema de reconocimiento óptico de caracteres (OCR), la información escrita será extraída y organizada en hit boxes, donde cada cuadro representará un campo específico en la base de datos de Microsoft Access o en un archivo de Excel.
Desarrollo
El desarrollo de AC-SARAD se llevará a cabo en varias etapas:
1.	Captura de Imagen:
o	Descripción: Utilizando tecnología de visión por computadora con OpenCV, se capturarán imágenes de la libreta a través de la cámara del ordenador.
o	Objetivo: Facilitar la digitalización de la información escrita.
2.	Reconocimiento de Texto:
o	Descripción: Se implementará un sistema de OCR mediante Pytesseract, que transformará la información escrita en texto digital.
o	Objetivo: Convertir el texto manuscrito en datos que puedan ser procesados.
3.	Definición de Hit Boxes:
o	Descripción: Se establecerán áreas específicas (hit boxes) en la imagen capturada, donde cada recuadro corresponderá a un campo particular que se desea llenar en la base de datos (por ejemplo, nombre, fecha, cantidad).
o	Objetivo: Asegurar que la información se organice correctamente antes de ser almacenada.
4.	Procesamiento y Validación:
o	Descripción: El texto extraído será analizado y validado para asegurar que la información se almacene en los recuadros correctos.
o	Objetivo: Minimizar errores en la entrada de datos.
5.	Integración con Bases de Datos:
o	Descripción: Se desarrollará una conexión con Microsoft Access utilizando la biblioteca pyodbc.
o	Objetivo: Permitir la inserción automática de datos en las tablas correspondientes.
6.	Interfaz de Usuario:
o	Descripción: Se creará una interfaz gráfica intuitiva que mostrará las hit boxes de manera visual, facilitando a los operadores ver y corregir los datos antes de su inserción en la base de datos.
o	Objetivo: Mejorar la experiencia del usuario y facilitar la interacción con el sistema.
7.	Uso de la API de OpenAI:
o	Descripción: La API de OpenAI permite integrar modelos de lenguaje que pueden ayudar en la validación, enriquecimiento y procesamiento de datos.
o	Aplicaciones: Se utilizará para analizar y procesar texto, ofrecer sugerencias de entrada y mejorar la precisión de los datos extraídos.
Costos de la API de OpenAI
Los costos de la API son importantes para el presupuesto del proyecto. A continuación, se presentan los costos aproximados en pesos mexicanos (MXN):
•	Modelo GPT-3.5: $0.36 MXN por 1,000 tokens. Para 1,000,000 de tokens: $360 MXN.
•	Modelo GPT-4: $0.54 MXN por 1,000 tokens. Para 1,000,000 de tokens: $540 MXN.
Lenguajes y Tecnologías Utilizadas
1.	Python: Lenguaje principal para el desarrollo del sistema.
2.	OpenCV: Biblioteca de visión por computadora para la captura y manipulación de imágenes.
3.	Pytesseract: Wrapper de Python para el motor de OCR Tesseract.
4.	pyodbc: Biblioteca para la conexión a bases de datos.
5.	HTML/CSS/JavaScript: Tecnologías para el desarrollo de la interfaz gráfica.
6.	API de OpenAI: Para procesamiento de lenguaje natural y enriquecimiento de datos.
Términos del Patrocinio
Objetivo del Patrocinio: El patrocinio busca financiar el desarrollo y la implementación de AC-SARAD, permitiendo su despliegue en diversas organizaciones que requieran optimizar sus procesos de captura y almacenamiento de datos.
Beneficios para el Patrocinador:
1.	Visibilidad: El patrocinador tendrá su marca asociada a un proyecto innovador, lo que puede aumentar su reconocimiento en el sector.
2.	Oportunidades de Networking: Posibilidad de conectar con otras empresas y organizaciones que adopten el sistema.
3.	Acceso Preferencial: Oportunidad de implementar el sistema en sus propias operaciones antes de que esté disponible al público general.
4.	Reportes de Impacto: Recepción de informes periódicos sobre el rendimiento del sistema y su impacto en las organizaciones que lo implementan.
Responsabilidades del Desarrollador (Tú):
1.	Desarrollo del Sistema: Completar todas las etapas de desarrollo y asegurar la calidad del producto final.
2.	Actualizaciones y Soporte: Proporcionar soporte técnico y actualizaciones continuas del sistema.
3.	Transparencia: Mantener una comunicación abierta sobre el progreso del proyecto y el uso de los fondos recibidos.
Conclusión
El proyecto AutoCaptura (AC-SARAD) no solo aborda problemas críticos relacionados con la entrada manual de datos, sino que también promueve un entorno de colaboración y aprendizaje continuo. Al finalizar el proyecto, se espera contar con un sistema robusto que optimice la captura y almacenamiento de datos mediante el uso de hit boxes y la integración de la API de OpenAI, mejorando así la eficiencia operativa y la calidad de la información en las organizaciones.


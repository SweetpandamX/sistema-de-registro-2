Proyecto: AutoCaptura
Sistema Automatizado de Reconocimiento y Almacenamiento de Datos (AC-SARAD)

Introducción
El proyecto AutoCaptura (AC-SARAD) tiene como objetivo transformar el proceso de captura y almacenamiento de datos en organizaciones que dependen de la entrada manual de información. Con la creciente necesidad de optimizar flujos de trabajo y mejorar la precisión de los datos, este sistema automatizado permitirá a los operadores presentar una libreta frente a una cámara. A través de un sistema de reconocimiento óptico de caracteres (OCR), la información escrita será extraída y organizada en hit boxes, donde cada cuadro representará un campo específico en la base de datos de Microsoft Access o en un archivo de Excel.

Desarrollo
El desarrollo de AC-SARAD se llevará a cabo en varias etapas:

Captura de Imagen:

Descripción: Utilizando tecnología de visión por computadora con OpenCV, se capturarán imágenes de la libreta a través de la cámara del ordenador.
Objetivo: Facilitar la digitalización de la información escrita.
Reconocimiento de Texto:

Descripción: Se implementará un sistema de OCR mediante Pytesseract, que transformará la información escrita en texto digital.
Objetivo: Convertir el texto manuscrito en datos que puedan ser procesados.
Definición de Hit Boxes:

Descripción: Se establecerán áreas específicas (hit boxes) en la imagen capturada, donde cada recuadro corresponderá a un campo particular que se desea llenar en la base de datos (por ejemplo, nombre, fecha, cantidad).
Objetivo: Asegurar que la información se organice correctamente antes de ser almacenada.
Procesamiento y Validación:

Descripción: El texto extraído será analizado y validado para asegurar que la información se almacene en los recuadros correctos.
Objetivo: Minimizar errores en la entrada de datos.
Integración con Bases de Datos:

Descripción: Se desarrollará una conexión con Microsoft Access utilizando la biblioteca pyodbc.
Objetivo: Permitir la inserción automática de datos en las tablas correspondientes.
Interfaz de Usuario:

Descripción: Se creará una interfaz gráfica intuitiva que mostrará las hit boxes de manera visual, facilitando a los operadores ver y corregir los datos antes de su inserción en la base de datos.
Objetivo: Mejorar la experiencia del usuario y facilitar la interacción con el sistema.
Uso de la API de OpenAI
Para incorporar capacidades avanzadas de procesamiento de lenguaje natural en AC-SARAD, se considera el uso de la API de OpenAI.

Descripción: La API de OpenAI permite integrar modelos de lenguaje que pueden ayudar en la validación, enriquecimiento y procesamiento de datos.
Aplicaciones: Se utilizará para analizar y procesar texto, ofrecer sugerencias de entrada y mejorar la precisión de los datos extraídos.
Costos de la API de OpenAI
Los costos de la API son importantes para el presupuesto del proyecto. A continuación, se presentan los costos aproximados en pesos mexicanos (MXN):

Modelo GPT-3.5:

Costo: $0.36 MXN por 1,000 tokens.
Para 1,000,000 de tokens: $360 MXN.
Modelo GPT-4:

Costo: $0.54 MXN por 1,000 tokens.
Para 1,000,000 de tokens: $540 MXN.
Conclusión
El proyecto AutoCaptura (AC-SARAD) no solo aborda problemas críticos relacionados con la entrada manual de datos, sino que también promueve un entorno de colaboración y aprendizaje continuo. Al finalizar el proyecto, se espera contar con un sistema robusto que optimice la captura y almacenamiento de datos mediante el uso de hit boxes y la integración de la API de OpenAI, mejorando así la eficiencia operativa y la calidad de la información en las organizaciones.


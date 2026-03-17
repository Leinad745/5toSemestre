# Ecosistema de BIG DATA

## On-premise

Implica que toda la infraestructura de hardware y software ubicada en la organizacion. Hay un mayor control sobre la infraestructura, privacidad, y cumplimiento normativo, pero es de alto costo e implementacion y mantenimiento, con menos flexibilidad y escalabilidad frente a demandas fluctuantes.

### Herramientas On-Premise

#### Hadoop

Es un framework de procesamiento distribuido diseñado para el manejo de grandes volumenes de datos mediante clusteres de hardware estandar. Su arquitectura se basa en dos componentes principales:

- HDFS: Sistema de archivos distribuido que permite almacenar y replicar grandes conjuntos de datos por multiples nodos.
- MapReduce: Modelo de programacion que divide las tareas en pequeños fragmentos para ser procesados de manera paralela, ideal para el procesamiento de grandes volumenes de datos.

#### Apache Spark

Motor de procesamiento en memoria que permite realizar tareas de analisis de datos, procesamiento batch y procesamiento en tiempo real con una velocidad considerablemente superior a Hadoop, evitando uso excesivo de disco duro.

#### Apache Kafka

Plataforma distribuida de mensajeria en tiempo real que permite la publicacion, suscripcion, almacenamiento y procesamiento de flujos de datos. Kafka es ideal para mover grandes volumenes de datos en tiempo real de manera eficiente y escalable.

#### Bases de datos NoSQL

Sistemas diseñados para manejar datos no estructurados o semi-estructurados, como JSON, documentos o datos de graficos. Almacenan y gestionan grandes volumenes de datos generados en tiempo real o de fuentes no relacionales.

## Cloud

Una solucion big data en la nube es la utilizacion de plataformas y servicios basados en la nube para el almacenamiento, procesamiento, analisis y gestionar grandes volumenes de datos de manera eficiente, sin la necesidad de inversion en infraestructura fisica.

### Herramientas cloud en AWS

#### Redshift

Almacen de datos diseñado para realizar consultas complejas y analisis sobre grandes volumenes de datos estructurados.

#### EMR

Servicio de procesamiento de datos masivos basado en Apache Hadoop y Apache Spark que facilita la ejecucion de trabajos de procesamiento distribuido sobre grandes volumenes de datos.

#### Glue

Servicio de ETL (Extract, Transform, Load) completamente administrado que permite preparar y transformar datos para su analis.

#### Amazon S3

Almacenamiento de objetos diseñado para escalar masivamente con capacidades para almacenar datos sin limite.

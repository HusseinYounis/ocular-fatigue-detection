================================================================================
DATASET: Fatiga Ocular en Conductores - Señal EOG Vertical
================================================================================
Título       : Detección de Fatiga Ocular mediante Análisis de Parpadeo en EOG Vertical
Materia      : BI2010 - Análisis de Señales y Sistemas Biomédicos
Institución  : Tecnológico de Monterrey
Equipo       : Equipo 4

================================================================================
OBJETIVO
================================================================================
Cuantificar la fatiga ocular durante una tarea controlada de fijación visual,
mediante el análisis de parpadeos en la señal EOG vertical, estimando el Índice
de Cierre Ocular (ICO/PERCLOS) por participante.

================================================================================
DESCRIPCIÓN EXPERIMENTAL
================================================================================
Se registró la señal EOG vertical de 4 participantes de forma secuencial en una
sesión de laboratorio. Cada participante mantuvo la mirada fija en un punto en
pantalla durante su tiempo asignado. El registro inicia con 1 minuto de estado
basal (ojos abiertos en reposo).

================================================================================
INSTRUMENTACIÓN
================================================================================
- Sistema de adquisición : BIOPAC MP36 / MP150
- Electrodos             : Ag/AgCl periorbiculares (derivación vertical)
  · Electrodo (+)        : Por encima de la pupila (supraorbitario)
  · Electrodo (-)        : Por debajo del ojo (infraorbitario)
  · Referencia           : Canto externo del ojo derecho
- Frecuencia de muestreo : 1000 Hz
- Ancho de banda EOG     : 0.01 - 35 Hz (según literatura)
- Rango operacional      : [-0.50, 0.86] mV (señal completa)
- Software               : AcqKnowledge (BIOPAC)

================================================================================
PARTICIPANTES (ANONIMIZADOS)
================================================================================
ID           | Inicio (s) | Fin (s) | Duración (s)
-------------|-----------|---------|-------------
Basal        |     0     |    60   |     60
Participante_1 |   68   |   220   |    152
Participante_2 |  291   |   374   |     83
Participante_3 |  442   |   498   |     56
Participante_4 |  532   |   622   |     90

================================================================================
DESCRIPCIÓN DE ARCHIVOS
================================================================================
EOG_raw_signal.csv   - Señal EOG completa (time_s, Amp_mV), fs=1000 Hz
                       Download from: https://data.mendeley.com/datasets/w7hm97cts5/2

Data_Dictionary.csv  - Diccionario de variables
Colab_Notebook_Link.txt - Enlace al notebook reproducible en Google Colab
================================================================================

# TFG — Análisis automático de jugadas de voleibol con visión por computador

**Alumno:** Alejandro Márquez Malia  
**Tutor:** Jamal Toutouh El Alamin  
**Universidad:** Universidad de Málaga  

## Descripción
Sistema de análisis automático de jugadas de voleibol a partir de vídeo,
usando visión por computador e inteligencia artificial.

## Tecnologías
- YOLOv8s + ByteTrack — detección y tracking de jugadores
- Homografía — proyección pixel → metros reales
- K-means — separación de equipos
- YOLOv8s-pose — estimación de pose corporal
- Clasificador rule-based — acciones técnicas (remate, recepción, bloqueo)

## Módulos
1. Calibración de homografía
2. Detección y tracking
3. Limpieza y fusión de IDs
4. Análisis espacial: métricas y dashboard
5. Carga física (zonas Z1-Z5)
6. Estimación de pose y clasificación de acciones
7. Evaluación del tracker
8. Exportación de vídeo anotado

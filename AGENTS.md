# AGENTS.md: UTN Ciencia de Datos, TP Final

Instrucciones para agentes de IA. Trabajo final de la Diplomatura en Ciencia de Datos y Análisis Avanzado (UTN.BA), Grupo 6: predicción de intención de compra en e-commerce. Es un **fork** del repo del equipo (original: pablodamicopd/DCDDyAA_Grupo_6_Trabajo_Final); el remoto `origin` es de Carlota (carmaguina).

## Leer primero
1. `README.md` (descripción, metodología y resultados).
2. `DCDDyAA_Grupo_6_Trabajo_Final.ipynb` (notebook principal) y `DCDDyAA_Grupo_6_Trabajo_Final.pdf` (informe).

## Reglas
- Español rioplatense, trato de "vos". Respuestas cortas y claras.
- El notebook se corre con el kernel `venv_UTN (3.11)`, que vive en `C:\proyectos_Car\UTN_Ciencia_de_datos\venv_UTN`. No crear un entorno nuevo dentro de este repo.
- No tocar el notebook, el PDF ni el CSV sin que Carlota lo pida: es trabajo grupal entregado.
- No hacer push al repo original del equipo; solo a `origin` (carmaguina).
- Preguntar antes de `commit` o `push`.

## Contexto general y mantenimiento
Hay un repo de contexto general (lista de todos los proyectos, cómo armar la PC nueva y la rutina de respaldo mensual) en `C:\proyectos_Car\Contexto_General\README.md`. Leerlo si la tarea toca otros proyectos o si pasó más de un mes sin actualizar este repo: en ese caso, proponerle a Carlota hacer el repaso de respaldo (nunca hacerlo sin preguntar).

## Reglas para trabajar con dos IAs (Codex y Claude)
- Una sola IA trabaja en el proyecto a la vez. Antes de empezar: git status y git pull. Al terminar: commit y push (con mi confirmación), para que la otra IA vea los cambios.
- Cada IA guarda sus notas solo en su carpeta: Contexto_Codex\ (Codex) o Contexto_Claude\ (Claude). Pueden leer la carpeta de la otra, pero no modificarla.
- Los archivos compartidos se editan solo si yo lo pido, y se avisa qué cambió.
- Si dos documentos se contradicen, avisarme: no elegir uno en silencio.
- Al terminar cada sesión de trabajo, recordame hacer commit y push, y mostrame git status con lo que quedó sin subir.

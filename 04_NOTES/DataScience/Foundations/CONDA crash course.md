![[CondaCrashCourse.pdf]]

ver entorno: 
conda env list

crear entorno 
conda create --name nombre_entorno python=3.7 pandas=1.0 numpy scipy
' se creo con python=3.8 numpy'

para cambiar/ activar otro entorno

- conda activate nombre_entorno

para volver al entorno base

- conda deactivate

eliminar entorno

- conda env remove --name nombre_entorno

exportar entorno

- conda env export -n base -f environment_base.yml

importar entorno
- conda env create --file nombre_entorno.yml --name "nombre_entorno_a_crear"

Resumen:

![[Cheatsheet_Conda.pdf]]
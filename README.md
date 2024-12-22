# Laboratorio1
DESCRIPCION:Busqueda de rutas en empresa de paqueteria - Creado con "cookiecutter


## Intalacion optima para el laboratorio

  UPDATE: V+ - 24/12/21

  python -m venv venv.RzPlAu.act1
  source venv.RzPlAu.act1/bin/activate
  ==> sacar backup o restaurar el ambiente en directorio backups (respaldo - opcional)

  ## Intalando librerias de python: para jupiter notebook en local
  ``` librerias instaladas
      jupyter-book
      matplotlib
      numpy
      simpleai
      flask
      pydot
      graphviz ...... este se instala con brew (para MAC) o EXE (para Windows)
  ```
  
  pip install jupyter-book matplotlib numpy         # Estandares para Jupiter notebook
  pip install simpleai flask pydot graphviz         # para manejo de grafos
  pip install -r requirements.txt

  #### Librerias de visualización grafica del paso a paso:
  NOTA: Para la Intalacion de librerias de visualizacion grafica:
  ### - brew install graphviz  
  ``` python
  			# Implementa modos de visualizacion TOTAL y PASO A PASO
        # 3 modalidades, no se queden con la implementada
      # -------------------------------------------------------
      used_viewer=BaseViewer()
      #used_viewer=ConsoleViewer() # V+241222: CONSOLE - modo de visualizacion uno a uno graba imagen de paso en disco
      #used_viewer=WebViewer()     # V+241222: WEB     - modo de visualizacion grafica en linea, crea una pagina interactiva
                                   #                             Requiere instalacion de https://graphviz.org/download/
  ```

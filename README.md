# Parcial2_BigData


Parcial #2 de Big Data

Luis Nicolás Arboleda Jiménez

# Flujo de Trabajo
Workflow del parcial

![image](https://user-images.githubusercontent.com/111478322/197245995-a5f4a33b-e807-46ba-accf-d4ae83a0358d.png)

# Flujo con Crawler

![image](https://user-images.githubusercontent.com/111478322/197267858-b2d3e343-d0c3-4e22-9e06-6468d9c6147d.png)

# Jobs
Los jobs aparecen como job-copy o job-copy-copy debido a que se clonaban para no tener que configurar todo el s3 denuevo, y lo único que se cambiaba era el script

![image](https://user-images.githubusercontent.com/111478322/197268129-c2aab010-c704-4e33-96bf-44117c89ce23.png)

# BS4
Todos los programas están probados en local y funciona, el problema es que en aws no se descargan las librerías, la única forma de hacerlo es hacer que la instancia tenga el Bs4 por defecto, y eso se puede hacer pero se intentó y no se logró.

# TERCERA PRE-ENTREGA DE KARY FRANCIA
Proyecto python, comision43870-CODERHOUSE

Este proyecto es una aplicación web desarrollada en Django que brinda diversos cursos. Permite a los usuarios agregar estudiantes, profesores, entregables, 
registrar cursos y pagos, así como realizar búsquedas en la base de datos.
## Contenido

- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Funcionalidades](#funcionalidades)
- [Contribución](#contribución)

## Requisitos

- Python 3.11.4 (python --version)
- Django 4.2.3 (python -m django --version)

## Instalación

1. Clona este repositorio a tu máquina local: git clone https://github.com/KaryFrancia/Tercera_pre_entrega_Francia.git
2. Entra al directorio del proyecto: cd coder43870
3. Crea un entorno virtual y actívalo:
- Windows:
  ```
  python -m venv myenv
  myenv\Scripts\activate
  ```
- macOS/Linux:
  ```
  python3 -m venv myenv
  source myenv/bin/activate
  ```

4. Instala las dependencias: pip install -r requirements.txt

## Uso

1. Ejecuta el servidor de desarrollo de Django: python manage.py runserver
2. Accede a la aplicación en tu navegador visitando: `http://127.0.0.1:8000/`

## Funcionalidades

1. **Página de Inicio**: La página principal de la aplicación.
2. **Buscar**: Busca cursos, estudiantes, profesores, pagos y entregables en la base de datos.
3. **Profesores**: Agrega nuevos docentes y visualiza los docentes actuales.
4. **Estudiantes**: Registra nuevos estudiantes y visualiza los estudiantes actuales.
5. **Cursos**: Guarda nuevos cursos y visualiza los cursos actuales.
6. **Entregable**: Registra nuevos entregables y visualiza los entregables actuales.
7. **Pagos**: Agrega nuevos pagos y visualiza los pagos actuales.

## Contribución

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Crea un fork del repositorio.
2. Crea una rama para tus cambios: `git checkout -b feature/nueva-funcionalidad`
3. Haz tus cambios y realiza commits: `git commit -m "Agrega nueva funcionalidad"`
4. Empuja tus cambios a tu fork: `git push origin feature/nueva-funcionalidad`
5. Abre una solicitud pull en GitHub.
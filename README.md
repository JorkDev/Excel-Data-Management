
# Excel Data Management

Este proyecto permite gestionar datos provenientes de archivos Excel a través de una aplicación interactiva. Los usuarios pueden visualizar, editar y personalizar columnas, así como exportar reportes en múltiples formatos.

## Características

- **Visualización de datos**: Muestra el contenido de un archivo Excel de forma clara y organizada.
- **Edición de columnas**: Permite modificar y eliminar columnas según sea necesario.
- **Personalización de colores**: Opción para cambiar colores de las celdas o columnas.
- **Exportación de reportes**: Genera reportes mensuales en formato XLSX, PDF o CSV.

## Tecnologías Utilizadas

- **Lenguaje**: Python
- **Librerías principales**:
  - [Pandas](https://pandas.pydata.org/)
  - [OpenPyXL](https://openpyxl.readthedocs.io/)
  - [xlsxwriter](https://xlsxwriter.readthedocs.io/)
  - [ReportLab](https://www.reportlab.com/)
  - [PyPDF2](https://pypi.org/project/PyPDF2/)
  - [Tabulate](https://pypi.org/project/tabulate/)
  - [Flask](https://flask.palletsprojects.com/) (si la aplicación es web)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone <URL-del-repo>
   cd <nombre-del-repo>
   ```

2. Crea un entorno virtual e instala las dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate    # En Windows usa venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Agrega tus archivos Excel en la carpeta correspondiente.

## Uso

1. Ejecuta la aplicación:
   ```bash
   python main.py
   ```

2. Accede a la interfaz a través de tu navegador (si la aplicación es web) o utiliza la línea de comandos.

3. Realiza las siguientes operaciones:
   - Visualiza el contenido de tu archivo Excel.
   - Edita, elimina o personaliza columnas.
   - Exporta tu reporte mensual en el formato deseado (XLSX, PDF, CSV).

## Recursos

- [7 Python Excel Libraries In-Depth Review for Developers](https://dev.to/mhamzap10/7-python-excel-libraries-in-depth-review-for-developers-4hf4)
- Documentación oficial de las librerías utilizadas:
  - [Pandas](https://pandas.pydata.org/docs/)
  - [OpenPyXL](https://openpyxl.readthedocs.io/en/stable/)
  - [ReportLab](https://www.reportlab.com/documentation/)

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores o tienes ideas para mejorar el proyecto, no dudes en abrir un issue o enviar un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

# Convert-Py-Exe
Como convertir python a exe con librerias de pyexcel

#Instalar libreria
pip install pyinstaller

pyinstaller --noconfirm --onefile --console --icon "C:/Users/DIGITADOR10/Desktop/P/SCARE/FILES/images.ico" --name "Scare" --hidden-import "pyexcel_io.writers" --hidden-import "pyexcel_xls" --hidden-import "pyexcel_xlsx" --hidden-import "pyexcel_xls.xls" --hidden-import "pyexcel_xlsx.xlsx" --hidden-import "pyexcel_io.readers.csv_in_file" --hidden-import "pyexcel_io.readers.csv_in_memory" --hidden-import "pyexcel_io.readers.csv_content" --hidden-import "pyexcel_io.readers.csvz" --hidden-import "pyexcel_io.writers.csv_in_file" --hidden-import "pyexcel_io.writers.csv_in_memory" --hidden-import "pyexcel_io.writers.csvz_writer" --hidden-import "pyexcel_io.database.importers.django" --hidden-import "pyexcel_io.database.importers.sqlalchemy" --hidden-import "pyexcel_io.database.exporters.django" --hidden-import "pyexcel_io.database.exporters.sqlalchemy" --hidden-import "pyexcel_io.readers.csvr" --hidden-import "pyexcel_io.readers.tsv" --hidden-import "pyexcel_io.readers.tsvz" --hidden-import "pyexcel_io.writers.csvw" --hidden-import "pyexcel_io.writers.csvz" --hidden-import "pyexcel_io.writers.tsv" --hidden-import "pyexcel_io.writers.tsvz" --hidden-import "pyexcel_io.readers.tsv" --hidden-import "pyexcel_io.readers.tsvz"  "C:/Users/DIGITADOR10/Desktop/P/SCARE/Main.py"


#Crear exe con aplicacion
>pip install auto-py-to-exe
>auto-py-to-exe
>agregar opciones
>-Localizar el script main
>oppcion de un archivo
>consola basica
>agregar icono (.ico)
>en avanzado agregar opciones
>--name (nombre del .exe)
>--hidden-import:

hidden-import "pyexcel_io.writers"
--hidden-import "pyexcel_xls"
--hidden-import "pyexcel_xlsx" 
--hidden-import "pyexcel_xls.xls"
--hidden-import "pyexcel_xlsx.xlsx"
--hidden-import "pyexcel_io.readers.csv_in_file" 
--hidden-import "pyexcel_io.readers.csv_in_memory"
--hidden-import "pyexcel_io.readers.csv_content"
--hidden-import "pyexcel_io.readers.csvz"
--hidden-import "pyexcel_io.writers.csv_in_file"
--hidden-import "pyexcel_io.writers.csv_in_memory"
--hidden-import "pyexcel_io.writers.csvz_writer"
--hidden-import "pyexcel_io.database.importers.django"
--hidden-import "pyexcel_io.database.importers.sqlalchemy"
--hidden-import "pyexcel_io.database.exporters.django"
--hidden-import "pyexcel_io.database.exporters.sqlalchemy"
--hidden-import "pyexcel_io.readers.csvr"
--hidden-import "pyexcel_io.readers.tsv"
--hidden-import "pyexcel_io.readers.tsvz"
--hidden-import "pyexcel_io.writers.csvw"
--hidden-import "pyexcel_io.writers.csvz"
--hidden-import "pyexcel_io.writers.tsv"
--hidden-import "pyexcel_io.writers.tsvz"
--hidden-import "pyexcel_io.readers.tsv"
--hidden-import "pyexcel_io.readers.tsvz"

>En configuraciones poner la ruta de salidad

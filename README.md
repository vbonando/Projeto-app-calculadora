# Projeto-Calculadora-App

Utilize dentro do terminal para criar seu app

pyinstaller --name="Calculadora" --noconfirm --noconsole --onefile --add-data='../files/;files' --icon='../files/icon.png' --clean --log-level=WARN --distpath="calculadora_app/dist" --workpath="calculadora_app/build" --specpath="calculadora_app/" Calculadora.py
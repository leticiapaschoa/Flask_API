# Flask API REST

## Setup:
- Criar um ambiente virtual:
```py -m venv venv```

- Instalar o FLask:
```pip install flask```

## API:
- Importar o Flask 
``` from flask import Flask ```

- Definir uma rota e o método respectivo:
```
@app.route('/flask/api/cursos', methods=['GET'])
    def get_cursos():
```

## EXECUTE:
- Executar no terminal:
```
$ python ..\API\run.py
 * Serving Flask app "run" (lazy loading)
 * Environment: development
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 266-011-970
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

## UNIT TEST:
``` test.py
----------------------------------------------------------------------
Ran 2 tests in 2.078s

OK
```

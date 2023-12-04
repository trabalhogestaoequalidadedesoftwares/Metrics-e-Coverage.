# Metrics-e-Coverage.
Crie, no mínimo, 5 testes usando METRICS e COVERAGE e salve as saídas.


coverage report -m
pytest -vv --cov=. --cov-report=term-missing main.py
pytest -vv --cov= main.py
pytest main.py
coverage run -m pytest main.py
pytest -vv main.py

# Setup

```sh
pip install grpcio && pip freeze > requirements.txt
pip install grpcio-tools && pip freeze > requirements.txt

# OR:
# python -m pip install grpcio && pip freeze > requirements.txt
# python -m pip install grpcio-tools && pip freeze > requirements.txt
```

# Development

```sh
docker-compose exec python bash

# winpty docker-compose exec python bash
# winpty docker-compose exec python sh

# Run when start or add more modules.
cd /var/www/app/python
pip install --no-cache-dir -r requirements.txt
```

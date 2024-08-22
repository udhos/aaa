# aaa

# Start

```
git clone https://github.com/ory/kratos.git
cd kratos
git checkout master
docker-compose -f quickstart.yml -f quickstart-standalone.yml up --build --force-recreate
```

Source: https://www.ory.sh/docs/kratos/quickstart

Open http://127.0.0.1:4455/welcome

# Stop

```
docker-compose -f quickstart.yml down -v
docker-compose -f quickstart.yml rm -fsv
```

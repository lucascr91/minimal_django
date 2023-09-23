# minimal django

Este repositório contém as configurações mínimas para rodar um projeto de django usando docker. Por exemplo, para iniciar um projeto chamado app, basta fazer:

 ```
docker compose run --rm app django-admin startproject app .
```

Os arquivos do projeto estrão dentro da pasta app e as alterações feitas nessa pasta irão se refletir no container.

# Todo List

## Requisitos:
- Python >= 3.11.4
  - Instalar no site do python - <a href="https://www.python.org/downloads/" target="_blank">Acesse aqui!</a>
- Django >= 4.2.4
  - Instalação via terminel -> Windows: ```pip install django``` - Linux: ```pip install django``` ou ```pip3 install django```

## Execultando projeto
1. Através do GIT clone o repositório do projeto:
    - ```git clone https://github.com/Gabrielrc11/todolist.git```
2. Entre dentro da pasta **mvp_roleon** com o comando:
    - ```cd todolist```
4. Execulte o seguinte comando para rodar o projeto em debug:
    - ```python manage.py runserver```
> [!NOTE]
> Para parar a execução do projeto use, no terminal, as teclas: ```Ctrl + C```

## Padronizações
### Commits
Os commits devem seguir o padrão mostrado no site do <a href="https://www.conventionalcommits.org/pt-br/v1.0.0/" target="_blank">Conventional Commits</a>

## Branches
A padronização das **Branches** é parecida com a padronização dos commits, onde o nome da branch precisa ter um ***préfixo*** da seguinte forma:
 - ```feature/name_branch```
Esses **préfixo** podem ser:

| Préfixos  | Descrição |
| ------------- | ------------- |
| feature | Usado na branch que tem o objetivo de adicionar, refatorar ou remover um recurso  |
| bugfix  | Usado na branch que tem o objetivo de corrigir um bug  |
| hotfix  | Usado na branch que tem o objetivo de alterar o código com uma solução temporária e/ou sem seguir o processo normal (geralmente devido a uma emergência)  |
| improvement  | Usado na branch que tem o objetivo criar uma melhoria para algo que já existente, seja de performance, de escrita, de layout, etc. |

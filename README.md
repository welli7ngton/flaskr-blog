# Flaskr - Blog

## Descrição
Este repositório contém o código-fonte de um blog simples desenvolvido usando o framework Flask. O projeto é baseado no tutorial disponível na documentação oficial do Flask, que fornece uma introdução passo a passo ao desenvolvimento de aplicativos web com Flask.

## Pré-requisitos
Antes de executar este projeto, certifique-se de ter o seguinte software instalado em sua máquina:
- Python 3.x
- Flask
- Um navegador web compatível

## Instalação
1. Clone este repositório em seu ambiente de desenvolvimento local usando o seguinte comando:

    `git clone https://github.com/welli7ngton/flaskr-blog.git`

2. Navegue até o diretório do projeto:

    `cd flask-tutorial`

3. Instale as dependências do Python listadas no arquivo `requirements.txt`:

    `pip install -r requirements.txt`


## Executando o Projeto
1. Após a conclusão da instalação, você deve iniciar o banco de dados com o seguinte comando:

    `flask --app init-db`

3. Agora você pode iniciar o servidor de desenvolvimento Flask com o seguinte comando:

    `flask --app flaskr run`

4. O servidor Flask estará em execução localmente em `http://127.0.0.1:5000/`.

## Tutorial Original
O tutorial original para este projeto pode ser encontrado na documentação oficial do Flask em [Flask Tutorial: Flaskr](https://flask.palletsprojects.com/en/3.0.x/tutorial/).

## Estrutura do Projeto
- `__init__.py`: O ponto de entrada da aplicação Flask.
- `requirements.txt`: Arquivo de texto contendo as dependências do Python necessárias para este projeto.
- `templates/`: Diretório contendo os modelos HTML usados para renderizar as páginas da web.
- `static/`: Diretório contendo arquivos estáticos, como folhas de estilo CSS, JavaScript, imagens, etc.
- `db/`: Diretório opcional que poderia conter um banco de dados SQLite ou outro mecanismo de armazenamento de dados.

## Contribuindo
Contribuições são bem-vindas! Se você deseja melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar uma pull request.

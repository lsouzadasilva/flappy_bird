# flappy_bird 🦜

Importância do PyInstaller e do Pygame

PyInstaller

O PyInstaller é uma ferramenta essencial para transformar scripts Python em executáveis independentes. Isso permite distribuir sua aplicação sem que os usuários precisem instalar o Python ou outras dependências.

Pygame

O Pygame é uma biblioteca popular para criação de jogos e aplicações multimídia em Python. Ele fornece funcionalidades essenciais como manipulação de eventos, renderização de gráficos e controle de som.

Instalação

Antes de executar o projeto, é necessário instalar as dependências. Certifique-se de ter o Python instalado e utilize os seguintes comandos:

pip install pygame pyinstaller

# Como Executar o Arquivo

Se quiser gerar um executável para distribuir o projeto sem a necessidade do Python instalado, use o PyInstaller:

pyinstaller --onefile --windowed main.py

Isso gerará um executável na pasta dist/, que pode ser executado normalmente no sistema operacional.

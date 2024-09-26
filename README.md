### Instruções para Organizar o Projeto e Executar o Flappy Bird com IA
1. **Organização dos Arquivos:** Crie uma pasta principal para o projeto. Dentro dessa pasta, crie uma subpasta chamada `imgs` para armazenar todas as imagens do projeto. Na pasta principal, deve haver: a pasta `imgs`, o arquivo `config.txt`, e o script do jogo.
2. **Instalação das Bibliotecas Necessárias:** Para rodar o projeto, você precisará instalar as seguintes bibliotecas: **pygame**: Biblioteca para criar jogos em Python. **neat-python**: Biblioteca para a implementação de Neuroevolução de Topologias Aumentadas. Abra seu terminal ou prompt de comando e execute o seguinte comando: ```bash pip install pygame neat-python ```
3. **Executar o Jogo com IA:** Para executar o jogo com a IA, basta rodar o código normalmente.
4. **Jogar Manualmente:** Se você deseja jogar manualmente, altere a variável `IA_PLAYER` para `false` no início do código: ```python IA_PLAYER = False  # Mude para False para jogar manualmente ```
5. **Configurar a IA:** Na linha 269 do código, você encontrará uma condição dentro de um `if` que limita a IA. Essa configuração evita que a IA rode infinitamente e permite a geração de um relatório sobre a sobrevivência.

Em caso de dúvidas, pode enviar no meu linkedin que eu irei responder: https://www.linkedin.com/in/rafaelpierin/

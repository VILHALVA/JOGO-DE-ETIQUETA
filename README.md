# JOGO DE ETIQUETA
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
O aplicativo é um jogo de escolhas com uma narrativa interativa. O jogo visa explorar as escolhas éticas e morais do jogador, oferecendo uma experiência de tomada de decisões em um contexto ficcional. As principais características são:

1. **História Interativa:**
   - Apresenta uma situação hipotética em que o jogador precisa fazer uma escolha difícil relacionada à vida de sua esposa e a oportunidade de emprego.

2. **Escolhas do Jogador:**
   - Oferece ao jogador quatro opções de resposta (A, B, C, D) para lidar com a situação apresentada.

3. **Elemento Aleatório:**
   - Utiliza um elemento de aleatoriedade para determinar uma resposta pré-estabelecida para o robô.

4. **Feedback e Consequências:**
   - Fornece feedback e consequências com base na escolha do jogador, incluindo mensagens que refletem o desempenho e a moralidade das escolhas feitas.

5. **Contagem de Tentativas:**
   - Conta o número de tentativas necessárias para o jogador chegar a uma escolha que coincide com a resposta pré-estabelecida do robô.

6. **Resultado Final:**
   - Apresenta um resultado final, destacando o desempenho do jogador com base no número de tentativas.

7. **Ações de Pós-Jogo:**
   - Executa ações diferentes com base no desempenho do jogador, como abrir o YouTube se o jogador teve um bom desempenho ou abrir a Wikipedia se o desempenho foi ruim.

8. **Tempo de Espera:**
   - Adiciona um tempo de espera se o jogador ultrapassar um certo número de tentativas, antes de realizar a ação pós-jogo.

## EXECUTANDO O JOGO:
1. Acesse o diretório `./CODIGO` e execute o arquivo Python com o seguinte comando:

   ```bash
   python CODIGO.py
   ```

2. O jogo apresentará uma situação hipotética, e você deverá escolher entre **quatro opções**: **A**, **B**, **C** ou **D**.

3. Leia atentamente a situação e selecione a opção que você considera mais adequada.

4. Digite a **letra correspondente** à sua escolha e pressione **Enter**.

5. Se sua escolha **coincidir com a resposta aleatória** definida pelo computador, você vence.

6. Caso contrário, o jogo informará que você perdeu e exibirá mensagens relacionadas à sua escolha.

7. O jogo avaliará seu desempenho com base no **número de tentativas** até a vitória e exibirá um **feedback final**.

8. Ao término da partida:

   * Se você vencer **com até 5 tentativas**, o jogo abrirá o **YouTube** automaticamente.
   * Se precisar de **mais de 5 tentativas**, o jogo abrirá a **Wikipedia**.

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
- O executável gerado está disponível apenas para sistemas **Windows x64** e pode ser encontrado no diretório `./APP`. Para executá-lo, basta dar dois cliques. O executável é bastante útil caso o Python não esteja instalado. Trata-se da mesma aplicação do arquivo `./CODIGO/CODIGO.py`. Se desejar, você pode recompilá-lo novamente.

- É importante explicar que ao executar o arquivo executável deste jogo, é possível que o antivírus dispare um alerta de segurança. Isso ocorre porque o jogo abre sites no navegador da web diretamente.

    **Para lidar com isso, há 2 alternativas:**

    1. **Adicionar exceção ao antivírus:** Você pode optar por adicionar uma exceção ao antivírus para permitir que o jogo abra os sites no navegador sem disparar alertas. Isso geralmente pode ser feito acessando as configurações do antivírus e adicionando o arquivo executável do jogo à lista de exceções.

    2. **Executar apenas o `CODIGO.py`:** Uma alternativa é optar por executar apenas o arquivo de código-fonte Python (`CODIGO.py`). Isso evita que o antivírus dispare alertas, já que você e o sistema podem inspecionar o código fonte diretamente.
  
### 2. GERANDO:
> **IMPORTANTE:** Antes de gerar o novo `executável`, certifique-se de excluir o arquivo `./APP/JOGO DE ETIQUETA.exe`.

   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável:**
   - No diretório `./CODIGO`, execute o comando abaixo para gerar o executável a partir do arquivo `.spec`:

   ```bash
   pyinstaller EXECUTAVEL.spec
   ```

   - O arquivo `JOGO DE ETIQUETA.exe` será criado dentro da pasta `./CODIGO/dist`.

   - Após a geração, você pode mover o executável para `./APP` e remover as pastas temporárias `./CODIGO/build` e `./CODIGO/dist`.

   - Para executar o aplicativo, basta dar dois cliques no arquivo `.exe`.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)

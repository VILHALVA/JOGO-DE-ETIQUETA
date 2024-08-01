# JOGO DE ETIQUETA
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
O aplicativo é um jogo de escolhas com uma narrativa interativa. As principais características são:

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

O jogo visa explorar as escolhas éticas e morais do jogador, oferecendo uma experiência de tomada de decisões em um contexto ficcional.

## EXECUTANDO O JOGO:
1. Navegue até o diretório `./CODIGO`, e execute o arquivo Python com o comando:
```bash
python CODIGO.py
```
2. O jogo apresentará uma situação hipotética e você precisará escolher entre quatro opções (A, B, C ou D) para lidar com essa situação.
3. Leia atentamente a situação e escolha a opção que você acha ser a melhor.
4. Digite a letra correspondente à sua escolha e pressione Enter.
5. Se sua escolha coincidir com a resposta aleatória do computador, você vence.
6. Se sua escolha não coincidir, o jogo indicará que você perdeu e oferecerá algumas mensagens relacionadas à sua escolha.
7. Dependendo do número de tentativas que você leva para vencer, o jogo dará um feedback final.
8. Após o final do jogo, dependendo do seu desempenho, ele abrirá automaticamente o YouTube se você vencer com até 5 tentativas, ou abrirá a Wikipedia se você precisar de mais de 5 tentativas para vencer.

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
   - Este arquivo executável está disponível apenas para `Windows X64`. Para executá-lo, basta dar dois cliques. O executável é bastante útil caso o Python não esteja instalado. Trata-se da mesma aplicação do arquivo `CODIGO.py`. Se desejar, você pode recompilá-lo novamente; é para isso que forneci o arquivo `imagem.ico`.

### 2. GERANDO:
   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável:**
   - Para gerar o executável, utilize o comando `pyinstaller` seguido de opções:
      - `--icon="imagem.ico"`: Especifica o ícone do executável.
      - `-F`: Gera um único arquivo executável em vez de vários.
      - `CODIGO.py`: Substitua "CODIGO.py" pelo nome do seu arquivo Python principal.
   ```bash
   pyinstaller --icon="imagem.ico" -F CODIGO.py
   ```

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)
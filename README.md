# 🎮 Campo Minado em Java

## 📖 Sobre o Projeto

Este projeto é uma implementação do clássico jogo **Campo Minado** desenvolvido em **Java**. O objetivo do jogo é abrir todos os campos que não contêm minas, marcando corretamente os campos que possuem minas. O projeto foi desenvolvido para demonstrar boas práticas de programação, como o uso de **Orientação a Objetos**, **Design Patterns** (como o Observer), e manipulação de eventos de interface gráfica com **Swing**.

---

## 🚀 Funcionalidades

- **Abertura de Campos:**  
  - Clique com o botão esquerdo para abrir um campo. Se o campo contiver uma mina, o jogo termina. Caso contrário, o campo exibe o número de minas vizinhas.  
  - Exemplo: Abrir um campo seguro para revelar o número de minas ao redor.

- **Marcação de Campos:**  
  - Clique com o botão direito para marcar um campo como suspeito de conter uma mina.  
  - Exemplo: Marcar um campo onde você acredita que há uma mina.

- **Vitória e Derrota:**  
  - O jogador vence quando todos os campos seguros são abertos.  
  - O jogador perde se abrir um campo que contém uma mina.  
  - Exemplo: Receber uma mensagem de vitória ou derrota ao final do jogo.

- **Reinício do Jogo:**  
  - Após uma vitória ou derrota, o jogo pode ser reiniciado automaticamente.  
  - Exemplo: Reiniciar o jogo para tentar novamente.

- **Interface Gráfica Intuitiva:**  
  - O jogo possui uma interface gráfica simples e responsiva, construída com a biblioteca **Swing**.  
  - Exemplo: Botões interativos para cada campo do tabuleiro.

---

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem principal do projeto, com uso de POO (Programação Orientada a Objetos).  
- **Swing**: Biblioteca para criação da interface gráfica.  
- **GitHub**: Versionamento do código e hospedagem do projeto.  

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Swing](https://img.shields.io/badge/Swing-ED8B00?style=for-the-badge&logo=java&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

---

## 📦 Estrutura do Projeto

O projeto está organizado da seguinte forma:  

1. **Classes Principais:**  
   - `Campo`: Representa um campo do tabuleiro, podendo conter uma mina ou estar vazio.  
   - `Tabuleiro`: Gerencia a lógica do jogo, incluindo a criação do tabuleiro e a verificação de vitória/derrota.  
   - `CampoEvento`: Enumeração que define os eventos que podem ocorrer em um campo (abrir, marcar, explodir, etc.).  
   - `CampoObservador`: Interface para notificação de eventos ocorridos em um campo.  
   - `ResultadoEvento`: Classe que representa o resultado do jogo (vitória ou derrota).  

2. **Interface Gráfica:**  
   - `TelaPrincipal`: Janela principal do jogo, onde o tabuleiro é exibido.  
   - `PainelTabuleiro`: Painel que contém os botões que representam os campos do tabuleiro.  
   - `BotaoCampo`: Botão personalizado que representa um campo do tabuleiro, com interações de clique.  

3. **Recursos:**  
   - Pasta `src/`: Contém o código-fonte do projeto.  

---

## 🎯 Como Usar

1. **Clone o Repositório:**  
   - Clone o repositório para sua máquina local:  
     ```bash
     git clone https://github.com/seu-usuario/seu-repositorio.git
     ```

2. **Execute o Projeto:**  
   - Abra o projeto em uma IDE Java (como IntelliJ IDEA ou Eclipse).  
   - Execute a classe `TelaPrincipal` para iniciar o jogo.  

3. **Interaja com o Jogo:**  
   - Clique com o botão esquerdo para abrir campos.  
   - Clique com o botão direito para marcar campos suspeitos de conter minas.  
   - Tente abrir todos os campos seguros sem detonar nenhuma mina!  

4. **Reiniciar o Jogo:**  
   - Após uma vitória ou derrota, o jogo será reiniciado automaticamente.  

---

## 🧑‍💻 Desenvolvedor

<table>
  <tr>
    <td align="center">
      <a href="https://www.linkedin.com/in/guilhermegeisler/">
        <img src="https://avatars.githubusercontent.com/u/53203780?s=400&u=9a85ac6d2d3c55a872ab0bafd1d38d8bd0da5cc4&v=4" width="100px;" alt="Foto do Guilherme Geisler"/><br>
        <sub>
          <b>Guilherme Geisler</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

---

## 📧 Contato

Se tiver alguma dúvida, sugestão ou quiser entrar em contato, fique à vontade:  

- **LinkedIn**: [Guilherme Geisler](https://www.linkedin.com/in/guilhermegeisler/)  
- **Email**: [guilherme.sgeisler@gmail.com](mailto:guilherme.sgeisler@gmail.com)  

---

Feito com ❤️ por [Guilherme Geisler](https://www.linkedin.com/in/guilhermegeisler/).

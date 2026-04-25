# Remake Dots and Boxes

Jogo desenvolvido em Java, inspirado no clássico Dots and Boxes, com foco na implementação de suas principais mecânicas de jogabilidade. 

O projeto foi criado como trabalho prático da disciplina Linguagem e Técnicas de Programação II, no curso técnico em Informática do CEFET-MG, utilizando a biblioteca LibGDX para gerenciamento de recursos gráficos e multimídia.

## Status do Projeto

Projeto estável e pronto para uso.

Este projeto foi desenvolvido para fins acadêmicos e não está mais em manutenção. O projeto é mantido aqui como demonstração de conceito e aprendizado.

---

## Objetivos
- Praticar lógica de programação
- Aplicar conceitos de Programação Orientada a Objetos no desenvolvimento de jogos
- Recriar as principais mecânicas, regras e elementos visuais do jogo base
- Adquirir experiência no desenvolvimento de jogos utilizando a biblioteca LibGDX

## Funcionalidades
- Jogo por turnos entre dois jogadores
- Desenho de linhas horizontais e verticais na grade
- Sistema de detecção de caixas completas
- Marcação automática de pontos ao completar uma caixa
- Exibição da pontuação do jogador e da máquina
- Vitória ou derrota ao final da partida

## Tecnologias Usadas
- Java
- Gradle
- LibGDX
- VS Code

---

## Como Executar

### Requisitos
- JDK 8 ou superior
- Gradle (opcional, caso não utilize o wrapper incluído no projeto)

### Execução Via terminal
1. Baixe e extraia o arquivo `.zip` do projeto
2. Navegue até o diretório raiz do projeto pelo terminal
3. Execute o comando abaixo:
```
gradlew lwjgl3:run
```

### Execução Via IDE
1. Baixe e extraia o arquivo `.zip` do projeto
2. Abra o projeto em sua IDE de preferência 
3. Aguarde o carregamento e a sincronização das dependências do Gradle
4. Navegue até o seguinte arquivo: `lwjgl3/src/main/java/com/tp1/dotsandboxes/lwjgl3/Lwjgl3Launcher.java`
5. Execute a classe `Lwjgl3Launcher`

---

## Como Jogar

### Objetivo
Completar o maior número de caixas.

### Regras
- Quem completar a última aresta de um quadrado ganha um ponto
- Quem completar o maior número de caixas antes do fim da partida vence

### Controles
- **🖱 Botão direito do mouse**: Conectar pontos adjacentes nas linhas horizontais ou verticais

### Dica
Execute o jogo em modo janela, na resolução inicial, para evitar problemas de escala gráfica.

---

## Telas do Jogo

Capturas de tela mostrando a interface e a jogabilidade do projeto.

### Tela Inicial
<img width="500" height="331" alt="image" src="https://github.com/user-attachments/assets/81a536d6-107d-4d13-ad64-296c550e4789" />

### Tela do Jogo no Modo Fácil
<img width="500" height="331" alt="image" src="https://github.com/Grupo-8-2025/TrabalhoPratico1/blob/main/assets/Jogo-DotsAndBoxes%2025_05_2025%2019_36_36.png" />

### Tela do Jogo no Modo Difícil
<img width="500" height="331" alt="image" src="https://github.com/user-attachments/assets/83acd784-01e4-43fb-8a34-da2f805de3da" />

### Telas Finais
<img width="500" height="331" alt="image" src="https://github.com/user-attachments/assets/9c2458f5-6426-492f-89c0-02840e3c07c6" />
<br>
<img width="500" height="331" alt="image" src="https://github.com/Grupo-8-2025/TrabalhoPratico1/blob/main/assets/Jogo-DotsAndBoxes%2025_05_2025%2019_38_33.png" />

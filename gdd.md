# Game Design Document

---

## Overview

### Theme / Setting / Genre
* **Tema:** Horror Sci-Fi com foco em terror sensorial (som e iluminação) e estética cyberpunk decadente.
* **Configuração:** O jogo se passa em uma nave espacial industrial pertencente a uma megacorporação, à deriva no espaço profundo após a fuga de uma entidade alienígena. A nave apresenta sistemas instáveis, luzes falhando, painéis holográficos com glitch e atmosfera claustrofóbica.
* **Gênero:** Terror em primeira pessoa, com mecânicas de stealth e exploração.

### Core Gameplay Mechanics Brief
* **Mecânica 1 – Movimento Baseado em Risco Sonoro:** O tipo de movimentação do jogador (andar, correr ou agachar) influencia diretamente o nível de ruído gerado e o raio de detecção do alien.
* **Mecânica 2 – Sistema de Furtividade e Esconderijo:** O jogador pode utilizar pontos específicos da nave para se esconder temporariamente, reduzindo a chance de detecção.
* **Mecânica 3 – Defesa Limitada (Taser):** Ferramenta não letal que paralisa o alien por alguns segundos, utilizando bateria limitada.
* **Mecânica 4 – Sistema de Autodestruição com Timer:** Ativar a autodestruição inicia uma contagem regressiva que aumenta drasticamente a agressividade do alien e a tensão ambiental.
* **Mecânica 5 – Detecção de Som via Microfone:** Sons captados pelo microfone do jogador podem alertar o alien, integrando o ambiente real ao jogo.

### Targeted Platforms
* PC

---

## Monetization Model

* **Monetização:** Modelo Premium – Jogo pago com uma única compra.
* **Link:** Não aplicável (a monetização é baseada na venda direta do jogo).
* **Venda de trilha sonora:** R$ 15,00
* **Custo do jogo:** R$ 50,00
* **Livro de arte:** R$ 15,00
* **Expansão:** R$ 35,00
* **Patrocínios:** R$ 1.000,00 (por empresa/marca)

---

## Project Scope

### Game Time Scale
* **Custo Estimado:** R$ 26.380,00
* **Tempo de Desenvolvimento:** 3 a 4 meses

### Team Size
**Equipe Principal:**
* **Programador Principal:** Responsável pela implementação das mecânicas de jogo, IA, sistema de microfone e sistema de física.
* **Artista 3D:** Criar os modelos dos personagens, nave e ambientes.
* **Animador 3D:** Responsável por animações 3D.

**Equipe de Marketing:**
* **Community Managers:** Criar e manter a presença do jogo nas redes sociais.

### Licenças / Hardware / Outros Custos
* Licenciamento de software (3ds MAX, Unity 6, Blender).
* Custos de servidores para testagem, se aplicável.
* **Custos Totais (Breakdown extra):** R$ 2.000,00

---

## Influences

* **Influência #1: Alien, o Oitavo Passageiro**
    * **Medium:** Filme
    * **Explicação:** Atmosfera claustrofóbica, isolamento e sensação constante de ser caçado por uma criatura invisível.
* **Influência #2: Blade Runner**
    * **Medium:** Filme
    * **Explicação:** Estética cyberpunk decadente, iluminação contrastante e ambientação tecnológica opressiva.
* **Influência #3: Cyberpunk 2077**
    * **Medium:** Jogo
    * **Explicação:** Interfaces futuristas, identidade corporativa e ambientação tecnológica avançada.
* **Influência #4: Resident Evil**
    * **Medium:** Jogo
    * **Explicação:** Tensão constante, vulnerabilidade do jogador e uso estratégico de recursos limitados.

---

## Project Description

### The Elevator Pitch
> "Um jogo de terror em primeira pessoa onde você é um contrabandista espacial preso em uma nave à deriva, caçado por um alienígena mortal, com tempo correndo contra você para escapar."

### Brief Description
Em um futuro dominado por megacorporações, um contrabandista espacial transporta uma entidade alienígena proibida. Durante a viagem, a criatura escapa e danifica os sistemas da nave. O piloto deve sobreviver usando furtividade, controle emocional e silêncio para escapar antes que o alien o capture.

### Detailed Description
O jogo segue Zadock, um piloto de contrabando que aceita transportar uma forma de vida alienígena para uma megacorporação. Durante o trajeto, a criatura escapa e compromete os sistemas da nave.

A nave está à deriva no espaço profundo. O jogador deve explorar um ambiente 3D linear com sensação de mapa aberto, localizar a cápsula de fuga e ativar o protocolo de autodestruição.

A experiência é estruturada como uma progressão de tensão sensorial:
* Iluminação dinâmica (azul → falhas → vermelho de emergência)
* Terror sonoro constante
* Reação da IA a sons internos e externos

Não há progressão tradicional, objetivos secundários ou sistema de salvamento. Caso o jogador seja capturado, a experiência reinicia do início.

### What sets this project apart?
* Tensão sensorial constante, baseada em som real e iluminação dinâmica.
* Integração do microfone como mecânica central, tornando o silêncio parte do gameplay.
* Permadeath, aumentando a pressão psicológica.
* Narrativa visual, construída através da ambientação cyberpunk decadente.

---

## Core Gameplay Mechanics (Detailed)

### Mecânica 1: Movimento com Risco
* **Detalhes:** O jogador pode andar, correr ou se agachar. Cada tipo de movimento gera diferentes níveis de ruído.
* **Como funciona:** Quanto maior o ruído gerado, maior o raio de investigação do alien.

### Mecânica 2: Esconder-se
* **Detalhes:** Pontos específicos da nave permitem ocultação temporária.
* **Como funciona:** O jogador reduz a visibilidade e ruído, mas o alien pode eventualmente investigar o local.

### Mecânica 3: Uso do Taser
* **Detalhes:** Ferramenta não letal com bateria limitada.
* **Como funciona:** Ao atingir o alien, ele é paralisado por alguns segundos, permitindo fuga estratégica.

### Mecânica 4: Autodestruição
* **Detalhes:** Sistema ativado em setor específico.
* **Como funciona:** Inicia contagem regressiva real. A iluminação muda para vermelho, alarmes soam e o alien entra em estado agressivo.

### Mecânica 5: Sistema de Microfone
* **Detalhes:** Sons reais do ambiente são captados.
* **Como funciona:** Sons acima de determinado limite aumentam a probabilidade de o alien se aproximar da posição do jogador.

---

## Story and Gameplay

### Story (Brief)
Um contrabandista espacial precisa sobreviver em uma nave em colapso enquanto é caçado por uma entidade alienígena.

### Story (Detailed)
Zadock aceita transportar uma criatura proibida para uma megacorporação. Durante o trajeto, ela escapa e compromete toda a nave.

Sozinho e com sistemas falhando, o protagonista deve atravessar corredores industriais, salas técnicas e setores de energia até encontrar a cápsula de fuga. O ambiente comunica a história por meio de falhas elétricas, alarmes e iluminação instável.

### Gameplay (Brief)
Explorar a nave, manter silêncio, evitar a criatura, ativar autodestruição e escapar antes que o tempo termine.

### Gameplay (Detailed)
O jogador inicia em um ambiente relativamente estável. Conforme avança, falhas elétricas e sons aumentam a tensão. O alien patrulha setores e reage a sons do jogo e do microfone real.

Após ativar a autodestruição, a experiência entra em seu estágio final: iluminação vermelha, alarmes constantes e IA extremamente agressiva. O jogador deve correr até a cápsula de fuga antes que o tempo termine.

---

## Assets Needed

### 2D
* Texturas industriais
* Interfaces holográficas glitchadas
* HUD minimalista
* Ícones de bateria

### 3D
* **Personagens:** Zadock (Protagonista), Alien
* **Ambientes:** Corredores da nave, Sala de controle, Setor de energia, Cápsula de fuga, Áreas de esconderijo

### Sound
* **Ambiente:** Sons de falhas elétricas, Alarmes, Rangidos metálicos, Sons do alien
* **Personagem:** Respiração, Passos, Batimentos cardíacos
* **Taser:** Sons de disparo, Sons de recarga

### Code
* Scripts do jogador (movimentação, input, interação)
* IA do alien (patrulha, investigação, perseguição, frenesi)
* Sistema de detecção por microfone
* Sistema de autodestruição com timer
* Controle de iluminação dinâmica

### Animation
* **Ambientes:** Luzes piscando, Faíscas, Portas automáticas
* **Personagens:** Movimento do alien, Ataque, Reação ao taser, Animações de movimentação do protagonista

---

## Schedule

### Fase 1: Conceito e Protótipo Inicial
* [ ] Design básico do nível
* [ ] Movimento do personagem
* [ ] Protótipo da IA
* [ ] Teste do sistema de microfone

### Fase 2: Desenvolvimento de Recursos e Som
* [ ] Implementação do taser
* [ ] Sistema de esconderijos
* [ ] Iluminação dinâmica
* [ ] Áudio ambiental completo

### Fase 3: Testes e Ajustes Finais
* [ ] Balanceamento de dificuldade
* [ ] Ajuste da sensibilidade do microfone
* [ ] Ajustes de IA
* [ ] Implementação final da autodestruição
* [ ] Polimento visual e sonoro

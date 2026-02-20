
# Game Design Document

### Overview

#### Theme / Setting / Genre

* **Tema**: Horror Sci-Fi com elementos de suspense e sobrevivência.
* **Configuração**: O jogo se passa em uma nave espacial que vaga pelo vazio sideral, após a fuga de uma entidade alienígena. O ambiente da nave é sombrio, claustrofóbico e com sistemas danificados, criando uma atmosfera de tensão constante.
* **Gênero**: Terror em primeira pessoa, com mecânicas de stealth e exploração.

### Core Gameplay Mechanics Brief

## Mecânica 1 – Movimento Baseado em Risco Sonoro: O tipo de movimentação do jogador (andar, correr ou agachar) influencia diretamente o nível de ruído gerado e o raio de detecção do alien.

## Mecânica 2 – Sistema de Furtividade e Esconderijo: O jogador pode utilizar pontos específicos da nave para se esconder temporariamente, reduzindo a chance de detecção.

## Mecânica 3 – Defesa Limitada (Taser): Ferramenta não letal que paralisa o alien por alguns segundos, utilizando bateria limitada.

## Mecânica 4 – Sistema de Autodestruição com Timer: Ativar a autodestruição inicia uma contagem regressiva que aumenta drasticamente a agressividade do alien e a tensão ambiental.

## Mecânica 5 – Detecção de Som via Microfone: Sons captados pelo microfone do jogador podem alertar o alien, integrando o ambiente real ao jogo.

#### Targeted platforms

* PC
  
#### Monetization model (Brief/Document)

* **Monetização**: Modelo Premium – Jogo pago com uma única compra.
* **Link**: Não aplicável (a monetização é baseada na venda direta do jogo).
* Venda de trilha sonora: R$ 15,00
* Custo do jogo: R$ 50,00
* Livro de arte: R$ 15,00
* Expansão: R$ 35,00
* Patrocínios: R$ 1.000 (por empresa/marca)


#### Project Scope

* **Game Time Scale**:

  * **Custo**: R$ 24380,00.
  * **Tempo de Desenvolvimento**: 3-4 meses.
* **Team Size**:

  * **Equipe Principal**:

    * Programador Principal: Responsável pela implementação das mecânicas de jogo, IA e sistema de física.
    * Artista 3D: Criar os modelos dos personagens, nave e ambientes.
    * Animador 3D: Responsável por animações 3D.
  * **Equipe de Marketing**:
    * Community Managers: Criar e manter a presença do jogo nas redes sociais.
* **Licenças / Hardware / Outros Custos**:

  * Licenciamento de software (3ds MAX, Unity6, Blender).
  * Custos de servidores para testagem, se aplicável.
* **Total Costs with breakdown**: R$ 2.000,00.

#### Influences (Brief)

* **Influência #1**: *Alien, o Oitavo Passageiro* (1979)

  * *Medium*: Filme
  * *Explicação*: A atmosfera tensa e claustrofóbica, onde o jogador se sente caçado por uma criatura, é uma grande inspiração para o clima do jogo.
* **Influência #2**: *Bladerunner* (1982)

  * *Medium*: Filme
  * *Explicação*: O mundo futurista e cyberpunk, com um ambiente isolado e apocalíptico, oferece uma base para o design da nave e o cenário em que o jogo se passa.
* **Influência #3**: *Cyberpunk 2077* (2020)

  * *Medium*: Jogo
  * *Explicação*: A inspiração vem na criação de um mundo distópico e de alta tecnologia, mesclando o sci-fi com o terror e a exploração de ambientes.
* **Influência #4**: *Resident Evil* (franquia)

  * *Medium*: Jogo
  * *Explicação*: As mecânicas de tensão constante, exploração e o uso de recursos limitados para defesa são uma forte influência para as mecânicas de jogo de terror.

#### The elevator Pitch

* "Um jogo de terror em primeira pessoa onde você é um contrabandista espacial preso em uma nave à deriva, caçado por um alienígena mortal, com tempo correndo contra você para escapar."

#### Project Description (Brief)

* **Descrição curta**:
  Em um futuro dominado por megacorporações, um contrabandista espacial transporta uma entidade alienígena proibida, mas durante a viagem a criatura escapa e destrói os sistemas da nave. O piloto deve agora sobreviver, usando furtividade e inteligência para escapar da nave antes que o alien ou o próprio espaço o mate.

#### Project Description (Detailed)

* **Descrição detalhada**:
  O jogo segue Zadock, um contrabandista espacial que, após aceitar transportar uma forma de vida alienígena, se vê preso em sua nave quando a criatura escapa. A nave está danificada e a deriva no espaço profundo. O objetivo do jogador é explorar a nave para encontrar uma cápsula de fuga, enquanto é perseguido pela criatura hostil. O jogo combina elementos de stealth com mecânicas de sobrevivência e combate limitado, forçando o jogador a tomar decisões rápidas e a gerenciar recursos escassos, como baterias, enquanto lida com o ambiente hostil e as falhas nos sistemas da nave.

---

### What sets this project apart?

* **Tensão constante** através da mecânica de som e movimento, criando uma experiência de medo crescente.
* **IA adaptativa** do alien, que responde ao comportamento do jogador e se torna mais agressiva ao longo do jogo.
* **Ambiente dinâmico** com a nave se deteriorando, forçando o jogador a agir rapidamente e adicionar urgência.
* **Mecânica de autodestruição**, que aumenta a pressão do tempo e cria momentos decisivos durante a partida.

---

### Core Gameplay Mechanics (Detailed)

#### **Mecânica 1: Movimento com risco**

* **Detalhes**: O jogador pode andar, correr ou se agachar para se mover pela nave. Cada tipo de movimento tem um impacto diferente no nível de detecção do alien. Correr faz barulho, enquanto andar e agachar reduzem o som, mas tornam o movimento mais lento.
* **Como funciona**: Se o jogador correr, o alien tem um raio de detecção maior, mas se andar, o risco é reduzido. Se o jogador se agachar, ele diminui quase completamente a chance de ser detectado, mas também anda muito mais devagar.

#### **Mecânica 2: Esconder-se**

* **Detalhes**: Existem pontos específicos na nave onde o jogador pode se esconder para escapar do alien.
* **Como funciona**: O jogador deve parar de se mover e se esconder para evitar ser encontrado. No entanto, esses pontos não são 100% seguros, e o alien pode eventualmente detectar o esconderijo.

#### **Mecânica 3: Uso do Taser**

* **Detalhes**: O taser é uma ferramenta vital para paralisar temporariamente o alien.
* **Como funciona**: O taser tem uma bateria limitada, que o jogador deve procurar pela nave. Usá-lo no alien o paralisa por alguns segundos, permitindo ao jogador escapar ou atacar.

#### **Mecânica 4: Autodestruição**

* **Detalhes**: Ativar a autodestruição da nave é um dos principais objetivos do jogador.
* **Como funciona**: Quando a autodestruição é ativada, o timer começa a contar e o alien se torna mais agressivo. Isso adiciona uma pressão extra, forçando o jogador a tomar decisões rápidas.

---

### Story and Gameplay

#### Story (Brief)

* **Resumo**: Um contrabandista espacial deve sobreviver em uma nave danificada no vazio do espaço, fugindo de um alien hostil, enquanto tenta escapar antes que o tempo acabe e o espaço o devore.

#### Story (Detailed)

* **Detalhes**: Zadock, um piloto de contrabando, é contratado para transportar uma misteriosa criatura alienígena para uma megacorporação. No entanto, a criatura escapa e destrói a nave. Agora, com sistemas falhando e o alien caçando-o, Zadock deve usar sua astúcia e habilidades de sobrevivência para encontrar a cápsula de fuga, enquanto lida com os falhas dos sistemas da nave e as falhas no fornecimento de recursos. O alien está sempre à espreita, e cada movimento pode ser fatal.

#### Gameplay (Brief)

* **Resumo**: O jogador deve explorar a nave, gerenciar recursos, e usar furtividade para escapar do alien enquanto ativa a autodestruição e tenta chegar à cápsula de fuga.

#### Gameplay (Detailed)

* O jogador começa com recursos limitados e deve explorar a nave para encontrar baterias para o taser e outras ferramentas. O alien patrulha a nave, e a jogabilidade foca em evitar ser detectado. O jogador deve ativar a autodestruição para forçar uma fuga acelerada, mas isso aumenta o risco de ser pego pelo alien.

---

### Assets Needed

#### 2D

* **Texturas**: Texturas para a nave, interfaces e HUDs.
* **Outros**: Ícones para itens (baterias, taser, etc.).

#### 3D

* **Personagens**:

  * Zadock (Protagonista)
  * Alien
* **Ambientes**:

  * Corredores da nave
  * Salas de controle
  * Áreas de esconderijo

#### Sound

* **Ambiente**:

  * Sons de falhas nos sistemas
  * Ruídos da nave
  * Sons do alien se movendo
* **Personagem**:

  * Sons de respiração
  * Sons de movimento (passos)

* **Taser**:
    * Sons de disparo
    * Sons de recarga
#### Code

* **Scripts**:

  * Script do jogador
    
  * IA do alien
      
  * Sistema de autodestruição
    

#### Animation

* **Ambientes**:

  * Luzes piscando
  * Faíscas
  * Portas
* **Personagens**:

  * Animações de movimento de Zadock
  * Animações do Taser
  * Animações de movimento e ataque do alien
  * Animação de equipar item

---

### Schedule

* **Fase 1**: Conceito e protótipo inicial

  * **Milestones**: Design básico do nível, movimento do personagem, e IA do alien.
* **Fase 2**: Desenvolvimento de recursos e som

  * **Milestones**: Implementação do taser, esconderijos, e áudio ambiental.
* **Fase 3**: Testes e ajustes finais

  * **Milestones**: Testar balanceamento de dificuldade, ajustes de IA e implementação de autodestruição.

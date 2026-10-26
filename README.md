<div align="center">

# Living Society

### Personagens com memória. Decisões com consequências.

Projeto de simulação social e autonomia para **RimWorld**.

`C#` · `.NET Framework 4.7.2` · `Harmony` · `XML` · `Persistência de estado`

**Em desenvolvimento · Versão 0.16.223 · Validação em RimWorld 1.6**

</div>

---

## A ideia

Como transformar uma colônia em uma sociedade na qual cada pessoa tenha objetivos próprios?

Living Society conecta memória, conhecimento individual, personalidade, relações, economia e construção às ações reais do jogo. O objetivo é permitir histórias que surjam das decisões dos personagens e das consequências dessas decisões.

Este repositório é a **apresentação pública do projeto**. Não distribui código-fonte, arquivos do jogo ou versões instaláveis do mod.

## Sistemas trabalhados

| Área | Comportamento desenvolvido |
|---|---|
| Memória e relações | Experiências e conversas influenciam decisões e reações futuras. |
| Conhecimento individual | Pesquisa e habilidade da pessoa condicionam o que ela consegue fazer. |
| Construção autônoma | Moradia e infraestrutura usam plantas, materiais e trabalhos reais do jogo. |
| Economia e serviços | Compras, refeições e serviços incluem circulação física de itens e prata. |
| Governo | Liderança, sucessão e obras públicas se conectam às necessidades locais. |
| Expressões e comunicação | Falas contextuais e manifestações visuais tornam as interações mais legíveis. |
| Persistência | Estados, projetos e acordos precisam sobreviver ao salvamento e à recarga. |

Os sistemas têm escopos e limitações. A presença de uma área nesta tabela não significa que todas as situações possíveis estejam implementadas ou certificadas.

## Três formas de jogar

| Modo | Papel do jogador |
|---|---|
| **Diretor** | Administra a colônia e toma as decisões de gestão. |
| **Compartilhado** | Divide decisões com moradores que desenvolvem seus próprios projetos. |
| **RPG / Sociedade viva** | Joga com um personagem, sujeito a conhecimento, propriedade e autoridade locais. |

## Um exemplo: uma reserva de energia que funciona de verdade

Um construtor experiente, com conhecimento e materiais disponíveis, pode planejar um compartimento de pedra, piso não inflamável e teto para uma bateria. O morador precisa construir a proteção, a bateria, os fios e a chave.

Nos cenários controlados, a chave foi operada por um trabalho nativo: o personagem caminhou até ela. A reserva isolada preservou carga durante um curto na rede principal, voltou a alimentar um consumidor durante a falta de geração e reconectou para recarregar após a fonte retornar.

Isso não torna a construção invulnerável a raios, explosões ou qualquer configuração de rede feita pelo jogador.

## Evidências da revisão de 25/10/2026

O fechamento dos dois blocos mais recentes registrou **14 execuções e 159 verificações aprovadas** na versão 0.16.223. São verificações de cenários, não 159 testes unitários independentes nem uma certificação completa do mod.

Em uma campanha existente, foram observados mais **60.000 ticks, equivalentes a um dia**, com salvamento e recarga:

| Medida | Início | Final |
|---|---:|---:|
| Moradores vivos acompanhados | 16 | 16 |
| Casas com piso | 6 | 8 |
| Obras privadas pendentes | 106 | 62 |
| Estabelecimentos registrados ativos | 1 | 2 |

Não foram fornecidos recursos, cura, conhecimento, necessidades preenchidas, trabalhos forçados ou deslocamentos artificiais durante essa observação. Os testes controlados de sistemas são separados desse acompanhamento.

## Limitações conhecidas

- Um save antigo conserva uma fila de 140 cabos e dois geradores públicos; os construtores contratados ainda não tinham o conhecimento individual necessário. Essa rede não foi considerada operacional no resultado da campanha.
- A vila inicial pré-construída está desativada.
- A versão 1.7 não está certificada. A referência de validação é a 1.6.
- A revisão funcional não constitui benchmark de desempenho nem validação de todas as combinações de mods.
- O projeto ainda não foi publicado no Workshop; nenhum link de download é anunciado aqui.

## Meu papel e processo

**Aron — estudante de ADS.** Direção do projeto, definição dos comportamentos e acompanhamento das iterações. Uso IA para somar à criatividade e ao desenvolvimento, com apoio na implementação, revisão e testes. O projeto é também um espaço de aprendizado técnico contínuo.

## Código e distribuição

O código do mod permanece fora deste repositório público. Esta apresentação não concede uma licença de reutilização ou redistribuição do software. Dependências e materiais de terceiros conservam seus próprios direitos e condições. Uma futura distribuição terá seus requisitos e condições informados no canal oficial.

<sub>Projeto da comunidade, sem afiliação ou endosso oficial. Portions of the materials used to create this content/mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This content/mod is not official and is not endorsed by Ludeon.</sub>

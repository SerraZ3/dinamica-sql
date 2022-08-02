# Game BD

## Descrição

Esse é um banco de dados para um jogo. O jogo possui jogadores, personagens, habilidades, fases e níveis.

## Entidades

Jogador
- Nickname (único)
- Senha
- Email
- Data de criação

Personagem  (champion)
- Nome (único)
- Classe (mago, guerreiro, assassino, arqueiro e curandeiro)
- Força
- MP
- Vida
- Recuperação
- Resistência Física
- Resistência Mágica

Habilidades
- Nome (único)
- Descrição
- Nivel mínimo

Fase
- Nome (único)
- Descrição
- Nível mínimo

## Regras de negócios

- Cada jogador possui um ou mais personagens. Deve-se registrar o dia que o personagem foi adquirido pelo jogador
- Cada jogador possui um nível em cada personagem
- Um jogador não pode ter dois personagem iguais
- Cada personagem possui uma ou mais habilidades
- Cada jogador pode estar em uma ou mais fases

## Relatórios

- Quantos jogadores existem na plataforma?
- Qual o personagem que os jogadores mais tem? E o que menos tem?
- Qual fase possui mais jogadores?
- Qual média de nível dos personagens?


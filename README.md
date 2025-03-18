# Jogo da Palavra Secreta

Este projeto é um **jogo da forca** simples, onde o usuário tenta adivinhar uma palavra secreta, letra por letra. O jogo continua até que o usuário adivinhe a palavra corretamente, e o programa conta o número de tentativas feitas.

## Objetivo

O objetivo deste exercício é criar um jogo simples da **forca** em Python, onde o jogador deve tentar adivinhar a palavra secreta, fornecendo uma letra por vez. A palavra secreta é oculta inicialmente, e ao longo do jogo, o jogador vê as letras corretas que foram adivinhadas sendo reveladas.

## Como Funciona

1. O programa define uma **palavra secreta** que o usuário precisa adivinhar. Neste caso, a palavra secreta é `'perfume'`.
2. O jogador insere uma **letra** por vez.
3. Se a letra inserida for parte da palavra secreta, ela é revelada na posição correspondente.
4. O programa continua pedindo letras até que o jogador adivinhe toda a palavra.
5. Ao final, o programa informa o número total de tentativas realizadas para adivinhar a palavra.

### Passos:
- O jogador deve inserir apenas **uma letra** de cada vez.
- Se o jogador digitar mais de uma letra, o programa solicitará que insira apenas uma letra.
- O programa exibe a palavra formada até o momento, mostrando as letras adivinhadas e substituindo as letras não adivinhadas por asteriscos (`*`).
- O jogo termina quando a palavra completa é adivinhada corretamente.

## Exemplo de Execução

### Inicialização:

```
Digite uma letra: p
Palavra formada:  p******
Digite uma letra: e
Palavra formada:  pe****
Digite uma letra: r
Palavra formada:  per***
Digite uma letra: f
Palavra formada:  perf**
Digite uma letra: u
Palavra formada:  perfu*
Digite uma letra: m
Palavra formada:  perfum
Digite uma letra: e
Palavra formada:  perfume
VOCÊ GANHOU! PARABÉNS!
A palavra era perfume
Tentativas: 7
```

### Caso de Erro (letra digitada errada ou mais de uma letra):

```
Digite uma letra: pe
Digite apenas uma letra.
```

## Como Funciona

1. O jogo começa com uma palavra secreta definida pelo programador (no caso, "perfume").
2. O jogador deve digitar uma letra. Se a letra digitada estiver na palavra secreta, ela será revelada na posição correspondente.
3. O programa vai acumulando as letras corretas e mostrando a palavra com letras reveladas e asteriscos no lugar das letras não descobertas.
4. O jogo continua até que o jogador complete a palavra secreta.

## Estrutura do Código

- **Palavra secreta**: Definida pela variável `palavra_secreta`, neste caso, a palavra é `'perfume'`.
- **Letras acertadas**: A variável `letras_acertadas` guarda as letras que o jogador acertou.
- **Contador de tentativas**: A variável `numero_tentativas` conta quantas tentativas o jogador fez até acertar a palavra secreta.
- **Verificação de letra**: O código verifica se a letra digitada está correta e a adiciona à palavra formada.
- **Fim do jogo**: O jogo termina quando o jogador acerta todas as letras da palavra secreta.

## Requisitos

- Python 3.x
- Sistema operacional que suporte o comando `cls` (para limpar a tela no Windows).

## Como Usar

1. Clone ou baixe este repositório.
2. Abra o arquivo Python no seu editor de código favorito.
3. Execute o programa.
4. O programa solicitará que você digite letras até adivinhar a palavra secreta.

## Contribuindo

Se você deseja contribuir para este exercício, pode adicionar novas funcionalidades, como:
- Escolher palavras aleatórias para o jogo.
- Limitar o número de tentativas do jogador.
- Melhorar a interface do usuário (exibindo dicas ou categorias de palavras).

Para contribuir:
1. Fork o repositório.
2. Crie uma nova branch.
3. Faça suas modificações.
4. Abra um **pull request** com suas alterações.

## Licença

Este projeto é de código aberto e pode ser modificado ou compartilhado conforme necessário.

---

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato! 😄

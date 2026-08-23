# Assuntos

Jogos de estudo, um por assunto, organizados por **matéria** e **ano**. Cada jogo é um único
arquivo HTML: sem rede, sem dependências, funciona no celular e no computador.

**▶ Portal:** https://quieterkali.github.io/assuntos/

## Assuntos

| Matéria | Ano | Assunto | Base do conteúdo | Jogar |
|---|---|---|---|---|
| Ciências | 3º | O Corpo Humano | Cap. 9, p. 121–131 (fotos do livro) | [6 missões](https://quieterkali.github.io/assuntos/ciencias/3-ano/corpo-humano/) |
| Matemática | 3º | Fábrica da Tabuada — multiplicação de 0 a 9 | currículo padrão do ano | [6 missões](https://quieterkali.github.io/assuntos/matematica/3-ano/tabuada/) |
| Matemática | 3º | Festa da Divisão — dividir, o resto e os atalhos | currículo padrão do ano | [6 missões](https://quieterkali.github.io/assuntos/matematica/3-ano/divisao/) |
| Matemática | 3º | Contagem Regressiva — revisão para a prova | roteiro da escola + livro | [8 missões](https://quieterkali.github.io/assuntos/matematica/3-ano/revisao-3a-etapa/) |
| História | 6º | Rios do Tempo — Mesopotâmia e Egito | currículo padrão (BNCC EF06HI06–09) | [6 missões](https://quieterkali.github.io/assuntos/historia/6-ano/civilizacoes-antigas/) |
| Língua Portuguesa | 3º | Cidade das Palavras — revisão para a prova | roteiro da escola + 86 fotos das atividades | [8 missões](https://quieterkali.github.io/assuntos/lingua-portuguesa/3-ano/revisao-3a-etapa/) |

> Todos os jogos **perguntam o nome antes de começar** e personalizam tudo com ele — inclusive a
> concordância de gênero escolhida pela criança e o diploma final. E **cada missão começa com uma
> aula curta**, narrada por um guia diferente em cada matéria.

## Estrutura

```
/                                    portal: índice por matéria e ano
/<matéria>/<ano>-ano/<assunto>/
    index.html                       o jogo (6 missões)
    base-de-conhecimento.md          o conteúdo, na linguagem da idade
    revisao-de-precisao.md           a prova de que confere com o livro
```

Como está hoje:

```
/ciencias/3-ano/corpo-humano/
/matematica/3-ano/tabuada/
/matematica/3-ano/divisao/
/matematica/3-ano/revisao-3a-etapa/
/historia/6-ano/civilizacoes-antigas/
```

**O ano é pasta, não etiqueta.** Em fevereiro o 3º ano vira 4º: com o ano na pasta, o material
antigo continua acessível e o novo entra ao lado, sem colidir. O mesmo assunto pode voltar num
ano mais adiantado, com outra profundidade, sem sobrescrever nada.

Assunto novo = pasta nova + um cartão no portal.

## Como cada assunto é construído

Sempre os mesmos quatro passos, nessa ordem — quando há fotos do livro. Sem elas, o passo 1 vira
o **currículo padrão do ano** (BNCC), e o passo 3 fica pendente até as fotos chegarem:

1. **Fotos das páginas** do capítulo → a fonte da verdade.
2. **`base-de-conhecimento.md`** — o capítulo reescrito na linguagem da idade, sem inventar
   nada que não esteja no livro.
3. **`revisao-de-precisao.md`** — a prova de que o conteúdo confere. Separa duas coisas que
   falham de formas diferentes: *fidelidade ao livro* (a base diz o mesmo que a página?) e
   *veracidade do enriquecimento* (os fatos acrescentados são verdadeiros?). O enriquecimento
   é o risco real — uma criança decora um número errado como verdade.
4. **`index.html`** — o jogo. Um arquivo só, sem dependências, sem rede, funciona no celular.

## Princípios de design dos jogos

Estes foram decididos depois de testar e encontrar o problema, não a priori:

- **Estrelas vêm do conhecimento, nunca do reflexo.** Mini-jogos de ação valem pontos; a nota
  sai do quiz. Senão a criança sabe a matéria e tira zero por não ter dedo rápido.
- **As alternativas embaralham a cada partida.** Sem isso a resposta certa concentra numa letra
  só, e ela aprende o padrão em vez do conteúdo.
- **Errar sempre explica o porquê.** O erro é o momento de ensino, não a punição.
- **A colinha fica aberta o tempo todo.** Consultar não é trapaça — e onde há cronômetro, abrir
  a colinha o pausa.
- **Alvos de toque generosos e nunca sobrepostos** — dedo de criança, tela de celular.
- **Refazer só melhora.** As estrelas nunca descem.
- **Quem joga tem nome.** Nada de constante fixa no código: o jogo pergunta e personaliza.
- **A explicação vem antes do erro, não só depois dele.** Cada missão abre com uma aula curta:
  um conceito por slide, uma frase-chave, e o último slide diz o que vai cair. Só aparece na
  estreia da missão, e dá para pular.
- **Habilidade se treina, conteúdo se entende.** Em matéria de treino (tabuada), o jogo **anota o
  que a criança errou** e faz esses fatos voltarem com mais frequência depois. Errar é dado, não
  fracasso.

## Privacidade

As páginas estão marcadas com `noindex, nofollow`, então o site **não aparece em buscadores**
— o link funciona para quem o tem, mas não é descoberto pelo Google. Para reverter, remova a
linha `<meta name="robots" ...>` dos arquivos `index.html`.

## Histórico

Este repositório se chamava `ciencias-maflany` e tinha os assuntos soltos na raiz. Foi renomeado
para `assuntos` ao passar a abrigar mais de uma matéria. O GitHub redireciona os endereços
antigos, mas o oficial agora é o `assuntos`.

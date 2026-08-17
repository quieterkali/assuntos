# Jogos de Estudo

Jogos de estudo feitos por matéria e por capítulo. Um arquivo HTML por assunto: sem rede,
sem dependências, funciona no celular e no computador.

**▶ Portal:** https://quieterkali.github.io/ciencias-maflany/

## Assuntos

| Matéria | Assunto | Base | Jogar |
|---|---|---|---|
| Ciências · 3º ano | O Corpo Humano | Cap. 9, p. 121–131 (fotos do livro) | [6 missões](https://quieterkali.github.io/ciencias-maflany/corpo-humano/) |
| História · 6º ano | Rios do Tempo — Mesopotâmia e Egito | currículo padrão (BNCC EF06HI06–09) | [6 missões](https://quieterkali.github.io/ciencias-maflany/civilizacoes-antigas/) |

> O jogo de História **pergunta o nome antes de começar** e personaliza tudo com ele — incluindo
> a concordância (arqueólogo/arqueóloga) e o diploma final.

## Como cada assunto é construído

Sempre os mesmos quatro passos, nessa ordem — quando há fotos do livro. Sem elas, o passo 1 vira
o **currículo padrão do ano** (BNCC), e o passo 3 fica pendente até as fotos chegarem:

1. **Fotos das páginas** do capítulo → a fonte da verdade.
2. **`base-de-conhecimento.md`** — o capítulo reescrito em linguagem de 9 anos, sem inventar
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
- **A colinha fica aberta o tempo todo.** Consultar não é trapaça.
- **Alvos de toque generosos e nunca sobrepostos** — dedo de criança, tela de celular.
- **Refazer só melhora.** As estrelas nunca descem.

## Privacidade

As páginas estão marcadas com `noindex, nofollow`, então o site **não aparece em buscadores**
— o link funciona para quem o tem, mas não é descoberto pelo Google. Para reverter, remova a
linha `<meta name="robots" ...>` dos arquivos `index.html`.

## Estrutura

```
/                          portal com a lista de assuntos
/corpo-humano/             Ciências · 3º ano
    index.html             o jogo (6 missões)
    base-de-conhecimento.md
    revisao-de-precisao.md
/civilizacoes-antigas/     História · 6º ano
    index.html             o jogo (6 missões)
    base-de-conhecimento.md
```

Cada assunto novo entra como uma pasta nova, e ganha um cartão no portal.

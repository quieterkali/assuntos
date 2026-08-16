# Ciências da Maflany

Jogos de estudo para a Maflany (9 anos), do livro **Aprender Juntos — Ciências, 3º ano**
(SM Educação). Um jogo por capítulo, feito a partir das fotos das páginas do livro dela.

**▶ Portal:** https://quieterkali.github.io/ciencias-maflany/

## Assuntos

| Assunto | Capítulo | Páginas | Jogar |
|---|---|---|---|
| O Corpo Humano | Cap. 9 | 121–127, 130–131 | [6 missões](https://quieterkali.github.io/ciencias-maflany/corpo-humano/) |

## Como cada assunto é construído

Sempre os mesmos quatro passos, nessa ordem:

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
/                        portal com a lista de assuntos
/corpo-humano/
    index.html           o jogo (6 missões)
    base-de-conhecimento.md
    revisao-de-precisao.md
```

Cada assunto novo entra como uma pasta nova, e ganha um cartão no portal.

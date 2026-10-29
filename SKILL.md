---
name: critique-de-fluxo
description: Faz a critique do desenho antes de ele ir para a reunião com produto e engenharia. Devolve as perguntas que o time vai fazer, as decisões que ainda não foram tomadas e os estados que faltam. Use sempre antes de apresentar um fluxo.
---

# Critique de fluxo

Chegar na reunião com a tela bonita e sair com trinta perguntas é o jeito mais caro de descobrir que o desenho não estava pronto.

🔴 **O trabalho desta skill é fazer essas perguntas antes**, quando corrigir ainda custa uma hora em vez de um ciclo.

Ela não melhora o desenho. Ela encontra o que o desenho ainda não decidiu.

---

## A base, com crédito

A prática de design critique é pública e tem literatura própria. A referência direta é **Adam Connor e Aaron Irizarry**, *Discussing Design: Improving Communication and Collaboration Through Critique*, O'Reilly, 2015.

A regra que vem de lá e vale mais que todas: **critique não é feedback sobre gosto, é checagem de se o desenho atende ao objetivo declarado.** Sem objetivo declarado não existe critique, existe opinião.

---

## Como rodar

### 1 · Exigir o objetivo antes de olhar a tela

Três perguntas, e sem as três a critique não começa:

1. **Quem entra neste fluxo, e vindo de onde?**
2. **O que essa pessoa veio resolver?**
3. **Como vamos saber que funcionou?**

🔴 **Se não houver resposta para as três, o problema não é o desenho.** Diga isso e pare. Fazer critique de um fluxo sem objetivo é discutir cor.

### 2 · Percorrer o caminho, não as telas

Tela por tela esconde o que mora entre elas. O percurso é:

| o que olhar | a pergunta |
|:--|:--|
| **a entrada** | a pessoa chega sabendo onde está e por que veio? |
| **cada decisão** | ela tem a informação que precisa para decidir, na hora de decidir? |
| **cada ação** | depois de agir, ela sabe o que aconteceu? |
| **a saída** | ela sabe que terminou, e o que vem depois? |
| **a desistência** | se ela sair no meio, o que acontece com o que já foi feito? |

### 3 · Cobrar os estados que todo mundo esquece

Esta é a parte que mais encontra problema, e é mecânica:

- **vazio** · a primeira vez, sem nenhum dado
- **um item só** · o layout aguenta?
- **muitos itens** · tem paginação, busca, ordenação?
- **carregando** · e se demorar oito segundos?
- **erro de rede** · dá para tentar de novo sem perder o que foi digitado?
- **erro de validação** · a mensagem diz como sair?
- **sem permissão** · a pessoa entende por que não pode?
- **texto longo** · nome de 60 caracteres quebra o cartão?
- **offline** · o que acontece?

🔴 **Estado que não foi desenhado vira decisão de quem implementa.** E aí não é mais design.

### 4 · Nomear o que ainda não foi decidido

A pergunta que mais economiza reunião: **o que neste fluxo ainda é suposição?**

Separar em três:

| | |
|:--|:--|
| **decidido** | está desenhado e tem motivo escrito |
| **suposto** | está desenhado porque pareceu razoável. Precisa de confirmação de alguém |
| **em aberto** | não está desenhado, e o time vai perguntar |

Levar a terceira coluna **escrita** para a reunião muda o tom: deixa de ser avaliação do seu trabalho e vira decisão conjunta.

---

## A saída

```
OBJETIVO DECLARADO
  quem · o que resolve · como se mede

O QUE JÁ ESTÁ DE PÉ
  três a cinco pontos, para a conversa não começar pelo buraco

AS PERGUNTAS QUE O TIME VAI FAZER
  ordenadas por quanto custa descobrir tarde

ESTADOS QUE FALTAM
  lista seca, por tela

AINDA NÃO DECIDIDO
  o que vai à reunião como pergunta, não como falha
```

🔴 **"O que já está de pé" não é gentileza.** Uma critique que só lista problema faz o time discutir defesa em vez de solução.

---

## 🔴 Os limites, que vão escritos na entrega

1. **Isto não substitui a critique com gente.** O time enxerga a restrição técnica, o custo e o histórico que a skill não tem.
2. **Ela não sabe o que já foi decidido fora do arquivo.** Se a escolha veio de uma conversa, ela vai perguntar de novo.
3. **Ela não julga estética.** Hierarquia, ritmo e acabamento são do olho de quem desenha.

---

## O que nunca fazer

- **Não transformar critique em aprovação.** O resultado é uma lista de perguntas, nunca um "pode seguir".
- **Não levar a lista crua para a reunião.** Ela passa pelo meu olho antes, e o que não se sustenta sai.
- **Não confundir com varredura heurística.** Aquela mede o desenho contra princípio conhecido. Esta mede o desenho contra o objetivo declarado. São dois passos diferentes, e esta vem depois.

# critique de fluxo

Faz a critique do desenho antes da reunião, e devolve as perguntas que o time vai fazer.

Uma skill para o [Claude Code](https://claude.com/claude-code). Não é um script: é **critério de trabalho escrito por extenso**, para que a decisão seja a mesma na segunda-feira e na sexta.

## Por que ela existe

Chegar na reunião com a tela bonita e sair com trinta perguntas é o jeito mais caro de descobrir que o desenho não estava pronto.

Esta skill faz essas perguntas antes, quando corrigir custa uma hora em vez de um ciclo. Ela não melhora o desenho: encontra o que o desenho ainda não decidiu.

## O método, com crédito

A referência é **Adam Connor e Aaron Irizarry**, *Discussing Design: Improving Communication and Collaboration Through Critique*, O’Reilly, 2015. A regra que vem de lá: critique não é feedback sobre gosto, é checagem de se o desenho atende ao objetivo declarado.

🔴 **O método é público e tem autor. O que é próprio é a disciplina de rodar sempre, e o critério de corte.**

## O que ela devolve

O objetivo declarado, o que já está de pé, as perguntas que o time vai fazer ordenadas por custo, os estados que faltam, e o que ainda não foi decidido, separado em decidido, suposto e em aberto.

## O que ela NÃO faz

Não substitui a critique com gente: o time enxerga restrição técnica, custo e histórico que a skill não tem. Não sabe o que foi decidido fora do arquivo. E não julga estética, que é do olho de quem desenha.

## O que tem aqui

```
SKILL.md    a skill inteira, que é o que o Claude lê
README.md   este arquivo
LICENSE     MIT
```

## Instalar

```bash
git clone https://github.com/pedromantovanidesign/critique-de-fluxo.git ~/.claude/skills/critique-de-fluxo
```

O Claude Code carrega a skill sozinho quando o assunto aparece, ou com `/critique-de-fluxo`.

---

Escrito e mantido por [Pedro Mantovani](https://pedromantovani.com) · Product & Brand Designer

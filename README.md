# Ocarina of Time — Dublagem em Português (pt-BR)

Re-dublagem completa, feita por fã, de **The Legend of Zelda: Ocarina of Time** em português do Brasil, gerada por IA. São **255 personagens + narrador** e quase **24 mil falas** com voz — da Navi às Pedras de Fofoca.

> **Projeto de fã, sem fins lucrativos. Não tem ligação com a Nintendo nem com os criadores do Longshot.**
> Este repositório contém **apenas a camada de voz em português** (o nosso código) e o guia. **Não** contém o jogo, a ROM, nem qualquer material da Nintendo. Você aplica a dublagem na sua própria cópia do jogo, montada com o Longshot.

## O que é
A dublagem entra junto do mod **Longshot** do OoT e toca as falas já gravadas em português. Não gera voz na hora — nada de IA ou placa de vídeo rodando, só áudio pronto, então funciona em qualquer PC.

## Como instalar (beta)
**Pré-requisito:** já ter o **Longshot** instalado e buildado a partir do seu próprio dump do jogo (fluxo oficial em https://longshot.magicbean.dev, canal Nightly `nightly-345-43f40b87`, idioma Português do Brasil).

1. Baixe as **3 partes** do Release.
2. Extraia **todas na mesma pasta nova** (ex.: "Zelda Dublado") — clique direito → Extrair Tudo em cada ZIP, na mesma pasta.
3. Dê 2 cliques em **`INSTALAR.bat`**; se pedir, arraste o seu `longshot.exe` pra janela.
4. Jogue pelo atalho **"Zelda Dublado"** na área de trabalho. (`DESINSTALAR.bat` volta ao normal.)

É **beta** — pode ter falhas. Nada da Nintendo/Longshot é redistribuído (o módulo do sistema é gerado da sua própria máquina na instalação).

As vozes (~3,3 GB) **não ficam no Git** — são distribuídas como **assets de Release** em 3 partes < 2 GB.

## A comunidade pode melhorar
A dublagem é aberta: trocar a voz de um personagem = gerar o áudio dele de novo com outra voz. A estrutura está pronta pra isso.

## Créditos
- **PC do Fafá** — idealização, direção de vozes e produção da dublagem.
- **Longshot** — a dublagem roda sobre o mod Longshot do OoT (projeto independente; sem ligação com seus criadores).
- **Nintendo** — The Legend of Zelda: Ocarina of Time é da Nintendo. Nada do jogo está incluído aqui.

## Licença
- **Código** (instalador + motor que toca as vozes): **GPL-3.0-or-later** — a mesma licença do Longshot, com o qual ele conversa. Ver `LICENSE`.
- **Pacote de vozes** (os áudios da dublagem): **MIT**, © PC do Fafá. Ver `LICENSE-vozes`.

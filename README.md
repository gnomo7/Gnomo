# Gnomo Vegas — slots, visitantes, resultados e Jogo Secreto 777

Projeto estático para GitHub + Netlify. Não exige comando de build nem servidor próprio para os jogos individuais.

## Publicar no Netlify

1. Baixe e extraia o ZIP.
2. Envie `index.html`, `netlify.toml`, `README.md` e `.nojekyll` para a raiz do repositório no GitHub.
3. No Netlify, importe esse repositório.
4. Deixe **Build command** vazio e configure **Publish directory** como `.`.
5. Publique.

## Contas e chaves predefinidas

Todos os slots aparecem como ocupados. Selecione um slot, informe a chave e toque em **Entrar na conta**.

| Slot | Nick | Chave |
|---:|---|---|
| 01 | Chocco | `chocco777@` |
| 02 | LulaDoPix | `GV-7K2P-91MX` |
| 03 | FlavioBolso | `LB-4Q8N-62TZ` |
| 04 | VorcaroJackpot | `NR-9W3F-28KA` |
| 05 | XandaoDaRoleta | `VS-5D7J-83PL` |
| 06 | NikolasNoPix | `PF-2H6M-49RX` |
| 07 | TarcisioTurbo | `ZR-8B4T-17QN` |
| 08 | AndersonNeiff | `MF-3N9C-56WD` |
| 09 | JanjaNaRoleta | `GM-6P1V-74YS` |
| 10 | TrumpDoTruco | `DK-4X8L-35BJ` |

### Visitante

Na tela de entrada, toque em **Entrar como visitante**. O site gera um nick automático; não é necessária chave. O perfil de visitante fica salvo localmente no navegador.

## Baixar resultado e histórico

1. Entre em uma conta ou como visitante.
2. Abra qualquer jogo e conclua uma jogada/rodada.
3. Na mesa, toque em **Baixar resultado desta rodada** para baixar um arquivo HTML leve e personalizado.
4. Toque em **Baixar histórico da sessão** para baixar todos os resultados registrados na sessão atual (até 200 entradas).
5. O relatório mostra nick, pontuação, saldo fictício, número das rodadas, data/hora e resultados. O arquivo abre sem internet e pode ser impresso ou salvo em PDF pelo navegador.

## Jogo Secreto 777

1. Abra **Jogo Secreto 777**.
2. Digite sua resposta e toque em **Confirmar**.
3. Depois de qualquer resposta enviada, correta ou incorreta, aparece **Baixar resposta do Jogo 777**.
4. O arquivo registra a pergunta, o que o jogador respondeu, se acertou e qual era a resposta correta. Resposta correta concede os pontos de demonstração indicados no jogo.

## Incluído

- Interface responsiva escura, verde-lima e dourada.
- Jogos individuais, 10 slots predefinidos e entrada de visitante.
- Conta Chocco com cosméticos especiais e destaque no ranking local.
- Perfis locais, amigos por link e ranking local.
- Exportação individual de rodada e relatório do histórico da sessão.
- Exportação do registro do Jogo Secreto 777 depois que a pessoa responde.

## Limitações importantes

- Os resultados exportados são registros locais da interface, não certificados independentes.
- Contas, pontuação, fichas e amigos não sincronizam globalmente entre dispositivos; o histórico de jogo fica na sessão do navegador.
- Pontos e créditos são fictícios, sem valor monetário.
- Por ser um site estático, as chaves aparecem no código-fonte publicado. Elas organizam os slots demonstrativos, mas não protegem contas reais como faria uma autenticação de servidor.
- Limpar os dados do navegador pode apagar o progresso local.

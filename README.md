# Gnomo Vegas

Projeto estático para publicar no GitHub e no Netlify. Não precisa de servidor próprio, Render, banco de dados ou comando de build.

## Publicar no Netlify

### Opção A — enviar o projeto diretamente
1. Baixe e extraia `gnomo-vegas-pronto-github-netlify.zip`.
2. No Netlify, crie um site por implantação manual (deploy manual).
3. Arraste a pasta extraída para a área de implantação. Se a interface pedir arquivos, envie o conteúdo da pasta.
4. O arquivo `index.html` precisa ficar na raiz publicada.

### Opção B — GitHub conectado ao Netlify
1. Crie um repositório no GitHub.
2. Envie para a raiz do repositório os arquivos `index.html`, `netlify.toml`, `README.md` e `.nojekyll`.
3. No Netlify, escolha **Add new site / Import an existing project** e conecte o repositório.
4. Configure **Build command** vazio e **Publish directory** como `.`.
5. Publique o site.

## O que está incluído

- Interface responsiva do Gnomo Vegas.
- Jogos individuais executados no navegador.
- Criação de perfis locais com até 10 slots neste navegador.
- Progresso, fichas e itens salvos localmente.
- Perfil especial Chocco com cosméticos exclusivos e destaque no ranking local.
- Compartilhamento de perfil por link e lista local de amigos.
- Ranking montado com perfis locais, perfis compartilhados e perfis de referência.
- Sons sintetizados no navegador, ativados após interação do usuário.

## Limitações importantes

- Não há partidas multiplayer nem sincronização global em tempo real.
- Amigos são adicionados por meio de um retrato do perfil codificado no link. Para atualizar os dados, compartilhe um novo link.
- Perfis, progresso e amigos ficam no armazenamento do navegador (`localStorage`). Limpar os dados do navegador pode apagar essas informações; outro dispositivo começa com dados próprios.
- O link de amizade não contém a senha, mas os dados do perfil incluídos nele são públicos para quem receber o link.
- A senha especial Chocco é verificada no código do navegador; isso serve para o modo demonstrativo/local, não como autenticação segura para dados privados ou competitivos.
- O ranking e os perfis de referência são locais/demonstrativos, não um ranking global verificado.

## Arquivos

- `index.html` — aplicação completa.
- `netlify.toml` — configuração de publicação e cabeçalhos HTTP.
- `.nojekyll` — evita processamento Jekyll se o repositório também for publicado pelo GitHub Pages.
- `README.md` — estas instruções.

# Sound Testing

Página pública para testar, organizar e aprovar sons antes de integrá-los aos jogos.

## Organização das pastas

A página lê automaticamente os arquivos de áudio publicados nestas pastas:

- `sounds/01-efeitos-acoes/` → seção 1
- `sounds/02-ambiente-cenario/` → seção 2
- `sounds/03-interface-feedback/` → seção 3
- `sounds/04-musica-outros/` → seção 4

Os arquivos dentro de cada pasta são ordenados pelo nome. A numeração exibida no painel segue o formato `seção.arquivo`; por exemplo, o terceiro arquivo da pasta 2 aparece como `2.3`.

## Como adicionar uma pasta ou som

1. No GitHub, abra o repositório e entre em **Add file → Create new file**.
2. No campo do nome, digite o caminho completo, por exemplo: `sounds/01-efeitos-acoes/.gitkeep`.
3. Faça o commit. Isso cria a pasta.
4. Entre na pasta criada e use **Add file → Upload files** para enviar os sons.
5. Depois do commit, o GitHub Pages publica a atualização e a página carrega os novos arquivos automaticamente.

Também é possível enviar uma pasta inteira pelo GitHub Desktop ou pelo Git, mantendo esses nomes de diretório.

## Aprovação

A aprovação é marcada no navegador e permanece salva nesse navegador para os arquivos publicados. A numeração ajuda a referenciar os sons nos chats de desenvolvimento.

O botão **Copiar aprovados** gera uma mensagem pronta com as seções, a numeração e os nomes dos sons aprovados, copiando tudo para a área de transferência para você tomar nota.

Arquivos adicionados pelo botão da própria página são apenas temporários: servem para testar antes de publicar e não são enviados automaticamente ao GitHub. Isso evita que a página tenha permissão para alterar o repositório.

## Candidatos adicionais — Bosque e inimigos

- `sounds/01-efeitos-acoes/30`–`32`: Goblins Sound Pack — CC0: https://opengameart.org/content/goblins-sound-pack
- `sounds/01-efeitos-acoes/33`–`38`: 80 CC0 creature SFX — CC0: https://opengameart.org/content/80-cc0-creature-sfx
- `sounds/01-efeitos-acoes/39`–`40`: Monster Sound Pack, Volume 1 — CC0: https://opengameart.org/content/monster-sound-pack-volume-1
- `sounds/04-musica-outros/01`: Forest Ambience — CC0: https://opengameart.org/content/forest-ambience
- `sounds/04-musica-outros/02`: Natural Forest Fantasy Music — CC-BY 4.0: https://opengameart.org/content/natural-forest-fantasy-music

A música `02-bosque-natural-forest-fantasy-ccby.mp3` exige atribuição caso seja aprovada e integrada.

## Candidatos adicionais — especiais e Boss da Floresta

- `41-bravo-estilingue-throw-01.wav`, `44-bravo-estilingue-impact-01.wav`, `45-bravo-estilingue-crackle-01.wav` e `46-bravo-fala-npc-01.wav`: Various Sound Effects — CC0: https://opengameart.org/content/various-sound-effects-0
- `42-rainha-aranha-teia-sproing.wav` e `43-rainha-aranha-teia-splurt.wav`: Various Sound Effects — CC0: https://opengameart.org/content/various-sound-effects-0

São candidatos para testar os sons do estilingue, impacto, fala do Bravo Novato e lançamento de teia. Ainda não foram integrados ao Booga.

## Candidatos para inimigos da Floresta

### Lobos

- `47-lobo-howl-cc0.ogg`
- `48-lobo-barking-01-cc0.ogg`
- `49-lobo-barking-02-cc0.ogg`

Fonte: **80 CC0 creature SFX** — CC0: https://opengameart.org/content/80-cc0-creature-sfx

### Goblins inimigos

- `50-goblin-pack-1-cc0.wav` até `57-goblin-pack-8-cc0.wav`

Fonte: **Goblins Sound Pack** — CC0: https://opengameart.org/content/goblins-sound-pack

Esses arquivos são apenas candidatos para escuta. Ainda não foram integrados ao Booga.

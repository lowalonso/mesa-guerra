🗺 Mesa de Althas — Mapa de Guerra

Mapa de guerra interativo para a campanha Cinco Estandartes em Chamas (Daggerheart), com sincronização em tempo real entre mestre e jogadores.

Tudo em um único arquivo (index.html): mapa, regras, imagens e lógica. Os dados das mesas ficam no Firebase Realtime Database — o site é só a casca, então trocar de hospedagem não apaga nada.

⚔ O que tem
Mapa de Althas com locais (pins) das cinco nações: Altomonte, Armada, Gracien, Polaris e Voldaen
Personagens com ficha, ouro, base, grupos e habilidades — cada jogador controla só o seu
Missões com ordens, prazos em semanas e resolução por d12 de Esperança/Medo
Viagem pessoal e caravana: postura (discreta/normal/acelerada), custo por pessoa, uma rolagem d100 por semana na tabela de eventos da estrada, encontros hostis com ficha por patamar (só o mestre vê)
Baralho (tarot): leituras sobre nações, personagens, a semana, eventos políticos e viagens — com efeitos mecânicos aplicáveis ao mapa
Objetivos por nação e diário de registro (entradas 🔒 visíveis só ao mestre)
Multiplayer em tempo real: quem está online aparece no topo; tudo salva sozinho
🚪 Como entrar

Cada pessoa usa o link com seus parâmetros:

https://SEUUSUARIO.github.io/mesa-althas/?mesa=mesa01&nome=Sollum
Parâmetro	O que faz
mesa=mesa01	Escolhe a sala (mesa01, mesa02…)
nome=Sollum	Identifica o jogador (controla só o próprio personagem)
mestre=1	Modo mestre: vê fichas de inimigos, entradas 🔒, rola eventos e controla todos

Sem parâmetros, o app abre o menu de entrada com as mesas e personagens disponíveis.

🔄 Como atualizar o site
No repositório: Add file → Upload files
Arraste o index.html novo e clique em Commit changes
Aguarde 1–2 minutos e recarregue com Ctrl+Shift+R
Confira o carimbo de versão no console (ex.: MESA DE ALTHAS build: v-083200-fichaSempre)

Deu problema? O histórico de commits permite restaurar qualquer versão anterior.

🛠 Tecnologia
HTML/CSS/JS puro, sem build — abre em qualquer navegador
Firebase Realtime Database (sincronização) — SDK compat v10.12.2
Hospedado no GitHub Pages
🎲 Créditos

Ferramenta de mesa criada para uso pessoal na campanha. Daggerheart é da Darrington Press; as fichas de adversários citadas referem-se ao Livro Básico e não são reproduzidas aqui.

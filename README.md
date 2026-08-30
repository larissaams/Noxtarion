# Noxtarion 

*Integrantes:*

  Anny Elly -- RM:565055

  Larissa -- RM:564168

  Raira -- RM:564850

### Proposta de Valor

O Noxtarion unifica a experiência do RPG de mesa em uma plataforma social integrada. Em vez de alternar entre múltiplos aplicativos para gerenciar fichas, controlar inventário, transferir itens, mapas, conversar e transmitir a partida, entre outros, o Noxtarion oferece um ecossistema centralizado para conectar mestres e jogadores, facilitando a criação de campanhas e o compartilhamento de momentos marcantes. 

 Problema que o App Resolve

Fragmentação de ferramentas: Jogadores precisam usar uma plataforma para ficha, outra para rolagem de dados, outra para voz/vídeo e redes sociais para encontrar mesas. 

Barreira de entrada para iniciantes: Dificuldade em encontrar grupos de RPG e gerenciar fichas complexas sem suporte automatizado. 

Falta de um espaço dedicado: Redes sociais genéricas não são otimizadas para a cultura do RPG de mesa e o compartilhamento de registros de campanhas/diários de aventura. 


### Público-Alvo 

Jogadores de RPG: Pessoas que buscam organizar suas fichas, gerenciar itens de forma intuitiva e encontrar novas mesas para jogar. 

Mestres de RPG: Criadores de conteúdo e narradores que precisam gerenciar múltiplos jogadores, inventários de grupo e organizar sessões. 

Streamers e Criadores de Conteúdo: Jogadores que desejam transmitir suas campanhas ao vivo e construir uma comunidade em torno de suas sessões. 

### Principais Funcionalidades (MVP) 

- Perfil Social & Feed: Criação de perfil para jogadores e mestres, com feed de notícias para postar atualizações de campanhas, artes e histórias. 

- Gerenciamento de Fichas: Criação e edição de fichas dinâmicas compatíveis com múltiplos sistemas de RPG. 

- Inventário Interativo: Sistema visual de gestão de itens, moedas e equipamentos com suporte a drag-and-drop e compartilhamento em tempo real. 

- Transmissão ao Vivo: Espaço integrado para realizar streams das sessões diretamente na plataforma com chat interativo para espectadores, compartilhar mesas, e assistir a outras campanhas. 

- Sistemas próprios: Criar o próprio sistema, fazer descrições, criar imagens e cenários, adicionar tags para fácil identificação. 

- Busca de Mesas: Ferramenta para mestres divulgarem vagas em campanhas e jogadores encontrarem grupos por sistema, horário e estilo de jogo. 


### Estrutura do projeto (inicial)
```
noxtarion
├── lib/
│   ├── main.dart
│   ├── theme/app_theme.dart          # cores, fontes
│   ├── widgets/portal_painter.dart   # o portal (CustomPainter, anéis + partículas)
│   ├── widgets/app_cards.dart
│   └── screens/
│       ├── portal_intro_screen.dart  # abertura com rolagem
│       ├── landing_screen.dart       # marketing (desktop/web)
│       ├── login_screen.dart
│       ├── register_screen.dart
│       └── home_screen.dart
├── pubspec.yaml
└── README.md
```

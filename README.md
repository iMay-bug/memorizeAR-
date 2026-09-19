# Memorize Ará — Conexão Araxá 🧠✨

Jogo da memória interativo desenvolvido especialmente para o evento **Conexão Araxá** (UNIARAXÁ). Uma aplicação web leve, responsiva e 100% autônoma (*single-page application*), projetada para totens, tablets e smartphones.

> *"Conectando instituições. Transformando vida e sociedade!"*

---

## 🌟 Funcionalidades

- **3 Modos de Jogo:**
  - 🎮 **Clássico:** Jogue sem pressa no seu próprio ritmo.
  - ⏱️ **Contra o Tempo:** Desafio com contagem regressiva e penalidade de `-2s` a cada erro!
  - 👥 **2 Jogadores (Duelo Local):** Jogador 1 (Azul) vs Jogador 2 (Verde) disputando turnos no mesmo aparelho. Quem acerta ganha ponto e joga novamente!
- **4 Níveis de Dificuldade:**
  - Fácil (12 cartas — 6 pares)
  - Médio (16 cartas — 8 pares)
  - Difícil (24 cartas — 12 pares)
  - 🔥 Insano (30 cartas — 15 pares)
- **💡 "Você Sabia?":** Curiosidades históricas e culturais de Araxá apresentadas a cada par completado.
- **🏆 Ranking Top 5:** Placar local para registrar os melhores tempos do totem/aparelho.
- **🔍 Poder de Espiada:** Dica rápida de 1 segundo para memorização estratégica (1 uso por partida).
- **🔥 Sistema de Combos:** Efeitos especiais visuais e sonoros para acertos consecutivos.
- **🎵 Áudio Sintetizado Nativo:** Sons de virada, acerto, erro, combo e fanfarra de vitória via Web Audio API (100% offline, sem arquivos externos de áudio).
- **🎟️ QR Code de Brinde & Compartilhamento:** QR Code nativo na vitória para validação de brindes no estande e botão de envio rápido para o WhatsApp.

---

## 🎓 Recursos Especiais para a Apresentação Acadêmica
1. **Modal `🎓 Sobre o Projeto & Equipe`**: Botão direto no HUD explicando a proposta pedagógica, stack técnica (Vanilla JS, Web Audio API, Web Storage) e a equipe.
2. **Avaliação por Estrelas & Precisão**: Exibição da taxa de acerto (`%`), estrelas (`⭐⭐⭐`) e título honorário (*Mestre da Memória Araxaense*) na tela de vitória.
3. **Atalhos do Apresentador (Demonstração Imediata)**:
   - `Shift + D` ou `Shift + W` no teclado dispara a tela de vitória instantânea com confetes e ranking para a banca.
   - Toque triplo na logo do cabeçalho dispara a vitória em telas touch.

---

## ☁️ Cadastro Inicial e Ranking Global Compartilhado em Nuvem (JSON)
1. **Cadastro de Boas-Vindas**: Ao abrir o site pela primeira vez, o jogador digita seu nome ou apelido e já fica conectado.
2. **Badge do Jogador**: Exibido no cabeçalho (`👤 Jogador: [Nome] ✏️`), permitindo alterar o nome a qualquer momento.
3. **Ranking Geral Compartilhado**:
   - Armazenado em nuvem via API REST JSON (`extendsclass.com/api/json-storage/bin/fafffac`), visível para **todos os aparelhos e pessoas que abrirem o link**!
   - Aba **🏅 Melhores Pontuações**: Classificação global por jogadas e tempo.
   - Aba **👥 Cadastrados**: Lista de todas as pessoas que entraram no jogo com data/hora.
   - Botão **📥 Baixar arquivo ranking.json**: Exporta o arquivo JSON real para demonstração aos professores.
   - Modo de resiliência offline: Se estiver sem internet, usa backup em `localStorage`.

---

## 🚀 Como Executar

Por ser uma aplicação estática construída com HTML5, CSS3 e JavaScript puro:
1. Clone o repositório ou baixe os arquivos.
2. Dê um duplo clique no arquivo `index.html` (ou `jogo-memoria-conexao-araxa.html`) para abrir diretamente em qualquer navegador moderno.
3. Não requer instalação de dependências ou servidor web Node/PHP.

---

## 📁 Estrutura de Arquivos

```text
├── index.html                     # Arquivo principal do jogo
├── jogo-memoria-conexao-araxa.html # Cópia original standalone
├── logo-memorize-ara-nova.jpg      # Logotipo oficial master com os 8 eixos
├── logo-conexao-araxa.png         # Tipografia oficial 3D da vitória
├── logo-memorize-ara.jpg          # Imagem de suporte da identidade visual
└── README.md                      # Documentação do projeto
```

---

## 🏛️ Eixos Temáticos de Araxá

1. **Social:** Acolhimento comunitário e projetos de cidadania.
2. **Educação:** O polo acadêmico de excelência do UNIARAXÁ.
3. **Saúde:** Bem-estar termal e cuidado hospitalar.
4. **Segurança:** Qualidade de vida e tranquilidade no Alto Paranaíba.
5. **Esporte:** Capital do mountain bike e Copa do Mundo de ciclismo.
6. **Turismo:** O emblemático Grande Hotel e as termas do Barreiro.
7. **Cidadania:** Participação ativa e construção do futuro de Araxá.
8. **Cultura:** Folclore, artesanato e doces tradicionais de Dona Beja.

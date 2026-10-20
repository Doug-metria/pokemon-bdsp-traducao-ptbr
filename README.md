# 🌟 Tradução PT-BR - Pokémon Brilliant Diamond (PC / Switch)

[![GitHub Release](https://img.shields.io/badge/Release-v1.5.0-blue.svg)](../../releases)
[![Language](https://img.shields.io/badge/Idioma-Português%20(Brasil)-green.svg)](#)
[![Platform](https://img.shields.io/badge/Plataforma-PC%20%7C%20Switch-red.svg)](#)

Patch de tradução, localização e revisão completa para **Português do Brasil (PT-BR)** de *Pokémon Brilliant Diamond*.

---

## 📌 Sumário
- [Destaques da Tradução](#-destaques-da-tradução)
- [Download](#-download)
- [Como Instalar](#-como-instalar)
- [Versão PC Port](#versão-pc-port)
- [Versão Nintendo Switch / Emulador](#versão-nintendo-switch--emulador-ryujinx--yuzu--suyu)
- [Conteúdo Detalhado](#-conteúdo-detalhado)
- [Histórico de Versões (Changelog)](#-histórico-de-versões-changelog)
- [Aviso Legal](#-aviso-legal--disclaimer)

---

## ✨ Destaques da Tradução

* ⚔️ **Interface de Batalha Localizada:** Indicadores de eficácia dos golpes durante o combate (*Super eficaz*, *Pouco eficaz*, *Eficaz*, *Sem efeito*) e mensagens com ordem gramatical natural.
* 📖 **Pokédex Completa:** Todas as 493 entradas da Pokédex traduzidas, incluindo espécies/categorias, e conversão de medidas para o sistema métrico (metros e quilos).
* 💥 **Golpes (826 Moves):** Todos os movimentos de batalha traduzidos com a terminologia oficial consagrada da franquia.
* 🛡️ **Habilidades (268 Abilities):** Descrições e efeitos 100% em português claro, conciso e sem ambiguidades.
* 🎒 **Itens e Mochila (1.823 Itens):** Itens de cura, Poké Bolas, Itens Chave, TMs, itens de batalha e pedras evolutivas com pluralização gramatical correta.
* ⛏️ **Subterrâneo Grandioso (Grand Underground):** Diálogos com mineradores, escavações, pedestais, itens e bases secretas revisados.
* 💬 **Interface e Cenários:** Menus de batalha, caixas de diálogo, opções de sistema e nomes de cidades padronizados (*Cidade de Veilstone*, *Cidade de Pastoria*, *Cidade de Jubilife*, etc.).
* 🔧 **Correções Técnicas de Engine:** Fim definitivo de palavras coladas (*"aprendero"*, *"algunssegundos"*, *"Rosnado!E"*), eliminação de quebras artificiais de tela e preservação das animações originais de Level Up e Evolução.

---

## 📥 Download

Baixe sempre a versão mais recente na aba [**Releases**](../../releases/latest):
* **Arquivo:** `Traducao_Pokemon_Brilliant_Diamond_PC_PTBR.zip`

---

## 🚀 Como Instalar

### Versão PC Port
1. Baixe o arquivo `Traducao_Pokemon_Brilliant_Diamond_PC_PTBR.zip`.
2. Extraia o conteúdo diretamente na pasta principal onde seu jogo está instalado (onde fica o executável `Dpr.exe`).
3. Quando o Windows perguntar, confirme para **Substituir os arquivos no destino**.
4. Inicie o jogo pelo executável padrão ou Launcher e divirta-se!

## ❓ Perguntas Frequentes (FAQ)
#### Essa tradução afeta meu save atual?
> **Não.** A tradução apenas substitui pacotes de recursos de texto (`AssetAssistant\Message`). Seu savegame, seus Pokémon capturados e seu progresso continuam 100% intactos.
#### Funciona no Nintendo Switch ou em emuladores?
> Este pacote foi estruturado e compilado especificamente para a versão **PC Port (Unity x86_64)**. Para emuladores (Ryujinx/Yuzu), a estrutura de mods do RomFS pode requerer o empacotamento compatível com o console.
#### O jogo precisa estar em português na seleção de idiomas?
> Como este mod substitui o canal de idioma principal do port (`english`), você pode deixar o jogo em **Inglês** no menu de opções, e todos os textos carregarão automaticamente em **Português do Brasil**.

---

## 🔍 Conteúdo Detalhado

| Categoria | Status | Descrição |
| :--- | :---: | :--- |
| **História Principal** | ✅ 100% | Diálogos de NPCs, treinadores, Equipe Galáctica e Líderes de Ginásio |
| **Pokédex** | ✅ 100% | Textos, categorias, peso em kg e altura em metros |
| **Movimentos de Batalha** | ✅ 100% | 826 golpes traduzidos com precisão oficial |
| **Habilidades** | ✅ 100% | 268 habilidades e naturezas corrigidas |
| **Itens e Mochila** | ✅ 100% | 1.823 itens, incluindo TMs, itens raros e esferas |
| **Menus e Interface** | ✅ 100% | Telas de batalha, opções, salvar, resumo de Pokémon e eficácia |
| **Grand Underground** | ✅ 100% | Mineração, pedestais, estátuas e diálogos |

---

## 📜 Histórico de Versões (Changelog)

## [v1.6.0] - Atualização Cumulativa de Correções, Diálogos e Localização
### 🛑 Correções de Travamento (Softlocks e Controles)
- **Correção Geral das Placas de Sinnoh (155 placas):**
  - Resolvido o congelamento do jogo e a falta de resposta do controle ao ler placas e marcos geográficos pelo mapa (ex: Vila Floaroma, Vila Twinleaf, Rotas e Cavernas).
  - Restaurada a estrutura técnica original de 2 linhas (`patternID = 7` no título e `patternID = 0, eventID = 7` no subtítulo), garantindo que a seta de diálogo apareça e o controle feche a mensagem normalmente.
---
### 💬 Correções de Quebras de Texto, Linhas e Caixa de Diálogo
- **Fim das Linhas Infinitas Ultrapassando a Tela (Overflow em Linha Única):**
  - Identificada e corrigida a causa raiz pela qual o motor Unity do jogo ignorava quebras de linha (`<BR>`) e novas páginas (`<PAGE>`) em frases com marcadores/tags: todos os eventos de quebra agora recebem rigorosamente `patternID = 7`. Textos longos não mais vazam para fora da tela em uma única linha.
- **Interação e Colheita de Frutas (Berries):**
  - Corrigida a colheita de frutas que antes transbordava a tela sem quebrar a linha: agora estruturada em 2 linhas limpas com avanço suave para a página seguinte ao pressionar o botão A.
  - Eliminado o vazamento de gramática em inglês que exibia *"Tem are 2 Fruta Chestos ! Você gostaria de colher them ?"*. A frase foi reconstruída em português limpo: *"Há {TAG:1} {TAG:2}! Gostaria de colher?"*.
- **Eliminação de Palavras Órfãs (Linhas com 1 palavra só):**
  - Varredura geral e redistribuição de quebras de linha em diálogos de NPCs e eventos de história para impedir que palavras soltas fiquem isoladas na linha inferior quando havia espaço suficiente na linha anterior.
- **Ajuste de Escala no Mapa-Múndi (Town Map):**
  - Redução das fontes dos nomes de cidades e descrições no Mapa-múndi (escalas ajustadas para 30 e 27) e quebras de texto refeitas, eliminando o texto que ultrapassava as bordas e barras do mapa.
- **Preservação de Telas de Animação e Batalha:**
  - Preservação integral dos tokens internos nas telas de subida de nível (*Level Up*), evolução (*Shinka Demo*) e lembrador de movimentos (*Move Relearner*).
---
### 🌐 Localização e Eliminação de Textos Restantes em Inglês
- **Mochila e Bolsos (Bag Pockets):**
  - Termos `[ Berries ]` e `Bolso de Berries` localizados oficialmente para **`Frutas`** e **`Bolso de Frutas`**.
  - Padronização de todos os bolsos: `Medicina`, `Pokébolas`, `Itens de Batalha`, `Frutas`, `Outros Itens`, `TMs`, `Tesouros` e `Itens-chave`.
  - Revisão e tradução de todas as descrições de frutas (*Berry* -> *Fruta*).
- **Sala União e Sala Global (Local & Global Union Rooms):**
  - Tradução integral de todas as 45 linhas das recepcionistas, confirmações de entrada/saída, cópia de Decoração de Cápsulas de Pokébolas e mistura de registros.
- **Comunicação Y-Comm e Batalhas em Rede:**
  - Tradução completa dos menus e notificações de conexão online, Códigos de Elo, busca de parceiros de troca, modo avião e lista de bloqueio de jogadores.
  - Tradução das telas de regras de batalhas online, seleção de equipes e checagem de itens repetidos.
- **Eletrodomésticos do Catálogo Rotom:**
  - Tradução de todas as mensagens de interação com os aparelhos no Edifício da Equipe Galáctica (forno micro-ondas, geladeira, máquina de lavar, ventilador e cortador de grama).
- **Movimentos, Itens Especiais e Marcos:**
  - Golpe *After You* localizado para a nomenclatura oficial **Depois de Você**.
  - Golpe *Light That Burns the Sky* localizado para **Luz que Queima o Céu**.
  - Notificação do item de som ajustada para: *"Você obteve os Sons do DS!"*.
  - Placa da Cidade de Veilstone traduzida: *"Cidade de Veilstone - Esculpida na Rocha"*.
  - Tradução das telas de entrada de texto virtual (teclado), avisos de salvamento e mensagens de erro de rede.
  - 
### v1.5.0
- **Eficácia de Golpes em Batalha:** Traduzidos os indicadores na seleção de golpes (*Super eficaz*, *Pouco eficaz*, *Eficaz*, *Sem efeito*).
- **Correção Profunda de Tokenização:** Fim definitivo de palavras coladas (*"aprendero"*, *"algunssegundos"*, *"Rosnado!E"*, *"Multiplicar.Um"*).
- **Remoção de Cortes de Página Artificiais:** Eliminadas mais de 800 quebras de tela desnecessárias que isolavam palavras (como o erro *"aqui no"*).
- **Preservação de Eventos da Engine:** Sincronia e pausas temporizadas originais restabelecidas no Level Up e Evolução (*"Um... dois... e... ta-da!"*).
- **Padronização Geográfica e Classes:** 218 termos padronizados nos diálogos (*Cidades*, *Rotas*, *Líderes*, *Treinador Ás*, *Piqueniqueira*, *Magnata da Torre*).

### v1.4.0
- **Ajuste Vertical na Mochila:** Limite estrito de 4 linhas nas descrições de itens para impedir corte visual.
- **Pluralização Automática:** Correção gramatical em itens, esferas e estátuas do Subterrâneo (*"Esferas Vermelhas"*, *"Poções"*).
- **Controle de Largura:** Mensagens limitadas a 44 caracteres por linha para evitar terceira linha fora da caixa.

### v1.3.0
- **Golpes Oficiais:** Tradução dos 826 movimentos para o padrão brasileiro (*Lança-chamas*, *Choque do Trovão*, *Raio de Gelo*).
- **Mensagens de Combate:** Padronização gramatical em batalhas (*"{Treinador} usou {Golpe}!"*).

### v1.2.0
- **Naturezas e Personalidades:** Correção de naturezas traduzidas ao pé da letra (*Firme*, *Precipitado*, *Forte*, *Calmo*).
- **Ajustes de Cenário:** Revisão dos diálogos de Twinleaf, Sandgem e primeiros ginásios.

### v1.1.0
- **Correção de Espaçamento em Batalha:** Corrigidas palavras coladas em caixas de diálogo contínuas (*"vai enviar"*, *"desafiado por"*, *"enviou"*).
- **Reestruturação de Troca de Pokémon:** Ajuste da mensagem `BTL_STRID_STD_IrekaeConfirm`.

### v1.0.0
- Lançamento inicial com tradução completa da Pokédex, menus, golpes, itens, habilidades e diálogos.

---

## ⚖️ Aviso Legal / Disclaimer

Este projeto é uma modificação feita por fãs, sem fins lucrativos, para a comunidade brasileira. Todos os direitos de *Pokémon*, *Pokémon Brilliant Diamond*, personagens, logotipos e marcas registradas pertencem à **Nintendo**, **Creatures Inc.** e **Game Freak / The Pokémon Company**.

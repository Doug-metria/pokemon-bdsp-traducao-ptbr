# 🌟 Tradução PT-BR - Pokémon Brilliant Diamond (PC / Switch)

[![GitHub Release](https://img.shields.io/badge/Release-v1.3-blue.svg)](../../releases)
[![Language](https://img.shields.io/badge/Idioma-Português%20(Brasil)-green.svg)](#)
[![Platform](https://img.shields.io/badge/Plataforma-PC%20%7C%20Switch-red.svg)](#)

Patch de tradução, localização e revisão completa para **Português do Brasil (PT-BR)** de *Pokémon Brilliant Diamond*.

---

## 📌 Sumário
- [Destaques da Tradução](#-destaques-da-tradução)
- [Download](#-download)
- [Como Instalar](#-como-instalar)
- [Versão PC](#versão-pc)
- [Versão Nintendo Switch / Emulador](#versão-nintendo-switch--emulador-ryujinx--yuzu--suyu)
- [Conteúdo Detalhado](#-conteúdo-detalhado)
- [Histórico de Versões (Changelog)](#-histórico-de-versões-changelog)
- [Aviso Legal](#-aviso-legal--disclaimer)

---

## ✨ Destaques da Tradução

* 📖 **Pokédex Completa:** Todas as entradas traduzidas, com espécies/categorias, proporção de gênero e conversão métrica (metros e quilos).
* ⚔️ **Golpes (826 Moves):** Movimentos de batalha traduzidos com a terminologia oficial brasileira.
* 🛡️ **Habilidades (268 Abilities):** Descrições e efeitos 100% em português claro e conciso.
* 🎒 **Itens (1.823 Itens):** Itens de cura, Poké Bolas, Itens Chave, TMs, itens de batalha e pedras evolutivas traduzidos.
* ⛏️ **Grand Underground:** Diálogos com mineradores, escavações, pedestais, itens e bases secretas revisados.
* 💬 **Interface e Diálogos:** Menus de batalha, caixas de diálogo, opções de sistema e nomes de locais revisados.
* 🔧 **Correções Técnicas v1.3:** Conversão global de comandos de scroll legados (`<EV4>`) para páginas naturais (`<PAGE>`), reestruturação das caixas de itens da Mochila sem cortes e 100% dos textos traduzidos (sem linhas em inglês).

---

## 📥 Download

Baixe sempre a versão mais recente na aba [**Releases**](../../releases/latest):
* **Arquivo:** `Traducao_Pokemon_Brilliant_Diamond_PC_PTBR.zip`

---

## 🚀 Como Instalar

### Versão PC
1. Baixe e extraia o arquivo `.zip` da tradução.
2. Copie a pasta **`Dpr_Data`** que está dentro do pacote.
3. Cole na pasta principal onde o seu jogo está instalado (por exemplo: `...\Pokemon Brilliant Diamond - PC Version\`).
4. Quando o Windows perguntar, confirme para **Substituir os arquivos no destino**.
5. Abra o jogo normalmente e divirta-se!

### Versão Nintendo Switch / Emulador (Ryujinx / Yuzu / Suyu)
1. Extraia os arquivos do pacote.
2. No seu emulador, clique com o botão direito sobre o jogo e selecione **Open Mod Directory** (ou *Abrir Diretório de Mods*).
3. Crie uma pasta com o nome `Traducao_PTBR`.
4. Dentro dela, coloque a estrutura `romfs/Data/StreamingAssets/AssetAssistant/Message/` com os arquivos substituídos (`english` e `common_msbt`).
5. Inicie o jogo.

---

## 🔍 Conteúdo Detalhado

| Categoria | Status | Descrição |
| :--- | :---: | :--- |
| **História Principal** | ✅ 100% | Diálogos de NPCs, treinadores e líderes de ginásio |
| **Pokédex** | ✅ 100% | Textos, categorias, peso em kg e altura em metros |
| **Movimentos de Batalha** | ✅ 100% | 826 golpes traduzidos com precisão |
| **Habilidades** | ✅ 100% | 268 habilidades |
| **Itens e Mochila** | ✅ 100% | 1.823 itens, incluindo TMs e itens raros |
| **Menus e Interface** | ✅ 100% | Telas de batalha, opções, salvar e resumo de Pokémon |
| **Grand Underground** | ✅ 100% | Mineração, pedestais e diálogos |

---

## 📜 Histórico de Versões (Changelog)

### v1.3.0
- **Ajuste Global das Caixas de Itens na Mochila:** Reestruturação de 1.502 descrições de itens para eliminar o vazamento/transbordamento de texto fora da moldura (ex: Poké Bola e itens com mais de 3 linhas). Agora 100% dos 1.823 itens cabem perfeitamente dentro da caixa com até 3 linhas e quebras naturais.
- **Revisão Geral de Gramática e Concordância:** Varredura em todos os 34.041 textos do jogo para eliminação de erros mecânicos de tradução e concordância verbal/nominal.
- **Tradução 100% da Sala Secreta do Rotom:** Diário de Plutínio (10 capítulos), diálogos com o Professor e interação com todos os eletrodomésticos (micro-ondas, geladeira, ventilador, lavadora e cortador de grama) totalmente traduzidos.
- **Tradução de Textos de Rede e Sistema:** Menus de comunicação local e online, verificações do Salão de Concurso, telas de entrada de texto e descrições de bagas redutoras de EV.
- **Zero Linhas em Inglês Remanescentes:** Cobertura de 100% dos arquivos do jogo em Português do Brasil.
- **Remoção Global de Scroll Bugado (`<EV4>`):** Substituição de comandos legados do Nintendo DS que deixavam palavras isoladas no topo da caixa de texto por quebras de página limpas e suaves.
- **Ajuste de Quebras Antecipadas:** Removidas quebras de linha manuais forçadas herdadas de telas pequenas, garantindo leitura contínua e espaçamento perfeito.
- **Correção da TV e Cenas de Abertura:** Linha do programa de TV corrigida para exibir até o final sem truncar na borda direita.

### v1.2.0
- **Correção da Mãe / Diálogos:** Preservação de `patternID = 7` para que quebras de página (`<PAGE>`) funcionem com o botão (A) sem travar ou pular texto.
- **Correção de Coleta de Itens:** Removido o "the" em inglês e corrigida a frase duplicada "da damochila".
- **Espaçamento Universal:** Prevenção de palavras grudadas antes e depois de quebras de linha (ex: "vaienviar", "enviouStarly").

### v1.1.0
- Ajustes de mensagens de batalha e combate.

### v1.0.0
- Lançamento inicial com tradução completa da Pokédex, menus, golpes, itens, habilidades e diálogos.

---

## ⚖️ Aviso Legal / Disclaimer

Este projeto é uma modificação feita por fãs, sem fins lucrativos, para a comunidade brasileira. Todos os direitos de *Pokémon*, *Pokémon Brilliant Diamond*, personagens, logotipos e marcas registradas pertencem à **Nintendo**, **Creatures Inc.** e **Game Freak / The Pokémon Company**.

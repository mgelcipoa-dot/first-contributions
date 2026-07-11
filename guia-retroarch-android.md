<title>Guia RetroArch no Android — Nintendo e Sega</title>

# 🎮 RetroArch no Android — Guia Completo (Nintendo + Sega)

Este guia deixa o seu RetroArch **organizado e pronto para jogar**: cada console com seu emulador certo, seus jogos em listas separadas com capas, e tudo abrindo com 2 toques. Siga na ordem — leva uns 20 a 30 minutos na primeira vez.

> **Consoles cobertos:** NES (Nintendinho), Super Nintendo, Game Boy / Game Boy Color, Game Boy Advance, Nintendo 64, Mega Drive, Master System, Game Gear, Saturn e Dreamcast.

---

## Passo 1 — Instale a versão certa do RetroArch

A versão da **Play Store** funciona, mas é limitada (demora a atualizar e às vezes não mostra todos os emuladores). A versão recomendada é a do site oficial:

1. No navegador do celular, acesse **retroarch.com/index.php?page=platforms**
2. Toque em **Android** e baixe o **RetroArch AArch64** (é a versão para celulares modernos, de 64 bits).
3. Abra o arquivo baixado e instale. Se o Android reclamar, autorize **"Instalar apps desconhecidos"** para o navegador.

Se você já tem a versão da Play Store e ela está funcionando, pode continuar com ela — o guia serve para as duas.

**Primeira abertura:** o RetroArch vai pedir **permissão de armazenamento**. Aceite — sem isso ele não enxerga seus jogos.

> 💡 **Deixe o menu em português:** `Settings → User → Language → Português (Brasil)`. O guia usa os nomes em português a partir daqui.

---

## Passo 2 — Organize suas ROMs em pastas

Essa é a parte mais importante para o RetroArch ficar organizado. Usando o app **Arquivos** (ou qualquer gerenciador de arquivos), crie esta estrutura na memória do celular:

```
Armazenamento interno/
└── ROMs/
    ├── NES/
    ├── SNES/
    ├── GameBoy/
    ├── GBA/
    ├── Nintendo64/
    ├── MegaDrive/
    ├── MasterSystem/
    ├── GameGear/
    ├── Saturn/
    └── Dreamcast/
```

Depois mova cada jogo para a pasta do console dele. Regras que evitam dor de cabeça:

- **Não misture consoles na mesma pasta.**
- Jogos podem ficar **em .zip** sem problema (NES, SNES, GB, GBA, Mega Drive, Master System, Game Gear).
- Jogos de **Saturn e Dreamcast** costumam vir em `.chd`, `.cue+.bin` ou `.gdi` — se for `.cue+.bin`, os dois arquivos precisam ficar juntos na pasta. O formato **.chd é o melhor** (menor e um arquivo só).

> ⚖️ **Nota legal:** use cópias (dumps) dos jogos que você possui. Não posso indicar sites de download de ROMs.

---

## Passo 3 — Baixe os emuladores certos (cores)

No RetroArch, cada console precisa de um **core** (o emulador em si). Baixe assim:

**Menu Principal → Carregar Core → Baixar um Core**

Na lista, baixe estes (toque em cada um e ele instala sozinho):

| Console | Core recomendado |
|---|---|
| NES | **Nestopia UE** |
| Super Nintendo | **Snes9x (versão atual)** |
| Game Boy / GB Color | **Gambatte** |
| Game Boy Advance | **mGBA** |
| Nintendo 64 | **Mupen64Plus-Next** |
| Mega Drive / Master System / Game Gear | **Genesis Plus GX** (um core só serve os três!) |
| Saturn | **YabaSanshiro** (leve) ou **Beetle Saturn** (mais fiel, exige celular forte + BIOS) |
| Dreamcast | **Flycast** |

> 💡 Na lista de download os nomes aparecem com o console antes, por exemplo: *"Nintendo - SNES / SFC (Snes9x - Current)"*.

### Ainda no Atualizador On-line, atualize os dados

Volte ao **Menu Principal → Atualizador On-line** e toque, um por um:

1. **Atualizar Perfis de Controle**
2. **Atualizar Bancos de Dados** *(essencial — é o que reconhece seus jogos no escaneamento)*
3. **Atualizar Recursos (Assets)**
4. **Atualizar Arquivos de Informação de Core**

---

## Passo 4 — Crie as playlists (escanear os jogos)

Agora vem a mágica da organização:

1. Vá em **Importar Conteúdo** (ícone de ➕ no menu).
2. Toque em **Escanear Diretório**.
3. Navegue até a pasta **ROMs** que você criou e toque em **\<Escanear Este Diretório\>**.
4. Aguarde — ele varre todas as subpastas de uma vez.

Quando terminar, vão aparecer no menu principal **ícones separados por console**: Nintendo - NES, Nintendo - SNES, Sega - Mega Drive, etc. Cada um é uma playlist com seus jogos em ordem alfabética. 🎉

> ⚠️ **Algum jogo não apareceu?** O escaneamento só aceita ROMs "conhecidas" pelo banco de dados. Para adicionar na marra: **Importar Conteúdo → Escanear Manualmente**, escolha a pasta e, em *Sistema*, selecione o console correspondente.

---

## Passo 5 — Baixe as capas dos jogos

Para as listas ficarem bonitas, com a capinha de cada jogo:

1. **Menu Principal → Atualizador On-line → Atualizador de Miniaturas de Playlists**
2. Toque em cada playlist (uma por vez) e aguarde o download.

Depois, dentro da playlist, as capas aparecem ao lado de cada jogo.

---

## Passo 6 — Associe o core certo a cada playlist

Para o jogo abrir direto com 1 toque, sem perguntar qual emulador usar:

1. Abra uma playlist (ex.: **Nintendo - SNES**).
2. Toque em qualquer jogo → **Definir Associação de Core** → escolha o core da tabela do Passo 3 (ex.: Snes9x).
3. Repita para cada playlist.

Pronto: agora é **playlist → jogo → Executar** e ele já abre jogando.

---

## Passo 7 — Controles

### Na tela de toque
Os botões virtuais (overlay) já vêm ativados. Se quiser ajustar o tamanho/transparência: `Configurações → Controle na Tela → Sobreposição na Tela`.

### Controle Bluetooth (recomendado!)
1. Pareie o controle no Bluetooth do Android normalmente.
2. Abra o RetroArch — ele reconhece sozinho e mostra *"Controle conectado na porta 0"*.
3. Se algum botão sair errado: `Configurações → Controles → Controles da Porta 1 → Definir Todos os Controles` e aperte os botões na ordem pedida.

> 💡 Para esconder os botões da tela quando o controle físico conectar: `Configurações → Controle na Tela → Sobreposição na Tela → Ocultar Sobreposição Quando um Controle for Conectado` → **Ativado**.

### Atalho essencial
O botão **Home/RetroArch** do overlay (ou `Select + Start` no controle, se configurar o *Combo de Botões do Controle para Alternar Menu*) abre o **menu rápido** durante o jogo — é lá que ficam salvar, carregar e fechar.

---

## Passo 8 — BIOS (só para Saturn e Dreamcast)

Os consoles de cartucho **não precisam de nada** — já funcionam. Os de CD podem precisar de arquivos de BIOS (que você extrai do seu próprio console):

| Console | Arquivo | Onde colocar |
|---|---|---|
| Saturn (Beetle) | `sega_101.bin` e `mpr-17933.bin` | pasta **RetroArch/system/** |
| Dreamcast | `dc_boot.bin` (opcional — Flycast roda a maioria dos jogos sem) | **RetroArch/system/dc/** |

Para achar a pasta *system*: `Configurações → Diretórios → BIOS` mostra o caminho exato no seu aparelho.

---

## Dicas de ouro 🏆

- **Salvar a qualquer momento (Save State):** durante o jogo, abra o menu rápido → **Salvar Estado de Jogo**. Para voltar: **Carregar Estado de Jogo**. Funciona até em jogo que não tinha save!
- **Avanço rápido:** menu rápido → segure o botão de *fast forward* para pular partes lentas (ótimo em RPGs).
- **Rebobinar (rewind):** errou o pulo? `Configurações → Estrutura de Execução → Rebobinar` → Ativado. Custa um pouco de desempenho, evite no N64/Dreamcast.
- **Tela esticada?** `Configurações → Vídeo → Escala → Proporção de Tela → Core Provido` mantém a proporção original.
- **Visual de tubo (scanlines):** menu rápido → **Shaders** → carregue um preset da pasta `crt` (experimente o *crt-easymode*).
- **N64 travando?** No menu rápido → **Opções do Core**, reduza a resolução para 320x240 e ative *Threaded Rendering*.

---

## Problemas comuns

| Sintoma | Solução |
|---|---|
| RetroArch não vê minhas pastas | Dê a permissão de arquivos em *Configurações do Android → Apps → RetroArch → Permissões* |
| Escaneou e não achou nada | Rode **Atualizar Bancos de Dados** (Passo 3) e escaneie de novo; ou use *Escanear Manualmente* |
| Jogo abre com tela preta | Core errado associado — refaça o Passo 6; em Saturn, confira a BIOS |
| Capas não baixam | Rode **Atualizar Recursos (Assets)** e tente o Passo 5 de novo |
| Som picotando | `Configurações → Áudio → Latência de Áudio` → aumente para 128 ms |

---

*Guia gerado em 11/07/2026 para RetroArch no Android — bom jogo! 🕹️*

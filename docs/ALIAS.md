# SetupVibe Aliases

Esta é a lista exaustiva de todos os aliases configurados pelo SetupVibe em todas as plataformas.

**Legenda de Disponibilidade:**
- 🖥️ **Desktop**: Disponível na edição Desktop (macOS e Linux Desktop).
- ☁️ **Server**: Disponível na edição Server (Linux).
- 🌐 **Ambos**: Disponível em todas as edições.

---

## AI CLIs

- **`ge`** (🌐 Ambos)
  - Comando: `gemini --approval-mode=yolo`
  - Descrição: Gemini CLI sem confirmações.

- **`cc`** (🌐 Ambos)
  - Comando: `claude --permission-mode=auto --dangerously-skip-permissions`
  - Descrição: Claude CLI sem confirmações.

## Skills CLI

- **`skl`** (🌐 Ambos)
  - Comando: `npx skills list`
  - Descrição: Lista todas as skills instaladas.

- **`skf`** (🌐 Ambos)
  - Comando: `npx skills find`
  - Descrição: Busca skills no registro (ex: `skf react`).

- **`ska`** (🌐 Ambos)
  - Comando: `npx skills add`
  - Descrição: Instala uma nova skill (ex: `ska owner/repo`).

- **`sku`** (🌐 Ambos)
  - Comando: `npx skills update`
  - Descrição: Atualiza todas as skills instaladas.

- **`skun`** (🌐 Ambos)
  - Comando: `npx skills remove`
  - Descrição: Remove uma skill instalada (ex: `skun nome`).

- **`skc`** (🌐 Ambos)
  - Comando: `npx skills check`
  - Descrição: Verifica atualizações disponíveis.

## Shell & Utilitários

- **`zconfig`** (🌐 Ambos)
  - Comando: `nano ~/.zshrc`
  - Descrição: Edita o arquivo de configuração do ZSH.

- **`reload`** (🌐 Ambos)
  - Comando: `source ~/.zshrc`
  - Descrição: Recarrega as configurações do ZSH sem reiniciar o terminal.

- **`path`** (🌐 Ambos)
  - Comando: `echo -e ${PATH//:/\\n}`
  - Descrição: Exibe cada entrada do PATH em uma linha separada.

- **`h`** (🌐 Ambos)
  - Comando: `history | grep`
  - Descrição: Busca no histórico de comandos.

- **`cls`** (🖥️ Desktop)
  - Comando: `clear`
  - Descrição: Limpa o terminal.

- **`please`** (🌐 Ambos)
  - Comando: `sudo`
  - Descrição: Atalho amigável para sudo.

- **`week`** (🌐 Ambos)
  - Comando: `date +%V`
  - Descrição: Exibe o número da semana atual.

## Navegação & Filesystem

- **`..`**, **`...`**, **`....`** (🌐 Ambos)
  - Comando: `cd ..`, `cd ../..`, `cd ../../..`
  - Descrição: Sobe um, dois ou três níveis de diretório.

- **`ll`** (🌐 Ambos)
  - Comando: `ls -lhA` (macOS) / `ls -lhA --color=auto` (Linux)
  - Descrição: Lista arquivos com detalhes e tamanho legível.

- **`la`** (🌐 Ambos)
  - Comando: `ls -A` (macOS) / `ls -A --color=auto` (Linux)
  - Descrição: Lista todos os arquivos incluindo ocultos.

- **`lsd`** (🌐 Ambos)
  - Comando: `ls -d */ 2>/dev/null`
  - Descrição: Lista apenas diretórios.

- **`md`** (🌐 Ambos)
  - Comando: `mkdir -p`
  - Descrição: Cria diretório e subdiretórios automaticamente.

- **`rmf`** (🌐 Ambos)
  - Comando: `rm -rf`
  - Descrição: Remove arquivos e diretórios recursivamente sem confirmação.

- **`du1`** (🌐 Ambos)
  - Comando: `du -h -d 1` (macOS) / `du -h --max-depth=1` (Linux)
  - Descrição: Uso de disco do diretório atual, um nível de profundidade.

## Tmux

- **`t`** (🌐 Ambos)
  - Comando: `tmux`
  - Descrição: Atalho para o tmux.

- **`tn`** (🌐 Ambos)
  - Comando: `tmux new -s`
  - Descrição: Cria nova sessão tmux.

- **`ta`** (🌐 Ambos)
  - Comando: `tmux attach -t`
  - Descrição: Reconecta a uma sessão existente.

- **`tl`** (🌐 Ambos)
  - Comando: `tmux ls`
  - Descrição: Lista todas as sessões tmux ativas.

- **`tk`** (🌐 Ambos)
  - Comando: `tmux kill-session -t`
  - Descrição: Encerra uma sessão tmux.

- **`tka`** (🌐 Ambos)
  - Comando: `tmux kill-server`
  - Descrição: Encerra todas as sessões tmux.

- **`td`** (🌐 Ambos)
  - Comando: `tmux detach`
  - Descrição: Desconecta da sessão sem encerrá-la.

- **`tw`** (🌐 Ambos)
  - Comando: `tmux new-window`
  - Descrição: Cria nova janela na sessão atual.

- **`ts`** (🌐 Ambos)
  - Comando: `tmux split-window -v`
  - Descrição: Divide painel horizontalmente.

- **`tsh`** (🌐 Ambos)
  - Comando: `tmux split-window -h`
  - Descrição: Divide painel verticalmente.

- **`trename`** (🌐 Ambos)
  - Comando: `tmux rename-session`
  - Descrição: Renomeia a sessão atual.

- **`twrename`** (🌐 Ambos)
  - Comando: `tmux rename-window`
  - Descrição: Renomeia a janela atual.

- **`treload`** (🌐 Ambos)
  - Comando: `tmux source ~/.tmux.conf`
  - Descrição: Recarrega as configurações do tmux.

- **`tconfig`** (🌐 Ambos)
  - Comando: `nano ~/.tmux.conf`
  - Descrição: Edita o arquivo de configuração do tmux.

## Git

- **`gs`**, **`ga`**, **`gaa`**, **`gc`**, **`gcm`**, **`gco`**, **`gcb`**, **`gp`**, **`gpl`**, **`gf`**, **`gfa`**, **`gm`**, **`grb`**, **`gcp`**, **`gl`**, **`glamelog`**, **`gd`**, **`gds`**, **`gb`**, **`gba`**, **`gbd`**, **`gtag`**, **`gclone`**, **`gst`**, **`gstp`**, **`grh`**, **`gundo`**, **`gwip`** (🌐 Ambos)
  - Descrição: Atalhos exaustivos para operações comuns do Git.

## GitHub CLI

- **`ghpr`**, **`ghprl`**, **`ghprv`**, **`ghprc`**, **`ghprs`**, **`ghrl`**, **`ghrc`**, **`ghiss`**, **`ghissn`**, **`ghrun`**, **`ghrunw`**, **`ghwf`**, **`ghwfr`**, **`ghrel`**, **`ghrelc`**, **`ghgist`**, **`ghssh`** (🌐 Ambos)
  - Descrição: Atalhos para interagir com o GitHub diretamente do terminal.

## SSH

- **`ssha`**, **`sshal`**, **`sshkeys`**, **`sshconfig`**, **`keygen`** (🌐 Ambos)
  - Descrição: Atalhos para gerenciamento de chaves e conexões SSH.

## Docker

- **`d`**, **`dc`**, **`dps`**, **`dpsa`**, **`dimg`**, **`dlog`**, **`dex`**, **`dstart`**, **`dstop`**, **`drm`**, **`drmi`**, **`dpull`**, **`dbuild`**, **`dstats`**, **`dins`**, **`dip`**, **`dnet`**, **`dvol`**, **`dprune`**, **`dcup`**, **`dcdown`**, **`dcstop`**, **`dcrestart`**, **`dcps`**, **`dclog`**, **`dclogs`**, **`dcbuild`**, **`dcpull`**, **`dcexec`** (🌐 Ambos)
  - Descrição: Conjunto completo de atalhos para Docker e Docker Compose.

## Gerenciadores de Pacotes

- **`update`** (🌐 Ambos)
  - Comando: `brew update && brew upgrade` / `apt update...`
  - Descrição: Atualiza o sistema e gerenciadores de pacotes.

- **`apti`**, **`aptr`**, **`apts`**, **`aptshow`**, **`aptls`** (☁️ Server / 🖥️ Desktop Linux)
  - Descrição: Atalhos para o gerenciador de pacotes APT.

- **`brewup`**, **`brewls`**, **`brewinfo`**, **`brewsearch`** (🖥️ Desktop / ☁️ Server se instalado)
  - Descrição: Atalhos para o Homebrew.

## Linguagens & Frameworks (🖥️ Desktop)

- **Laravel/PHP**: `art`, `artm`, `artmf`, `artmfs`, `arts`, `artq`, `artc`, `artt`, `artmake`, `artr`, `arttink`, `artkey`, `artopt`, `artschedule`, `artdb`, `artmodel`, `artjob`, `artevent`, `ci`, `cu`, `creq`, `creqd`, `cdump`, `crun`.
- **Node/JS**: `ni`, `nid`, `nr`, `nrd`, `nrb`, `nrt`, `nx`, `bi`, `br`, `brd`, `brb`, `bx`, `pn`, `pni`, `pnr`, `pnd`, `pnb`, `pnt`, `pnx`, `pnadd`, `pnaddd`.
- **Python**: `py`, `pyv`, `uvi`, `uvs`, `venv`, `activate`.
- **Ruby**: `rbv`, `rblocal`, `rbglobal`, `be`, `binstall`, `bupdate`.
- **Rust**: `cb`, `cbr`, `crun2`, `ct`, `ccheck`, `clippy`, `cfmt`, `cadd`, `crem`, `cupdate`, `cdoc`.
- **Go**: `gobuild`, `gorun`, `gotest`, `gomod`, `govet`, `gofmt`, `goget`, `goclean`, `gocover`, `gowork`.

## DevOps & Sistema

- **Ansible** (🌐 Ambos): `anp`, `ani`, `anping`, `anv`, `anve`, `anvd`, `anvr`, `ancheck`, `andiff`, `anfacts`.
- **Monitoramento**: `topc`, `topm` (macOS), `psg`, `df`, `meminfo` (Linux), `diskinfo` (Linux), `cpuinfo` (Linux), `sysinfo` (Linux).
- **Systemd (Linux)**: `sstatus`, `sstart`, `sstop`, `srestart`, `senable`, `sdisable`, `slogs`, `syslog`.

## Rede & Web

- **Rede**: `myip`, `localip`, `ports`, `wholistening` (Linux), `flush`.
- **cURL/HTTP**: `get`, `post`, `headers`, `httpcode`, `timing`.
- **JSON**: `jpp`, `jsonf`.
- **Segurança**: `certinfo`, `certexpiry`, `sslcheck`, `genpass`.
- **Ambiente**: `envls`, `envg`, `dotenv`.

---
> Follow the formatting guide: [Markdown Format Guide](.claude/commands/markdown-format.md)

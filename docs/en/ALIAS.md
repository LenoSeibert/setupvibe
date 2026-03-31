# SetupVibe Aliases

This is the exhaustive list of all aliases configured by SetupVibe on all platforms.

**Availability Legend:**
- 🖥️ **Desktop**: Available in the Desktop edition (macOS and Linux Desktop).
- ☁️ **Server**: Available in the Server edition (Linux).
- 🌐 **Both**: Available in all editions.

---

## AI CLIs

- **`ge`**
  - Availability: 🌐 Both
  - Command: `gemini --approval-mode=yolo`
  - Description: Gemini CLI without confirmations.
  - Example: `ge`

- **`cc`**
  - Availability: 🌐 Both
  - Command: `claude --permission-mode=auto --dangerously-skip-permissions`
  - Description: Claude CLI without confirmations.
  - Example: `cc`

## Skills CLI

- **`skl`**
  - Availability: 🌐 Both
  - Command: `npx skills list`
  - Description: Lists all installed skills.
  - Example: `skl`

- **`skf`**
  - Availability: 🌐 Both
  - Command: `npx skills find`
  - Description: Search for skills in the registry.
  - Example: `skf react`

- **`ska`**
  - Availability: 🌐 Both
  - Command: `npx skills add`
  - Description: Installs a new skill.
  - Example: `ska owner/repo`

- **`sku`**
  - Availability: 🌐 Both
  - Command: `npx skills update`
  - Description: Updates all installed skills.
  - Example: `sku`

- **`skun`**
  - Availability: 🌐 Both
  - Command: `npx skills remove`
  - Description: Removes an installed skill.
  - Example: `skun name`

- **`skc`**
  - Availability: 🌐 Both
  - Command: `npx skills check`
  - Description: Checks for available updates.
  - Example: `skc`

## Shell & Utilities

- **`zconfig`**
  - Availability: 🌐 Both
  - Command: `nano ~/.zshrc`
  - Description: Edits the ZSH configuration file.
  - Example: `zconfig`

- **`reload`**
  - Availability: 🌐 Both
  - Command: `source ~/.zshrc`
  - Description: Reloads ZSH settings without restarting the terminal.
  - Example: `reload`

- **`path`**
  - Availability: 🌐 Both
  - Command: `echo -e ${PATH//:/\\n}`
  - Description: Displays each PATH entry on a separate line.
  - Example: `path`

- **`h`**
  - Availability: 🌐 Both
  - Command: `history | grep`
  - Description: Search through command history.
  - Example: `h docker`

- **`cls`**
  - Availability: 🌐 Both
  - Command: `clear`
  - Description: Clears the terminal.
  - Example: `cls`

- **`please`**
  - Availability: 🌐 Both
  - Command: `sudo`
  - Description: Friendly shortcut for sudo.
  - Example: `please apt update`

- **`week`**
  - Availability: 🌐 Both
  - Command: `date +%V`
  - Description: Displays the current week number.
  - Example: `week`

## Navigation & Filesystem

- **`..`**
  - Availability: 🌐 Both
  - Command: `cd ..`
  - Description: Goes up one directory level.
  - Example: `..`

- **`...`**
  - Availability: 🌐 Both
  - Command: `cd ../..`
  - Description: Goes up two directory levels.
  - Example: `...`

- **`....`**
  - Availability: 🌐 Both
  - Command: `cd ../../..`
  - Description: Goes up three directory levels.
  - Example: `....`

- **`ll`**
  - Availability: 🌐 Both
  - Command: `ls -lhA` (macOS) / `ls -lhA --color=auto` (Linux)
  - Description: Lists files with details and human-readable size.
  - Example: `ll`

- **`la`**
  - Availability: 🌐 Both
  - Command: `ls -A` (macOS) / `ls -A --color=auto` (Linux)
  - Description: Lists all files including hidden ones.
  - Example: `la`

- **`lsd`**
  - Availability: 🌐 Both
  - Command: `ls -d */ 2>/dev/null`
  - Description: Lists directories only.
  - Example: `lsd`

- **`md`**
  - Availability: 🌐 Both
  - Command: `mkdir -p`
  - Description: Creates directory and subdirectories automatically.
  - Example: `md project/src/css`

- **`rmf`**
  - Availability: 🌐 Both
  - Command: `rm -rf`
  - Description: Removes files and directories recursively without confirmation.
  - Example: `rmf old_folder`

- **`du1`**
  - Availability: 🌐 Both
  - Command: `du -h -d 1` (macOS) / `du -h --max-depth=1` (Linux)
  - Description: Disk usage of the current directory, one level deep.
  - Example: `du1`

## Tmux

- **`t`**
  - Availability: 🌐 Both
  - Command: `tmux`
  - Description: Shortcut for tmux.
  - Example: `t`

- **`tn`**
  - Availability: 🌐 Both
  - Command: `tmux new -s`
  - Description: Creates a new tmux session.
  - Example: `tn my-project`

- **`ta`**
  - Availability: 🌐 Both
  - Command: `tmux attach -t`
  - Description: Reconnects to an existing session.
  - Example: `ta my-project`

- **`tl`**
  - Availability: 🌐 Both
  - Command: `tmux ls`
  - Description: Lists all active tmux sessions.
  - Example: `tl`

- **`tk`**
  - Availability: 🌐 Both
  - Command: `tmux kill-session -t`
  - Description: Ends a tmux session.
  - Example: `tk my-project`

- **`tka`**
  - Availability: 🌐 Both
  - Command: `tmux kill-server`
  - Description: Ends all tmux sessions.
  - Example: `tka`

- **`td`**
  - Availability: 🌐 Both
  - Command: `tmux detach`
  - Description: Disconnects from the session without ending it.
  - Example: `td`

- **`tw`**
  - Availability: 🌐 Both
  - Command: `tmux new-window`
  - Description: Creates a new window in the current session.
  - Example: `tw`

- **`ts`**
  - Availability: 🌐 Both
  - Command: `tmux split-window -v`
  - Description: Splits the pane horizontally (new pane below).
  - Example: `ts`

- **`tsh`**
  - Availability: 🌐 Both
  - Command: `tmux split-window -h`
  - Description: Splits the pane vertically (new pane on the right).
  - Example: `tsh`

- **`trename`**
  - Availability: 🌐 Both
  - Command: `tmux rename-session`
  - Description: Renames the current session.
  - Example: `trename new-name`

- **`twrename`**
  - Availability: 🌐 Both
  - Command: `tmux rename-window`
  - Description: Renames the current window.
  - Example: `twrename editor`

- **`treload`**
  - Availability: 🌐 Both
  - Command: `tmux source ~/.tmux.conf`
  - Description: Reloads tmux settings.
  - Example: `treload`

- **`tconfig`**
  - Availability: 🌐 Both
  - Command: `nano ~/.tmux.conf`
  - Description: Edits the tmux configuration file.
  - Example: `tconfig`

## Git

- **`gs`**
  - Availability: 🌐 Both
  - Command: `git status`
  - Description: Displays the current repository state.
  - Example: `gs`

- **`ga`**
  - Availability: 🌐 Both
  - Command: `git add`
  - Description: Adds files to the staging area.
  - Example: `ga file.txt`

- **`gaa`**
  - Availability: 🌐 Both
  - Command: `git add .`
  - Description: Adds all modified files to the staging area.
  - Example: `gaa`

- **`gc`**
  - Availability: 🌐 Both
  - Command: `git commit`
  - Description: Opens the editor to write the commit message.
  - Example: `gc`

- **`gcm`**
  - Availability: 🌐 Both
  - Command: `git commit -m`
  - Description: Commit with inline message.
  - Example: `gcm 'fix: typo'`

- **`gco`**
  - Availability: 🌐 Both
  - Command: `git checkout`
  - Description: Switches branches or restores files.
  - Example: `gco main`

- **`gcb`**
  - Availability: 🌐 Both
  - Command: `git checkout -b`
  - Description: Creates and switches to a new branch.
  - Example: `gcb feature/new-function`

- **`gp`**
  - Availability: 🌐 Both
  - Command: `git push`
  - Description: Sends commits to the remote repository.
  - Example: `gp`

- **`gpl`**
  - Availability: 🌐 Both
  - Command: `git pull`
  - Description: Downloads and integrates changes from the remote repository.
  - Example: `gpl`

- **`gf`**
  - Availability: 🌐 Both
  - Command: `git fetch`
  - Description: Fetches updates from remote without applying them.
  - Example: `gf`

- **`gfa`**
  - Availability: 🌐 Both
  - Command: `git fetch --all --prune`
  - Description: Fetches from all remotes and removes deleted branches.
  - Example: `gfa`

- **`gm`**
  - Availability: 🌐 Both
  - Command: `git merge`
  - Description: Merges a branch.
  - Example: `gm feature/x`

- **`grb`**
  - Availability: 🌐 Both
  - Command: `git rebase`
  - Description: Reapplies commits on top of another base.
  - Example: `grb main`

- **`gcp`**
  - Availability: 🌐 Both
  - Command: `git cherry-pick`
  - Description: Applies a specific commit to the current branch.
  - Example: `gcp abc123`

- **`gl`**
  - Availability: 🌐 Both
  - Command: `git log --oneline --graph --decorate`
  - Description: Compact log with branch graph.
  - Example: `gl`

- **`glamelog`**
  - Availability: 🌐 Both
  - Command: `git log --pretty=format:"%h %ad %s" --date=short`
  - Description: Compact log with dates.
  - Example: `glamelog`

- **`gd`**
  - Availability: 🌐 Both
  - Command: `git diff`
  - Description: Displays unstaged differences.
  - Example: `gd`

- **`gds`**
  - Availability: 🌐 Both
  - Command: `git diff --staged`
  - Description: Displays staged differences.
  - Example: `gds`

- **`gb`**
  - Availability: 🌐 Both
  - Command: `git branch`
  - Description: Lists local branches.
  - Example: `gb`

- **`gba`**
  - Availability: 🌐 Both
  - Command: `git branch -a`
  - Description: Lists all branches including remote ones.
  - Example: `gba`

- **`gbd`**
  - Availability: 🌐 Both
  - Command: `git branch -d`
  - Description: Removes a local branch.
  - Example: `gbd feature/x`

- **`gtag`**
  - Availability: 🌐 Both
  - Command: `git tag`
  - Description: Creates or lists tags.
  - Example: `gtag v1.0.0`

- **`gclone`**
  - Availability: 🌐 Both
  - Command: `git clone`
  - Description: Clones a repository.
  - Example: `gclone https://github.com/user/repo.git`

- **`gst`**
  - Availability: 🌐 Both
  - Command: `git stash`
  - Description: Temporarily saves changes in a stash.
  - Example: `gst`

- **`gstp`**
  - Availability: 🌐 Both
  - Command: `git stash pop`
  - Description: Restores the last stashed changes.
  - Example: `gstp`

- **`grh`**
  - Availability: 🌐 Both
  - Command: `git reset HEAD~1`
  - Description: Undoes the last commit while keeping changes.
  - Example: `grh`

- **`gundo`**
  - Availability: 🌐 Both
  - Command: `git restore .`
  - Description: Discards all unstaged changes.
  - Example: `gundo`

- **`gwip`**
  - Availability: 🌐 Both
  - Command: `git add -A && git commit -m "WIP"`
  - Description: Quickly saves work in progress.
  - Example: `gwip`

## GitHub CLI

- **`ghpr`**
  - Availability: 🌐 Both
  - Command: `gh pr create`
  - Description: Opens a wizard to create a Pull Request.
  - Example: `ghpr`

- **`ghprl`**
  - Availability: 🌐 Both
  - Command: `gh pr list`
  - Description: Lists open Pull Requests.
  - Example: `ghprl`

- **`ghprv`**
  - Availability: 🌐 Both
  - Command: `gh pr view`
  - Description: Displays current PR details.
  - Example: `ghprv`

- **`ghprc`**
  - Availability: 🌐 Both
  - Command: `gh pr checkout`
  - Description: Checks out a PR by number.
  - Example: `ghprc 42`

- **`ghprs`**
  - Availability: 🌐 Both
  - Command: `gh pr status`
  - Description: Status of PRs related to the current branch.
  - Example: `ghprs`

- **`ghrl`**
  - Availability: 🌐 Both
  - Command: `gh repo list`
  - Description: Lists repositories of the authenticated user.
  - Example: `ghrl`

- **`ghrc`**
  - Availability: 🌐 Both
  - Command: `gh repo clone`
  - Description: Clones a repository.
  - Example: `ghrc owner/repo`

- **`ghiss`**
  - Availability: 🌐 Both
  - Command: `gh issue list`
  - Description: Lists open issues for the repository.
  - Example: `ghiss`

- **`ghissn`**
  - Availability: 🌐 Both
  - Command: `gh issue create`
  - Description: Opens a wizard to create a new issue.
  - Example: `ghissn`

- **`ghrun`**
  - Availability: 🌐 Both
  - Command: `gh run list`
  - Description: Lists GitHub Actions workflow runs.
  - Example: `ghrun`

- **`ghrunw`**
  - Availability: 🌐 Both
  - Command: `gh run watch`
  - Description: Watches a workflow run in real-time.
  - Example: `ghrunw`

- **`ghwf`**
  - Availability: 🌐 Both
  - Command: `gh workflow list`
  - Description: Lists GitHub Actions workflows.
  - Example: `ghwf`

- **`ghwfr`**
  - Availability: 🌐 Both
  - Command: `gh workflow run`
  - Description: Manually triggers a workflow.
  - Example: `ghwfr deploy.yml`

- **`ghrel`**
  - Availability: 🌐 Both
  - Command: `gh release list`
  - Description: Lists repository releases.
  - Example: `ghrel`

- **`ghrelc`**
  - Availability: 🌐 Both
  - Command: `gh release create`
  - Description: Creates a new release.
  - Example: `ghrelc v1.0.0`

- **`ghgist`**
  - Availability: 🖥️ Desktop
  - Command: `gh gist create`
  - Description: Creates a Gist from a file.
  - Example: `ghgist file.sh`

- **`ghssh`**
  - Availability: 🖥️ Desktop
  - Command: `gh ssh-key list`
  - Description: Lists SSH keys registered in the GitHub account.
  - Example: `ghssh`

## SSH

- **`ssha`**
  - Availability: 🌐 Both
  - Command: `ssh-add`
  - Description: Adds an SSH key to the agent.
  - Example: `ssha ~/.ssh/id_ed25519`

- **`sshal`**
  - Availability: 🌐 Both
  - Command: `ssh-add -l`
  - Description: Lists keys loaded in the SSH agent.
  - Example: `sshal`

- **`sshkeys`**
  - Availability: 🌐 Both
  - Command: `ls -la ~/.ssh/`
  - Description: Lists all SSH key files.
  - Example: `sshkeys`

- **`sshconfig`**
  - Availability: 🌐 Both
  - Command: `nano ~/.ssh/config`
  - Description: Edits the SSH configuration file.
  - Example: `sshconfig`

- **`keygen`**
  - Availability: 🌐 Both
  - Command: `ssh-keygen -t ed25519 -C`
  - Description: Generates a new Ed25519 SSH key.
  - Example: `keygen 'email@x.com'`

## Docker

- **`d`**
  - Availability: 🌐 Both
  - Command: `docker`
  - Description: Shortcut for the docker command.
  - Example: `d ps`

- **`dc`**
  - Availability: 🌐 Both
  - Command: `docker compose`
  - Description: Shortcut for docker compose.
  - Example: `dc up -d`

- **`dps`**
  - Availability: 🌐 Both
  - Command: `docker ps`
  - Description: Lists running containers.
  - Example: `dps`

- **`dpsa`**
  - Availability: 🌐 Both
  - Command: `docker ps -a`
  - Description: Lists all containers including stopped ones.
  - Example: `dpsa`

- **`dimg`**
  - Availability: 🌐 Both
  - Command: `docker images`
  - Description: Lists locally available Docker images.
  - Example: `dimg`

- **`dlog`**
  - Availability: 🌐 Both
  - Command: `docker logs -f`
  - Description: Follows a container's logs.
  - Example: `dlog my-container`

- **`dex`**
  - Availability: 🌐 Both
  - Command: `docker exec -it`
  - Description: Executes an interactive command in a container.
  - Example: `dex app bash`

- **`dstart`**
  - Availability: 🌐 Both
  - Command: `docker start`
  - Description: Starts a stopped container.
  - Example: `dstart my-container`

- **`dstop`**
  - Availability: 🌐 Both
  - Command: `docker stop`
  - Description: Stops a running container.
  - Example: `dstop my-container`

- **`drm`**
  - Availability: 🌐 Both
  - Command: `docker rm`
  - Description: Removes a container.
  - Example: `drm my-container`

- **`drmi`**
  - Availability: 🌐 Both
  - Command: `docker rmi`
  - Description: Removes an image.
  - Example: `drmi my-image`

- **`dpull`**
  - Availability: 🌐 Both
  - Command: `docker pull`
  - Description: Downloads an image from a registry.
  - Example: `dpull nginx:alpine`

- **`dbuild`**
  - Availability: 🌐 Both
  - Command: `docker build -t`
  - Description: Builds an image with a tag.
  - Example: `dbuild app:latest .`

- **`dstats`**
  - Availability: 🌐 Both
  - Command: `docker stats`
  - Description: Monitors container CPU/memory usage in real-time.
  - Example: `dstats`

- **`dins`**
  - Availability: 🌐 Both
  - Command: `docker inspect`
  - Description: Inspects container or image details.
  - Example: `dins app`

- **`dip`**
  - Availability: 🌐 Both
  - Command: `docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}'`
  - Description: Gets a container's IP.
  - Example: `dip app`

- **`dnet`**
  - Availability: 🌐 Both
  - Command: `docker network ls`
  - Description: Lists available Docker networks.
  - Example: `dnet`

- **`dvol`**
  - Availability: 🌐 Both
  - Command: `docker volume ls`
  - Description: Lists created Docker volumes.
  - Example: `dvol`

- **`dprune`**
  - Availability: 🌐 Both
  - Command: `docker system prune -af --volumes`
  - Description: Removes all unused Docker resources.
  - Example: `dprune`

- **`dcup`**
  - Availability: 🌐 Both
  - Command: `docker compose up -d`
  - Description: Starts services in the background.
  - Example: `dcup`

- **`dcdown`**
  - Availability: 🌐 Both
  - Command: `docker compose down`
  - Description: Stops and removes compose containers.
  - Example: `dcdown`

- **`dcstop`**
  - Availability: 🌐 Both
  - Command: `docker compose stop`
  - Description: Stops services without removing containers.
  - Example: `dcstop`

- **`dcrestart`**
  - Availability: 🌐 Both
  - Command: `docker compose restart`
  - Description: Restarts all compose services.
  - Example: `dcrestart`

- **`dcps`**
  - Availability: 🌐 Both
  - Command: `docker compose ps`
  - Description: Lists compose services and their states.
  - Example: `dcps`

- **`dclog`**
  - Availability: 🌐 Both
  - Command: `docker compose logs -f`
  - Description: Follows logs from all compose services.
  - Example: `dclog`

- **`dclogs`**
  - Availability: 🌐 Both
  - Command: `docker compose logs --tail=100`
  - Description: Displays the last 100 lines of compose logs.
  - Example: `dclogs`

- **`dcbuild`**
  - Availability: 🌐 Both
  - Command: `docker compose build --no-cache`
  - Description: Rebuilds images without cache.
  - Example: `dcbuild`

- **`dcpull`**
  - Availability: 🌐 Both
  - Command: `docker compose pull`
  - Description: Updates compose service images.
  - Example: `dcpull`

- **`dcexec`**
  - Availability: 🌐 Both
  - Command: `docker compose exec`
  - Description: Executes a command in a service.
  - Example: `dcexec app bash`

## Package Managers

- **`update`**
  - Availability: 🌐 Both
  - Command: `brew update && brew upgrade` (macOS) / `sudo apt update...` (Linux)
  - Description: Updates the system and package managers.
  - Example: `update`

- **`apti`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo apt install`
  - Description: Installs a package via APT.
  - Example: `apti htop`

- **`aptr`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo apt remove`
  - Description: Removes a package via APT.
  - Example: `aptr htop`

- **`apts`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `apt search`
  - Description: Searches APT repositories for packages.
  - Example: `apts nginx`

- **`aptshow`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `apt show`
  - Description: Displays APT package details.
  - Example: `aptshow git`

- **`aptls`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `dpkg -l | grep`
  - Description: Filters installed packages.
  - Example: `aptls nginx`

- **`brewup`**
  - Availability: 🖥️ Desktop / ☁️ Server if installed
  - Command: `brew update && brew upgrade && brew cleanup`
  - Description: Updates Homebrew and removes old versions.
  - Example: `brewup`

- **`brewls`**
  - Availability: 🖥️ Desktop / ☁️ Server if installed
  - Command: `brew list`
  - Description: Lists all packages installed via Homebrew.
  - Example: `brewls`

- **`brewinfo`**
  - Availability: 🖥️ Desktop / ☁️ Server if installed
  - Command: `brew info`
  - Description: Displays information about a package.
  - Example: `brewinfo git`

- **`brewsearch`**
  - Availability: 🖥️ Desktop / ☁️ Server if installed
  - Command: `brew search`
  - Description: Searches Homebrew for packages.
  - Example: `brewsearch ripgrep`

## Languages & Frameworks (🖥️ Desktop)

### Laravel / PHP
- **`art`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan`
  - Description: Shortcut for PHP Artisan.
  - Example: `art list`

- **`artm`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan migrate`
  - Description: Runs pending migrations.
  - Example: `artm`

- **`artmf`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan migrate:fresh`
  - Description: Recreates all tables from scratch.
  - Example: `artmf`

- **`artmfs`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan migrate:fresh --seed`
  - Description: Recreates tables and populates with seeders.
  - Example: `artmfs`

- **`arts`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan serve`
  - Description: Starts the Laravel development server.
  - Example: `arts`

- **`artq`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan queue:work`
  - Description: Starts the queue worker.
  - Example: `artq`

- **`artc`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan cache:clear && php artisan config:clear && php artisan route:clear && php artisan view:clear`
  - Description: Clears all Laravel caches.
  - Example: `artc`

- **`artt`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan test`
  - Description: Runs the Laravel test suite.
  - Example: `artt`

- **`artmake`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan make`
  - Description: Shortcut for code generation.
  - Example: `artmake:controller UserController`

- **`artr`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan route:list`
  - Description: Lists all application routes.
  - Example: `artr`

- **`arttink`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan tinker`
  - Description: Opens the interactive Laravel REPL.
  - Example: `arttink`

- **`artkey`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan key:generate`
  - Description: Generates a new application key.
  - Example: `artkey`

- **`artopt`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan optimize:clear`
  - Description: Clears all caches and optimizations.
  - Example: `artopt`

- **`artschedule`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan schedule:work`
  - Description: Starts the scheduled tasks worker.
  - Example: `artschedule`

- **`artdb`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan db`
  - Description: Opens an interactive database connection.
  - Example: `artdb`

- **`artmodel`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan make:model`
  - Description: Creates a Model.
  - Example: `artmodel Post -m`

- **`artjob`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan make:job`
  - Description: Creates a Job for queues.
  - Example: `artjob ProcessPayment`

- **`artevent`**
  - Availability: 🖥️ Desktop
  - Command: `php artisan event:list`
  - Description: Lists all registered events and listeners.
  - Example: `artevent`

- **`ci`**
  - Availability: 🖥️ Desktop
  - Command: `composer install`
  - Description: Installs composer.json dependencies.
  - Example: `ci`

- **`cu`**
  - Availability: 🖥️ Desktop
  - Command: `composer update`
  - Description: Updates dependencies to allowed versions.
  - Example: `cu`

- **`creq`**
  - Availability: 🖥️ Desktop
  - Command: `composer require`
  - Description: Adds a package.
  - Example: `creq vendor/package`

- **`creqd`**
  - Availability: 🖥️ Desktop
  - Command: `composer require --dev`
  - Description: Adds a package as a dev-dependency.
  - Example: `creqd phpunit/phpunit`

- **`cdump`**
  - Availability: 🖥️ Desktop
  - Command: `composer dump-autoload`
  - Description: Regenerates the Composer autoloader.
  - Example: `cdump`

- **`crun`**
  - Availability: 🖥️ Desktop
  - Command: `composer run`
  - Description: Executes a script from composer.json.
  - Example: `crun dev`

### Node / JavaScript
- **`ni`**
  - Availability: 🌐 Both
  - Command: `npm install`
  - Description: Installs all package.json dependencies.
  - Example: `ni`

- **`nid`**
  - Availability: 🌐 Both
  - Command: `npm install --save-dev`
  - Description: Installs a package as a dev-dependency.
  - Example: `nid typescript`

- **`nr`**
  - Availability: 🌐 Both
  - Command: `npm run`
  - Description: Executes a package.json script.
  - Example: `nr build`

- **`nrd`**
  - Availability: 🌐 Both
  - Command: `npm run dev`
  - Description: Starts the development server.
  - Example: `nrd`

- **`nrb`**
  - Availability: 🌐 Both
  - Command: `npm run build`
  - Description: Runs the production build.
  - Example: `nrb`

- **`nrt`**
  - Availability: 🌐 Both
  - Command: `npm run test`
  - Description: Runs tests.
  - Example: `nrt`

- **`nx`**
  - Availability: 🌐 Both
  - Command: `npx`
  - Description: Executes a Node package without installing it globally.
  - Example: `nx create-react-app my-app`

- **`bi`**
  - Availability: 🌐 Both
  - Command: `bun install`
  - Description: Installs dependencies with Bun.
  - Example: `bi`

- **`br`**
  - Availability: 🌐 Both
  - Command: `bun run`
  - Description: Executes a script with Bun.
  - Example: `br dev`

- **`brd`**
  - Availability: 🌐 Both
  - Command: `bun run dev`
  - Description: Starts the dev server with Bun.
  - Example: `brd`

- **`brb`**
  - Availability: 🌐 Both
  - Command: `bun run build`
  - Description: Production build with Bun.
  - Example: `brb`

- **`bx`**
  - Availability: 🌐 Both
  - Command: `bunx`
  - Description: Executes a package without installing, via Bun.
  - Example: `bx cowsay hello`

- **`pn`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm`
  - Description: Shortcut for pnpm.
  - Example: `pn add axios`

- **`pni`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm install`
  - Description: Installs dependencies with pnpm.
  - Example: `pni`

- **`pnr`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm run`
  - Description: Executes a package.json script via pnpm.
  - Example: `pnr build`

- **`pnd`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm run dev`
  - Description: Starts the dev server with pnpm.
  - Example: `pnd`

- **`pnb`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm run build`
  - Description: Production build with pnpm.
  - Example: `pnb`

- **`pnt`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm run test`
  - Description: Runs tests with pnpm.
  - Example: `pnt`

- **`pnx`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm dlx`
  - Description: Executes a package without installing via pnpm.
  - Example: `pnx create-next-app`

- **`pnadd`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm add`
  - Description: Adds a dependency with pnpm.
  - Example: `pnadd axios`

- **`pnaddd`**
  - Availability: 🖥️ Desktop
  - Command: `pnpm add -D`
  - Description: Adds a dev-dependency with pnpm.
  - Example: `pnaddd vitest`

### Python / uv
- **`py`**
  - Availability: 🖥️ Desktop
  - Command: `python3`
  - Description: Shortcut for Python 3.
  - Example: `py main.py`

- **`pyv`**
  - Availability: 🖥️ Desktop
  - Command: `python3 --version`
  - Description: Displays the active Python version.
  - Example: `pyv`

- **`uvi`**
  - Availability: 🖥️ Desktop
  - Command: `uv pip install`
  - Description: Installs a Python package with uv.
  - Example: `uvi requests`

- **`uvs`**
  - Availability: 🖥️ Desktop
  - Command: `uv run`
  - Description: Executes a script with uv.
  - Example: `uvs main.py`

- **`venv`**
  - Availability: 🖥️ Desktop
  - Command: `python3 -m venv .venv && source .venv/bin/activate`
  - Description: Creates and activates a local virtualenv.
  - Example: `venv`

- **`activate`**
  - Availability: 🖥️ Desktop
  - Command: `source .venv/bin/activate`
  - Description: Activates the local virtualenv in the directory.
  - Example: `activate`

### Ruby / rbenv
- **`rbv`**
  - Availability: 🖥️ Desktop
  - Command: `rbenv versions`
  - Description: Lists Ruby versions installed via rbenv.
  - Example: `rbv`

- **`rblocal`**
  - Availability: 🖥️ Desktop
  - Command: `rbenv local`
  - Description: Sets the Ruby version for the current directory.
  - Example: `rblocal 3.2.0`

- **`rbglobal`**
  - Availability: 🖥️ Desktop
  - Command: `rbenv global`
  - Description: Sets the global Ruby version.
  - Example: `rbglobal 3.2.0`

- **`be`**
  - Availability: 🖥️ Desktop
  - Command: `bundle exec`
  - Description: Executes a command in the Bundler context.
  - Example: `be rails s`

- **`binstall`**
  - Availability: 🖥️ Desktop
  - Command: `bundle install`
  - Description: Installs gems from the Gemfile.
  - Example: `binstall`

- **`bupdate`**
  - Availability: 🖥️ Desktop
  - Command: `bundle update`
  - Description: Updates gems from the Gemfile.
  - Example: `bupdate`

### Rust / Cargo
- **`cb`**
  - Availability: 🖥️ Desktop
  - Command: `cargo build`
  - Description: Compiles the Rust project in debug mode.
  - Example: `cb`

- **`cbr`**
  - Availability: 🖥️ Desktop
  - Command: `cargo build --release`
  - Description: Compiles in optimized release mode.
  - Example: `cbr`

- **`crun2`**
  - Availability: 🖥️ Desktop
  - Command: `cargo run`
  - Description: Compiles and runs the Rust project.
  - Example: `crun2`

- **`ct`**
  - Availability: 🖥️ Desktop
  - Command: `cargo test`
  - Description: Runs project tests.
  - Example: `ct`

- **`ccheck`**
  - Availability: 🖥️ Desktop
  - Command: `cargo check`
  - Description: Checks for errors without generating a binary.
  - Example: `ccheck`

- **`clippy`**
  - Availability: 🖥️ Desktop
  - Command: `cargo clippy`
  - Description: Runs the Rust linter.
  - Example: `clippy`

- **`cfmt`**
  - Availability: 🖥️ Desktop
  - Command: `cargo fmt`
  - Description: Formats code with rustfmt.
  - Example: `cfmt`

- **`cadd`**
  - Availability: 🖥️ Desktop
  - Command: `cargo add`
  - Description: Adds a dependency to the Rust project.
  - Example: `cadd serde`

- **`crem`**
  - Availability: 🖥️ Desktop
  - Command: `cargo remove`
  - Description: Removes a dependency from the Rust project.
  - Example: `crem serde`

- **`cupdate`**
  - Availability: 🖥️ Desktop
  - Command: `cargo update`
  - Description: Updates all Cargo.lock dependencies.
  - Example: `cupdate`

- **`cdoc`**
  - Availability: 🖥️ Desktop
  - Command: `cargo doc --open`
  - Description: Generates and opens project documentation in the browser.
  - Example: `cdoc`

### Go
- **`gobuild`**
  - Availability: 🖥️ Desktop
  - Command: `go build ./...`
  - Description: Compiles all project packages in Go.
  - Example: `gobuild`

- **`gorun`**
  - Availability: 🖥️ Desktop
  - Command: `go run .`
  - Description: Runs the main package.
  - Example: `gorun`

- **`gotest`**
  - Availability: 🖥️ Desktop
  - Command: `go test ./...`
  - Description: Runs all project tests.
  - Example: `gotest`

- **`gomod`**
  - Availability: 🖥️ Desktop
  - Command: `go mod tidy`
  - Description: Removes unused dependencies from go.mod.
  - Example: `gomod`

- **`govet`**
  - Availability: 🖥️ Desktop
  - Command: `go vet ./...`
  - Description: Checks for common issues in Go code.
  - Example: `govet`

- **`gofmt`**
  - Availability: 🖥️ Desktop
  - Command: `gofmt -w .`
  - Description: Formats all Go files in the directory.
  - Example: `gofmt`

- **`goget`**
  - Availability: 🖥️ Desktop
  - Command: `go get`
  - Description: Adds a dependency to the Go project.
  - Example: `goget github.com/gin-gonic/gin`

- **`goclean`**
  - Availability: 🖥️ Desktop
  - Command: `go clean -cache`
  - Description: Removes Go build cache.
  - Example: `goclean`

- **`gocover`**
  - Availability: 🖥️ Desktop
  - Command: `go test ./... -coverprofile=coverage.out && go tool cover -html=coverage.out`
  - Description: HTML coverage.
  - Example: `gocover`

- **`gowork`**
  - Availability: 🖥️ Desktop
  - Command: `go work`
  - Description: Manages Go workspaces.
  - Example: `gowork use ./pkg`

## DevOps & System

- **`anp`**
  - Availability: 🌐 Both
  - Command: `ansible-playbook`
  - Description: Executes a playbook.
  - Example: `anp site.yml -i hosts`

- **`ani`**
  - Availability: 🌐 Both
  - Command: `ansible-inventory --list`
  - Description: Displays the inventory in JSON format.
  - Example: `ani`

- **`anping`**
  - Availability: 🌐 Both
  - Command: `ansible all -m ping`
  - Description: Tests connectivity with all hosts.
  - Example: `anping`

- **`anv`**
  - Availability: 🌐 Both
  - Command: `ansible-vault`
  - Description: Manages encrypted files with Vault.
  - Example: `anv edit secrets.yml`

- **`anve`**
  - Availability: 🌐 Both
  - Command: `ansible-vault encrypt`
  - Description: Encrypts a file with Vault.
  - Example: `anve secrets.yml`

- **`anvd`**
  - Availability: 🌐 Both
  - Command: `ansible-vault decrypt`
  - Description: Decrypts a file with Vault.
  - Example: `anvd secrets.yml`

- **`anvr`**
  - Availability: 🌐 Both
  - Command: `ansible-vault rekey`
  - Description: Re-encrypts with a new password.
  - Example: `anvr secrets.yml`

- **`ancheck`**
  - Availability: 🌐 Both
  - Command: `ansible-playbook --check`
  - Description: Simulates playbook execution without applying changes.
  - Example: `ancheck site.yml`

- **`andiff`**
  - Availability: 🌐 Both
  - Command: `ansible-playbook --check --diff`
  - Description: Simulates and displays a diff of the changes that would be applied.
  - Example: `andiff site.yml`

- **`anfacts`**
  - Availability: 🌐 Both
  - Command: `ansible all -m setup`
  - Description: Collects facts from all inventory hosts.
  - Example: `anfacts`

### Monitoring & Processes
- **`topc`**
  - Availability: 🌐 Both
  - Command: `top -o cpu` (macOS) / `top -bn1 | head -20` (Linux)
  - Description: Monitors processes ordered by CPU usage.
  - Example: `topc`

- **`topm`**
  - Availability: 🖥️ Desktop macOS
  - Command: `top -o mem`
  - Description: Monitors processes ordered by memory usage.
  - Example: `topm`

- **`psg`**
  - Availability: 🌐 Both
  - Command: `ps aux | grep`
  - Description: Searches for processes by name.
  - Example: `psg nginx`

- **`df`**
  - Availability: 🌐 Both
  - Command: `df -h`
  - Description: Disk usage with human-readable sizes.
  - Example: `df`

- **`meminfo`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `free -h`
  - Description: Displays RAM and swap usage.
  - Example: `meminfo`

- **`diskinfo`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `df -h`
  - Description: Displays disk usage of all partitions.
  - Example: `diskinfo`

- **`cpuinfo`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `lscpu`
  - Description: Displays detailed CPU information.
  - Example: `cpuinfo`

- **`sysinfo`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `hostnamectl`
  - Description: Displays OS and hostname information.
  - Example: `sysinfo`

### Systemd (Linux)
- **`sstatus`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl status`
  - Description: Displays the status of a service.
  - Example: `sstatus nginx`

- **`sstart`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl start`
  - Description: Starts a service.
  - Example: `sstart nginx`

- **`sstop`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl stop`
  - Description: Stops a service.
  - Example: `sstop nginx`

- **`srestart`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl restart`
  - Description: Restarts a service.
  - Example: `srestart nginx`

- **`senable`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl enable`
  - Description: Enables a service to start on boot.
  - Example: `senable nginx`

- **`sdisable`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo systemctl disable`
  - Description: Disables a service on boot.
  - Example: `sdisable nginx`

- **`slogs`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo journalctl -u`
  - Description: Displays logs for a specific service.
  - Example: `slogs nginx`

- **`syslog`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `sudo journalctl -f`
  - Description: Follows the system log in real-time.
  - Example: `syslog`

## Network & Web

- **`myip`**
  - Availability: 🌐 Both
  - Command: `curl -s ifconfig.me`
  - Description: Displays the machine's public IP.
  - Example: `myip`

- **`localip`**
  - Availability: 🌐 Both
  - Command: `ipconfig getifaddr en0` (macOS) / `hostname -I...` (Linux)
  - Description: Displays the primary local IP of the machine.
  - Example: `localip`

- **`ports`**
  - Availability: 🌐 Both
  - Command: `lsof -iTCP -sTCP:LISTEN -n -P` (macOS) / `ss -tulnp` (Linux)
  - Description: Lists all listening ports.
  - Example: `ports`

- **`wholistening`**
  - Availability: ☁️ Server / 🖥️ Desktop Linux
  - Command: `ss -tulnp`
  - Description: Alternative alias for listing listening ports.
  - Example: `wholistening`

- **`flush`**
  - Availability: 🌐 Both
  - Command: `dscacheutil...` (macOS) / `sudo systemd-resolve...` (Linux)
  - Description: Clears the DNS cache.
  - Example: `flush`

### cURL / HTTP
- **`get`**
  - Availability: 🌐 Both
  - Command: `curl -s`
  - Description: Simple GET request.
  - Example: `get https://api.github.com`

- **`post`**
  - Availability: 🌐 Both
  - Command: `curl -s -X POST -H 'Content-Type: application/json'`
  - Description: Simple JSON POST request.
  - Example: `post url -d '{"key":"val"}'`

- **`headers`**
  - Availability: 🌐 Both
  - Command: `curl -sI`
  - Description: Displays only response HTTP headers.
  - Example: `headers google.com`

- **`httpcode`**
  - Availability: 🌐 Both
  - Command: `curl -o /dev/null -s -w '%{http_code}\n'`
  - Description: Displays only the HTTP response code.
  - Example: `httpcode google.com`

- **`timing`**
  - Availability: 🌐 Both
  - Command: `curl -o /dev/null -s -w 'dns:%{time_namelookup}s...'`
  - Description: Detailed latency information.
  - Example: `timing google.com`

### JSON / YAML
- **`jpp`**
  - Availability: 🌐 Both
  - Command: `python3 -m json.tool`
  - Description: Formats and validates JSON.
  - Example: `cat data.json | jpp`

- **`jsonf`**
  - Availability: 🌐 Both
  - Command: `jq .`
  - Description: Formats JSON with colors via jq.
  - Example: `cat data.json | jsonf`

### Security & Certs
- **`certinfo`**
  - Availability: 🌐 Both
  - Command: `openssl x509 -text -noout -in`
  - Description: Displays .pem certificate details.
  - Example: `certinfo cert.pem`

- **`certexpiry`**
  - Availability: 🌐 Both
  - Command: `openssl x509 -enddate -noout -in`
  - Description: Displays a certificate's expiration date.
  - Example: `certexpiry cert.pem`

- **`sslcheck`**
  - Availability: 🌐 Both
  - Command: `openssl s_client -connect`
  - Description: Inspects a host's TLS.
  - Example: `sslcheck google.com:443`

- **`genpass`**
  - Availability: 🌐 Both
  - Command: `openssl rand -base64 32`
  - Description: Generates a secure random 32-byte password.
  - Example: `genpass`

### Environment
- **`envls`**
  - Availability: 🌐 Both
  - Command: `env | sort`
  - Description: Lists all environment variables sorted.
  - Example: `envls`

- **`envg`**
  - Availability: 🌐 Both
  - Command: `env | grep`
  - Description: Filters environment variables.
  - Example: `envg PATH`

- **`dotenv`**
  - Availability: 🌐 Both
  - Command: `export $(cat .env | grep -v '^#' | xargs)`
  - Description: Loads variables from the current .env file.
  - Example: `dotenv`

---
> Follow the formatting guide: [Markdown Format Guide](.claude/commands/markdown-format.md)

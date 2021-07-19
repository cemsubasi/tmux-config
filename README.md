# Tmux Configuration File

### Requirements

#### [Tmux](https://github.com/tmux/tmux) (Terminal Multiplexer)

#### [TPM](https://github.com/tmux-plugins/tpm) (Tmux Plugin Manager)

### Installation

```sh
git clone https://github.com/cemsubasi/tmux-config.git 
```
- Open downloaded file with any text editor.
- Copy codes to your .tmux.conf which is in your home directory. 
- If it doesn't exist than copy downloaded file to your home directory and add '.' prefix.
- Save and exit.
- Re-open .tmux.conf file and reload tmux environment so TPM is sourced:

```bash
# type this in terminal if tmux is already running
tmux source ~/.tmux.conf
```
- Press `prefix` (Ctrl + b) + <kbd>I</kbd> (capital i, as in **I**nstall) to fetch the plugin.

##### Thats it.

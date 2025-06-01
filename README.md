
# INSTALLATION GUIDE BELOW

```bash
sudo apt update
```
```bash
sudo apt install -y
```

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof nano unzip iproute2
```

```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
```

```bash
screen -S gensyn
```

```bash
cd $HOME && rm -rf gensyn-testnet && git clone https://github.com/zunxbt/gensyn-testnet.git && chmod +x gensyn-testnet/gensyn.sh && ./gensyn-testnet/gensyn.sh
```

This command for update error and do smooth
```bash
curl https://raw.githubusercontent.com/imysryasir/Gsnyn-1-Click-Solutions/refs/heads/main/fixgensyn.sh | bash
```
```bash
cd rl-swarm
```

```bash
RL_SWARM_UNSLOTH=False ./run_rl_swarm.sh
```
This command to check all improtant files
```bash
[ -f backup.sh ] && rm backup.sh; curl -sSL -O https://raw.githubusercontent.com/AbhiEBA/gensyn1/main/backup.sh && chmod +x backup.sh && ./backup.sh
```

```bash
screen -ls
```

```bash
screen -r
```
To kill a screen session in Linux, you can use the following command:

```bash
screen -X -S <session_name> quit
```

>
> New Update -----------------------------------
>
> To restart the node run
>
> ```bash
> cd rl-swarm
> ```
>
> ```bash
> python3 -m venv .venv
> source .venv/bin/activate
> ```
>
> ```bash
> ./run_rl_swarm.sh
> ```
>
> ```bash
> cloudflared tunnel --url http://localhost:3000
> ```

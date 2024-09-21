# paiton

A simple script to manage your Python virtual environments.
By default all virtual enviroments are stored in /home/user_name/.py-venv

## Installation

```bash
wget https://raw.githubusercontent.com/nonzeroexit/paiton/main/paiton.sh
sudo chmod a+rx paiton.sh
sudo mv paiton.sh /usr/local/bin/paiton
```

## Usage

### Create a new virtual environment

```bash
paiton -m v_env_name
```

### Activate virtual environment

```bash
source paiton v_env_name
```

### Delete virtual environment

```bash
paiton -d v_env_name
```

### Show help and virtual environments

```bash
paiton -h
```

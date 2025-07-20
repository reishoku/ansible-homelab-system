
# Ansible Playbook to configure homelab

## Setup

```sh
uv venv .venv
source .venv/bin/activate.fish
uv sync

ansible-galaxy collection install -r ./galaxy_requirements.yml
```

## Author

- KOSHIKAWA Kenichi

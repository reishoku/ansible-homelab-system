
# Ansible Playbook to conigure `home.reishoku.net` hosts

## Setup

```fish
# Create Python virtual environment in `.venv/` directory
uv venv .venv

# Activate Python virtual environment
source .venv/bin/activate.fish

# Install dependent packages
uv sync

# Install Ansible collections, roles
ansible-galaxy collection install -r ./galaxy_requirements.yml
```

## Author

- KOSHIKAWA Kenichi

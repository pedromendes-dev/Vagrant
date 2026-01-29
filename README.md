# Vagrant Project

Este projeto utiliza o Vagrant para criar e gerenciar ambientes de desenvolvimento.

## Estrutura do Projeto

- `docker.sh`: Script para gerenciar containers Docker.
- `master.sh`: Script principal para iniciar o ambiente.
- `worker.sh`: Script para gerenciar workers no ambiente.
- `Vagrantfile`: Arquivo de configuração do Vagrant.

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedromendes-dev/Vagrant.git
   cd Vagrant
   ```
2. Inicie o ambiente:
   ```bash
   vagrant up
   ```
3. Acesse o ambiente:
   ```bash
   vagrant ssh
   ```

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou correções. Abra um pull request ou envie um issue para discutir suas ideias!
# IaaS - Infraestrutura como Serviço

O modelo IaaS permite o uso de máquinas virtuais, redes, balanceadores de carga e armazenamento, fornecidos pela Azure.

**Exemplo de serviços IaaS:**
- Azure Virtual Machines
- Azure VNet
- Azure Load Balancer

**Comando para criar uma VM no Azure CLI:**
```bash
az login
az vm create \
  --resource-group MeuGrupo \
  --name MinhaVM \
  --image UbuntuLTS \
  --admin-username azureuser \
  --generate-ssh-keys
```
# Automation Prometheus-Alert
O objetivo desta automação é apresentar um exemplo prático de como implantar um sistema completo de monitoramento e alertas, utilizando as ferramentas Prometheus e Alertmanager, orquestradas pelo Ansible. O Ansible é uma poderosa ferramenta de automação de TI, originada na Red Hat, projetada para facilitar a implantação e a manutenção de infraestruturas e serviços de forma padronizada e reutilizável. Antes de executar esta automação, é crucial que você revise cada arquivo e realize os ajustes necessários para que a implantação seja bem-sucedida e 100% funcional no seu contexto. O Prometheus, por sua vez, é uma referência no monitoramento de serviços e infraestrutura, enquanto o Alertmanager complementa essa função ao gerenciar os alertas gerados, notificando as equipes responsáveis. Juntos, eles são peças-chave para a observabilidade, um dos fundamentos da cultura DevOps.

Pré-requisitos:

1. Python3 ou versões posteriores;
2. Componente PIP;

Para usar esta IaC, siga os passos abaixo:

1. Crie um ambiente virtual na sua máquina:

```bash
python3 -m venv <seu_ambiente_virtual>
source <seu_ambiente_virtual>/bin/activate
```

2. Instale as bibliotecas:
```bash
pip install -r requirements.txt
```
3. Agora, execute a automação:
```
ansible-playbook init_prometheus.yml -K

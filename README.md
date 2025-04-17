# Automation Prometheus-Alert
essa automação foi criado para demonstrar como funciona um deploy com ansible de um sistema de monitoramento e alertas com Prometheus e alertmanager, ansible é uma ferramente de automação de TI criada por alguns funcionarios da Red hat para facilitar o deployment de infra-estruturas e serviços que podem ser reutilizados, antes de usar essa automação sugiro que verifique arquivo por arquivo e faça as mudanças necessarias para fazer um deployment 100% funcional.

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

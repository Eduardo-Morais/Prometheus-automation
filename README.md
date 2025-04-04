# IAC-Prometheus-Alert
essa IAC foi criada para demonstrar como é realizado o deployment de um Prometheus com Alertmanager,com o intuito de monitorar VMs com NodeExport e notificar atráves de um chatbot do telegram,porém pode ser usada para outros tipos de monitoramento só adicionar o scrape no prometheus, para utilizar essa IAC primeiro visite arquivo por arquivo para modificar as sessões necessarias, após a modificação, realize os passos abaixo.

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

# Lightspeed Demo Repo

Configure and Licencing: https://www.redhat.com/en/blog/getting-started-red-hat-ansible-lightspeed-ibm-watsonx-code-assistant

Setup Watsonx for Codes Assistent: https://cloud.ibm.com/docs/watsonx-code-assistant?topic=watsonx-code-assistant-cloud-setup-a

Preismodolle WatsonX: https://cloud.ibm.com/catalog/services/ibm-watsonx-code-assistant



Install Vscode

Install Ansible Extension:

https://marketplace.visualstudio.com/items?itemName=redhat.ansible

create venv:
 
~~~bash
python3 -m venv .venv
# activate
source .venv/bin/activate
~~~

install ansible
 
~~~bash 
pip install -r requirements.txt
~~~ 


requirements.txt:

~~~
ansible
ansible-lint
ansible-navigator
ansible-creator
ansible-builder
ansible-sign
molecule
molecule-podman
pytest-ansible
tox-ansible
netaddr>=0.8
Jinja2>=3.1.2
~~~

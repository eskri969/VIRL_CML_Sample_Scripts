# VIRL_CML_Sample_Scripts

This is a sample repository created to demo automation capabilities of Cisco Modeling Labs, used to be called VIRL2.

## Content
* **APIDEMO** : Utilizing CML REST API
* **ClientDemo1** : Simple Lab creation and management via Python virlClient
* **ClientDemo2** : Lab creation from real device config files, pyATS testbed generation and interaction with devices using Netmiko.

## Requirements
* CML Deployment
* Python3
* Jupyter Notebook

## Seturp

```bash
pip3 install requirements.txt
mv env.config env.py
```

Fill env.py with your enviroment variables:
```Python
config = {}

config['CML_SERVER_URL'] = "https://ip/"
config['CML_SERVER_IP'] = "ip"
config['CML_USERNAME'] = "cisco"
config['CML_PASSWORD'] = "cisco"
config['TOKEN'] = "token"
```



## Run

```bash
jupyter-lab .
```
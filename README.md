Spark Playbook
==============

## Setup

Install Python 2.7 and virtualenv, and then:

```bash
$ cd spark-playbook
$ virtualenv venv
$ source venv/bin/activate
$ pip install ansible
```

## Run

```bash
$ ansible-playbook -i hosts site.yml
```

Common
=========

Executa tarefas comuns a todos os servidores, nomeadamente:
  - Adiciona entradas de todos os nós em /etc/hosts
  - Criação do utilizador gluster
  - Instalação e configuração da Firewall 

Requirements
------------

netaddr Python package

Role Variables
--------------
firewall
firewall_allowed_tcpp - Portas permitidas pela firewall em tráfego TCP
firewall_allowed_udpp - Portas permitidas pela firewall em tráfego UDP

Dependencies
------------

-

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: gluster
      roles:
         - common

License
-------

BSD

Author Information
------------------

João David Silva Oliveira
2018018671
Instituto Politécnico de Coimbra
Instituto Superior de Engenharia de Coimbra
Este contéudo foi desenvolvido em âmbito de estágio na empre OneSource
https://onesource.pt/

# Vagrant
# Introdução/Resumo do Script Vagrant

**Objetivo**

Este script Vagrant automatiza a criação e provisionamento de três máquinas virtuais (VMs) Debian 9: uma master e duas slaves. Ele utiliza o box Vagrant `generic/debian9`, permitindo fácil implantação em diversas plataformas de virtualização.

**Funcionalidades**

- Cria três VMs:
    - `master`: A máquina central para sua configuração multinode.
    - `slave1`: A primeira máquina slave.
    - `slave2`: A segunda máquina slave.
- Configura todas as VMs com as seguintes configurações:
    - Sistema operacional Debian 9
    - Endereços IP atribuídos por DHCP em uma rede privada
    - 1024 MB de RAM

**Benefícios**

- **Eficiência:** Estabelece rapidamente um ambiente Debian 9 multinode para desenvolvimento, testes ou experimentação.
- **Reprodutibilidade:** Garante uma configuração de VM consistente em todas as implantações.
- **Personalização:** Modifique facilmente o script para ajustar a alocação de recursos (RAM, CPU), configurações de rede ou instalação de software adicional usando os recursos de provisionamento do Vagrant.

**Público-alvo**

- Desenvolvedores e administradores de sistema que trabalham em projetos que exigem um ambiente Debian 9 multinode.
- Qualquer pessoa que busque agilizar a configuração de uma infraestrutura local de desenvolvimento ou teste com Vagrant.

**Como usar**

1. Instale o Vagrant ([https://developer.hashicorp.com/vagrant/install](https://developer.hashicorp.com/vagrant/install)).
2. Baixe ou clone este repositório contendo o Vagrantfile.
3. Abra um terminal no diretório do projeto.
4. Execute `vagrant up` para provisionar as VMs.

**Observações Adicionais**

- Considere adicionar comentários dentro do Vagrantfile para explicar opções de configuração específicas.
- Explore a documentação do Vagrant para personalizar ainda mais o script ([https://developer.hashicorp.com/vagrant/docs](https://developer.hashicorp.com/vagrant/docs)).

**Resumo**

Este script Vagrant oferece uma maneira eficiente e replicável de configurar um ambiente de desenvolvimento ou teste multinode Debian 9. É ideal para desenvolvedores, administradores de sistema e qualquer pessoa que queira agilizar o processo de provisionamento de VMs.


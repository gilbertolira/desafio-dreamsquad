**************** Projeto Desafio DreamSquad ****************

Requisitos
	- Ansible deve estar instalado no seu ambiente de desenvolvimento/local.
    - É necessário configurar as informações de acesso no arquivo hosts:
        - Incluir a chave de acesso.
        - Especificar o número de IP da máquina host.
    - Atente para o arquivo vars.yaml dentro da pasta wordpress/vars:
        - Insira a senha do banco de dados neste arquivo.

Executando o Projeto

Para executar os playbooks, siga estas etapas:
    1. Navegue até o serviço que deseja executar.
    2. Execute o seguinte comando no terminal:
       ansible-playbook -i ../hosts playbook.yaml

Certifique-se de ter configurado corretamente os requisitos mencionados acima antes de executar os playbooks.

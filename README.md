# Criar um Banco de Dados SQL no Azure

## Criar um Banco de dados SQL

Na página inicial do Azure, pesquise “Bancos de dados SQL” na barra de pesquisa na parte superior.
![pagina-inicial](./images/pagina-inicial.png)

Na página Bancos de dados SQL, clique no botão “Criar”.
![criar-db-sql](./images/criar-db-sql.png)

## Configuração

### Básico

- Assinatura: Escolha sua assinatura do Azure.
- Grupo de recursos: Selecione um grupo de recursos existente ou crie um novo.

![assinatura-1](./images/assinatura-1.png)
![assinatura-2](./images/assinatura-2.png)

- Nome do banco de dados: Insira um nome exclusivo para seu banco de dados.

![detalhes-1](./images/detalhes-1.png)
![detalhes-2](./images/detalhes-2.png)

- Servidor: Você precisará selecionar um servidor existente ou criar um novo.
  - Para criar um novo servidor, clique em “Criar novo” próximo ao campo Servidor. Preencha o nome do servidor, localização e os detalhes do método de autenticação. Clique em OK para criar o servidor.
  
  ![servidor-1](./images/servidor-1.png)
  ![servidor-2](./images/servidor-2.png)

- Computação + armazenamento: Clique em Configurar banco de dados para ajustar os DTUs ou vCores, bem como o tamanho do armazenamento. Depois de configurado, clique em Aplicar.

![configurar](./images/configurar.png)

- Redundância do armazenamento de backup: Escolha uma opção de redundância de backup.

![backup](./images/backup.png)

### Rede

- Escolha Ponto de extremidade público ou Ponto de extremidade público dependendo da configuração da sua rede.
  - Para acesso público, defina Permitir que serviços e recursos do Azure acessem este servidor como Sim (se necessário). Defina Adicionar o endereço IP do cliente atual como Sim (se necessário).

![rede](./images/rede.png)
![firewall](./images/firewall.png)

### Configurações adicionais

- Fonte de dados: Escolha começar com um banco de dados em branco ou restaurar a partir de um backup.
- Ordenação: Mantenha o padrão ou escolha as configurações de ordenação (se necessário).

![adicionais](./images/adicionais.png)

### Revisar + Criar

- Verifique seus custos e todas as suas configurações que você fez.
- Clique em Criar para implementar o banco de dados. O Azure começará a provisionar o banco de dados SQL e os recursos relacionados.

![revisar-criar-1](./images/revisar-criar-1.png)
![revisar-criar-2](./images/revisar-criar-2.png)  

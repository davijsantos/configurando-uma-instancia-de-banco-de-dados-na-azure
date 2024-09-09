# Configurando uma instância de Banco de Dados na Azure

Levando em conta IaaS, segue-se uma demonstração de criação de máquina virtual dentro da cloud Azure.


![image](https://github.com/user-attachments/assets/90c8ce9f-917b-483a-ae9f-203ccd993854)
*Acessando o menu Máquinas Virtuais*

![image](https://github.com/user-attachments/assets/57145aa1-8501-48b7-bb1f-a64a0ffbc340)
*Clicando em criar*

![image](https://github.com/user-attachments/assets/c7cc9eaf-5dfa-4b49-8451-cfb2d4527adb)

Nas duas opções acima, é possível selecionar a imagem (que definirá o sistema operacional da máquina a ser criada), além da arquitetura do processador.

![image](https://github.com/user-attachments/assets/96f471c4-f2b6-4dd3-bce6-7eea3296daa4)

Na aba "Disco", é possível criar um ou mais discos, definindo espaço, tipo de armazenamento e criptografia de dados.

![image](https://github.com/user-attachments/assets/cc73b3c2-27fa-4aa9-adf8-5cd41565938a)

Nesta imagem é possível observar o formulário de criação e configuração de rede, definindo o endereçamento de rede, e a definição de políticas de segurança de rede relacionadas a esta máquina.

![image](https://github.com/user-attachments/assets/414db647-0260-41cc-9ec1-2deca19ad088)

Na aba de Gerenciamento, é possível realizar configurações de backup, configurar acesso via EntraID, configurar desligamento automático, dentre outras configurações.

Estes passos constituem um exemplo do nível de complexidade que envolve a criação de uma máquina virtual que caracteriza também IaaS.

## Criando Banco de Dados SQL

![image](https://github.com/user-attachments/assets/036e8495-a985-40cd-8d4b-c7e8448796b5)
*Acessando a tela de criação de um banco de dados SQL*

![image](https://github.com/user-attachments/assets/aca9c49c-1a99-4cd1-84d5-65e7d3bfbb22)
*Definindo o nome do banco de dados*

![image](https://github.com/user-attachments/assets/ddcb596e-95d9-43f0-b98f-8f5d7a7f5299)
*Criando a instância que hospedará o serviço de banco de dados*

![image](https://github.com/user-attachments/assets/536510e1-9d85-4228-88ff-14f7edf482d7)
*Definindo o método de autenticação de acesso ao serviço (EntraID e/ou SQL)*

![image](https://github.com/user-attachments/assets/4f60f340-33ce-40db-a0be-2d8b9657b7ea)

Caso o método de autenticação SQL seja selecionado, será obrigatória a definição de usuário e senha do administrador do servidor.

![image](https://github.com/user-attachments/assets/fc7db23f-a096-4f19-a3bf-e801d1366271)
*Definindo o administrador do Microsoft Entra*

![image](https://github.com/user-attachments/assets/ddb2b778-8fa0-4774-ab48-0a2453fb0f91)
*Definindo a forma de redundância, com backup em 3 opções: local, zona e geográfica*

Cada tipo de redundância definirá o SLA que determina as obrigações do provedor em fornecer disponibilidade do serviço contratado.

![image](https://github.com/user-attachments/assets/325072f0-d8f4-4e0f-b3f8-e1ca2cf1a219)
*Calculadora que informa a previsão de custo do serviço*

Aqui nós temos um exemplo de PaaS, onde um serviço de banco de dados compõe um elemento de um ambiente de desenvolvimento.








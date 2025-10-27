Passo a Passo para Criar uma Instância EC2
1. Acesse o Console da AWS

Vá para console.aws.amazon.com
Faça login com suas credenciais.

2. Abra o Serviço EC2

No menu de serviços, procure por EC2 e clique.

3. Clique em “Launch Instance”

Na página principal do EC2, clique em “Launch Instance” ou “Iniciar instância”.

4. Configure a Instância

Nome da instância: Escolha um nome descritivo.
Imagem do sistema operacional (AMI): Escolha uma Amazon Machine Image, como Ubuntu, Amazon Linux, Windows, etc.
Tipo de instância: Selecione o tipo (ex: t2.micro para uso gratuito).
Par de chaves (Key Pair): Crie ou selecione uma chave para acesso SSH.
Configurações de rede:

Escolha a VPC e a sub-rede.
Configure o grupo de segurança (libere portas como 22 para SSH, 80 para HTTP, etc).



5. Armazenamento

Configure o volume de armazenamento (geralmente padrão é suficiente).

6. Configurações Avançadas (opcional)

Scripts de inicialização (user data), roles do IAM, etc.

7. Revisar e Criar

Revise todas as configurações.
Clique em “Launch Instance”.

8. Acessar a Instância

Após o status mudar para “running”, copie o IP público.

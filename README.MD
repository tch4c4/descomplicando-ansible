# Treinamento descomplicando o Ansible

# Projeto de instalação de um cluster Kubernetes + AWS


 ## Projeto
 ````
 Day 1 + Day 2 => Provisioning 
 Day 3 => Install Cluster
 Day 4 + Day 5 => Deploy App
 ````
 ### Day 1 
 Instruções iniciais do ansible
 ### Day 2
 Criação de credenciais e criando os primeiros hosts na AWS.
 ### Day 3
 Instalando um cluster Kubernetes
 ### Day 4 
 Instalando Helm Prometheus + App
 ### Day 5 
 Instalando Versão 2 do app e utilizando os handlers


# Dependencia
Instalar aws cli
````
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

aws --version
````
# Configurar Credencial
````
aws --profile giropops configure  
(adicionar Access key ID e Senha)
us-east-1
````


# Lab 171 - Criação de Instâncias do Amazon EC2

## Visão geral
Neste laboratório, pratiquei a criação e o gerenciamento de instâncias do Amazon EC2 utilizando tanto o Console de Gerenciamento da AWS quanto a AWS CLI, além de configurar um host bastion e solucionar problemas de serviço.

## Atividades realizadas
1. **Criação do Host Bastion no Console da AWS:** Instância `t3.micro` com Amazon Linux 2 na `Lab VPC`, Security Group SSH e perfil IAM `Bastion-Role`.
2. **Conexão segura via EC2 Instance Connect:** Acesso direto ao terminal Linux pelo navegador.
3. **Lançamento de servidor web usando AWS CLI:** Consulta de AMI no Parameter Store e execução de `aws ec2 run-instances` com script `UserData.txt`.
4. **Validação do servidor web:** Verificação do painel web através do DNS IPv4 público.
5. **Resolução de problemas:** Correção de acessos e do serviço Apache na instância `Misconfigured Web Server`.

*(As imagens ilustrativas de cada etapa podem ser incluídas no repositório seguindo o padrão de prints do Lab 170).*

## O que aprendi
* Criar e configurar instâncias EC2 pelo Console da AWS.
* Associar IAM Role para comandos CLI sem chaves fixas.
* Conectar-se via EC2 Instance Connect.
* Consultar parâmetros de AMI no Systems Manager Parameter Store.
* Automatizar servidores web com AWS CLI e User Data.
* Diagnosticar e resolver falhas de conectividade e serviços web.

## Página do projeto
**[Acessar GitHub Pages](https://github.io)**

## Créditos
Laboratório realizado na **Escola da Nuvem** (Formação em Computação em Nuvem).
* Professor: [Raphael Ohlsen](https://linkedin.com)
* Instituição: [Escola da Nuvem](https://escoladanuvem.org)

# Lab 171 - Criação de Instâncias do Amazon EC2

## Visão geral

Neste laboratório, pratiquei o lançamento e o gerenciamento de instâncias do Amazon EC2 utilizando o Console da AWS e a AWS CLI. Configurei um host bastion com IAM Role, publiquei um servidor web automatizado com User Data e realizei diagnósticos de rede e serviço.

## Atividades realizadas

1. **Criação do Host Bastion**: Instância `t3.micro` com Amazon Linux 2, Security Group para SSH e IAM Role `Bastion-Role`.
2. **Conexão e AWS CLI**: Uso do EC2 Instance Connect para consultar região, AMI no Systems Manager Parameter Store e instâncias ativas.
3. **Servidor Web via AWS CLI**: Lançamento via `aws ec2 run-instances` com script `UserData.txt`.
4. **Validação**: Confirmação da aplicação web *Widget Manufacturing Dashboard* no navegador através do DNS IPv4 público.
5. **Resolução de Problemas**: Correção na instância `Misconfigured Web Server` para restaurar o acesso e a página padrão do Apache.

## O que aprendi

- Criação e gerenciamento de instâncias EC2 (Console e AWS CLI).
- Associação de IAM Role e conexão via EC2 Instance Connect.
- Consulta de AMIs no Systems Manager Parameter Store.
- Automação com scripts de User Data e solução de problemas de rede.

## Página do projeto

**[Acessar GitHub Pages](https://github.io)** (Resumo e flashcards interativos).

## Créditos

Laboratório realizado durante a formação em Computação em Nuvem (AWS re/Start) da **Escola da Nuvem**.

- Professor: [Raphael Ohlsen](https://br.linkedin.com/in/raphael-ohlsen)
- Instituição: [Escola da Nuvem](https://escoladanuvem.org) | [LinkedIn da Escola da Nuvem](https://www.linkedin.com/school/escola-da-nuvem/)

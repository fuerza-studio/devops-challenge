# Challenge DevOps | Fuerza Studio

Desafio para atuação na área de DevOps na [Fuerza Studio](https://fuerzastudio.com.br)

---

## Sobre a Fuerza Studio

Uma empresa que está há 11 anos no mercado de tecnologia trabalhando com desenvolvimento web, design e branding. Nosso trabalho já foi reconhecido mundialmente, alcançando inclusive o Vale do Silício nos EUA e também grandes mercados digitais como a Europa e a Ásia.
Envio abaixo o link do site da empresa para que vocês possam conhecer um pouco mais da nossa história.
[fuerzastudio.com.br](https://www.fuerzastudio.com.br)

---



## Introdução

Desafio consiste em criar um ambiente de maneira automatizada para servir um site em [WordPress](https://wordpress.org/).

---

## Escopo

Para o site WordPress, é necessário que ele seja servido pelo [Apache](https://www.apache.org/) e o [PHP](https://www.php.net/) na versão 7.4.x.
Ter um proxy com [Nginx](https://www.nginx.com/).
Configurar banco de dados [MySQL](https://www.mysql.com/) na versão 5.7.x.

---

## Requisitos

* Usar a [AWS](https://aws.amazon.com/) como solução em cloud.
* O servidor deverão ter acesso público somente às portas 22, 80 e 443.
* Separar os serviços em containers usando [Docker](https://www.docker.com/).
* Deverá ter pelo menos 3 containers.¹
* Os containers deverão ter uma rede com IP fixos.
* Você estará livre para escolher script para automação, Bash, Python, Ruby e dentre outros ou usar o conceito de IaC, Ansible, Puppet, Chef...
* Ter experiência em realizar documentação técnica.
---

## Diferenciais

* Usar o Docker Compose para definir os serviços.
* Terraform para o aprovisionamento dos serviços na AWS.
* Criar uma VPC na AWS.
* Configurar o banco de dados em uma RDS.
---

## Instruções

Para realizar o desafio, envie um email para `devops@fuerzastudio.com.br` com o assunto: *Challenge DevOps* que serão enviadas maiores orientações a respeito do desafio. Obrigado pelo seu interesse!

---

## Dúvidas

Qualquer dúvida a respeito do desafio entre em contato conosco através do email devops@fuerzastudio.com.br que teremos o maior prazer em esclarecer.


¹ Se optar em usar uma instância separada para o MySql como por exemplo, pode-se o mínimo de 2 containers.

Boa sorte!

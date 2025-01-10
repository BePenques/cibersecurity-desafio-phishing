## Projeto prático do Bootcamp de cibersegurança da plataforma Dio - Phishing para captura de senhas do Facebook/Redes sociais

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados
Opção numero 1: 
![Screenshot_1](https://github.com/user-attachments/assets/5eceb88f-fe2f-4cb6-a54a-b147d0006584)

Opção numero 3:
![Screenshot_2](https://github.com/user-attachments/assets/5eee0957-1b78-4afd-81fa-f90e334121bd)

Opção numero 2(Site cloner):
![Screenshot_3](https://github.com/user-attachments/assets/6fda5a3b-a1d4-43dc-b472-2c6f51e8163b)

Acesse o navegador na maquina host com o seu ip (utilize ifconfig para saber o ip) 
![Screenshot_4](https://github.com/user-attachments/assets/44c7984f-9aa5-4635-8e5e-838def406fcb)
![Screenshot_5](https://github.com/user-attachments/assets/075f4fd5-afeb-4077-b40e-bd19c9870fbc)

O login e senha devem aparecer no console:
![Alt text](./passwd.png "Optional title")

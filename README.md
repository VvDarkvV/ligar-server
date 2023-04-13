# COMO LIGAR O SERVIDOR

Rápido tutorial para ensinar como iniciar o server pelo Google Shell

### TUTORIAL

1- Acesse a conta Google que o server está hosteado;

LISTA DE CONTAS SENDO USADAS
```
COBBLEMON:
e-mail: greatminerinhos@gmail.com 
senha: M1n3rsGr3@t
```

2- Entre no site [console.cloud.google.com](https://console.cloud.google.com/) e *tenha certeza que a conta logada é a do server que você quer usar*;

3- Clique no botão **"Ativar Cloud Shell"**;

4- Espere o console carregar e envie o comando `cd mcserver`;

5- Depois, envie nessa sequência os comandos `chmod +x *` e `./startserver`;

6- Quando ele confirmar que o servidor foi executado, envie o comando `screen -ls` para ver quais programas estão sendo executados, os seguintes aplicativos devem aparecer:
```
afk
server
playit
```
Se algum desses estiver faltando, houve algum erro, me avise nesse caso;

7- Use o comando `screen -r afk` para acompanhar o início do servidor, **o servidor estará ligado quando o uso da cpu ficar estabilizado abaixo de 40%**;

8- Mantenha a página com o console aberta, *se essa aba for fechada, o server deve fechar em aprox. 1 hora*;

9- Abra o minecraft e conecte-se no server;

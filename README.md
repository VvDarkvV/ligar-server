# COMO LIGAR O SERVIDOR

Rápido tutorial para ensinar como iniciar o server pelo Google Shell

### LIGANDO O SERVIDOR

1- Acesse a conta Google que o server está hosteado;

LISTA DE CONTAS SENDO USADAS
```
COBBLEMON:
e-mail: greatminerinhos@gmail.com 
senha: M1n3rsGr3@t

VANILLA+:
email: joigin.mines@gmail.com
senha: J01g1nM@!n3
modpack: https://drive.google.com/file/d/1YRGN7oOZb62f48CRTsA6xpqfaRjpYi5w/view?usp=sharing
```

2- Entre no site [console.cloud.google.com](https://console.cloud.google.com/) e *tenha certeza que a conta logada é a do server que você quer usar*;

3- Clique no botão **"Ativar Cloud Shell"**;

MODO NOVO

1- Digite `chmod +x *` e depois `./iniciar.sh`

MODO ANTIGO

1- Espere o console carregar e envie o comando `cd mcserver`;

2- Depois, envie nessa sequência os comandos `chmod +x *` e `./startserver`;

3- Quando ele confirmar que o servidor foi executado, envie o comando `screen -ls` para ver quais programas estão sendo executados, os seguintes aplicativos devem aparecer:
```
afk
server
playit
```
Se algum desses estiver faltando, houve algum erro, me avise nesse caso;

### PREPARANDO O IP

1- No console do Google Shell, use o comando `screen -r playit`

2- Se aparecerem informações de forma parecida do que está demonstrado abaixo, pode ignorar o resto dos passos, caso contrario, seguir para o passo 3; 
```
 playit.gg program (v0.9.3)                                                                                                                                                                                                                 
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 (o) Overview  (t) Tunnels [1]  (n) Network [xxx ms]  (l) Logs                                                                                                                                                                                
════════════════════════════════════════════════════════════════════════════
Visit https://playit.gg/account to manage your account
Authenticated: true
Connection Alive: true
Tunnels Setup: true
Latest Latency: xxx ms
Connected Tunnel Server ID: xxxxx
TCP Client Count: x
UDP Client Count: x 
```
3- Entre no site [playit.gg](https://playit.gg/account/) e entre com o email e senha sendo usados;

4- Clique no link que aparecer no console após digitar o código `screen -r playit`

5- Quando o site carregar, faça o login se não tiver feito e aceite o *"agente"*;

### MANTENDO O SERVER

1- No Google Shell, clique no botão de + ao lado da aba do console, isso irá abrir outra instância do console como se tivesse acabado de abrir;

2- Use o comando `screen -r afk` para acompanhar o início do servidor, **o servidor estará ligado quando o uso da cpu ficar estabilizado abaixo de 40% sem ninguém jogando**;

3- Mantenha a página com o console aberta, *se essa aba for fechada, o server deve fechar em aprox. 1 hora*;

4- Abra o minecraft e conecte-se no server;

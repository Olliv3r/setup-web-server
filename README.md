# Setup server
Configura servidor web automaticamente

# Instalação:
```
apt update && apt upgrade -y && apt update && apt install git -y && git clone https://github.com/Olliv3r/Setup-server && cd Setup-server && chmod +x setup-server && ./setup-server --setup
```

### Atualizar o certificado:
*Obs* Caso deseja atualizar o certificado, basta executar o script `updateCert` dentro do diretório raiz deste projeto, deixe os campos em branco dando ENTER:
```
bash ./updateCert 
```

### Habilite e desabilite o certificado:
Desabilitar:
```
./setup-server --disable-ssl
```
Habilitar:
```
./setup-server --disable-ssl
```

### Capturas
### Setup-server:
![main](https://github.com/Olliv3r/Setup-server/blob/main/media/Main.jpg)

### Login: `root` & `toor`
### phpmyadmin:
![painel](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-admin.jpg)
![dashboard](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-dashboard.jpg)

## Recursos:
- [x] Certificado SSL
- [x] Gerenciador server-web (opcional)
- [x] PhpMyAdmin
- [x] Apache
- [x] MariaDB
- [x] Url amigável ativo (a)
- [x] Hospedagem em /sdcard/htdocs
- [ ] Outros

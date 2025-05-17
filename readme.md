# n8n_data
Esse repositório foi criado para armazenar todos os fluxos e códigos utilizados no n8n.

&nbsp;

# Possíveis erros
se você obter um erro como: 
```bash
Error: message: EACCES: permission denied, open '/home/node/.n8n/config'
```

de a permissão para os diretórios internos para seu usuário:
```bash
sudo chown -R $(whoami):$(whoami) n8n_data
sudo chown -R $(whoami):$(whoami) postgres_data
```

&nbsp;

# Como rodar
```bash
docker-compose up --build
```

&nbsp;

# Acessando o n8n
Acesse o n8n em http://localhost:1000
```bash
email: antenor.filho@digiall.com
senha: 123Antenor!
```
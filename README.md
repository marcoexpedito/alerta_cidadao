# 🚨 Alerta Cidadão

Uma aplicação web em JavaScript que permite ao cidadão receber alertas SMS baseados na sua localização, eventos de segurança e notícias locais.

---

## 🧠 Como funciona

1. O usuário informa seu número de telefone e região ou seleciona um local no mapa.
2. O sistema monitora eventos relevantes (como segurança, desastres ou emergências sanitárias).
3. Quando um evento é detectado, um SMS automático é disparado para notificar os cidadãos cadastrados naquela área.
4. O usuário pode gerenciar os alertas — ativar/desativar — ou desativar permanentemente.

---

## 🛠️ Tecnologias utilizadas

- HTML5 + CSS3 – interface responsiva e interativa  
- JavaScript (vanilla) – validações e lógica front-end  
- Node.js + Express – backend para processar eventos e gerenciar usuários  
- Twilio (ou outra API SMS) – envio de mensagens  
- Banco de dados – para armazenar usuários, locais e configurações (ex.: MongoDB, PostgreSQL)

---

## 🚀 Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/marcoexpedito/alerta_cidadao.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd alerta_cidadao
   ```
3. Instale dependências:
   ```bash
   npm install
   ```
4. Crie arquivo de configuração `.env` com:
   ```
   PORT=3000
   TWILIO_ACCOUNT_SID=...
   TWILIO_AUTH_TOKEN=...
   TWILIO_PHONE_NUMBER=...
   MONGO_URI=...
   ```
5. Inicie o servidor:
   ```bash
   npm start
   ```
6. Acesse `http://localhost:3000` e utilize a interface para cadastro e recebimento de alertas.

---

## 🎯 Objetivos de aprendizado

- Integração com API de SMS (como Twilio)
- Configuração de backend em Node.js com Express
- Gerenciamento de banco de dados de usuários e eventos georreferenciados
- Criação de aplicações orientadas a notificações em tempo real

---

## 💡 Possíveis melhorias

- 🔔 Notificações via WhatsApp ou Telegram
- 🌐 Dashboard analítico com mapas e estatísticas
- 🔍 Filtros por tipo de alerta (segurança, saúde, trânsito etc.)
- 🚨 Sistema de webhook para que fontes externas reportem eventos
- 🏙 Suporte a múltiplas cidades e regiões com interface multilocal

---

## 🤝 Contribuições

Contribuições são bem-vindas! Para colaborar:

1. Faça um fork do projeto.  
2. Crie uma branch:  
   `git checkout -b feature/nome-do-recurso`
3. Adicione seu recurso ou correção e faça o commit:  
   `git commit -m "Adiciona ..."`
4. Envie para sua origin:  
   `git push origin feature/nome-do-recurso`
5. Abra um Pull Request detalhando a mudança.

---

## 👨‍⚖️ Licença

Este projeto está disponível sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

Proteja sua comunidade — esteja sempre alerta!

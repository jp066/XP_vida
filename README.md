# XP Vida - Gamificação da Rotina 🎮

**XP Vida** é um sistema de gamificação da rotina, projetado para transformar as tarefas diárias em desafios emocionantes. Os usuários ganham XP ao completar tarefas, avançam de nível e desbloqueiam recompensas. Este projeto é desenvolvido em **Django** para o backend e **React Native** para o frontend.

## 📌 Visão Geral

**XP Vida** permite que os usuários:
- **Complete tarefas** e ganhe XP.
- **Suba de nível** com base no XP acumulado.
- **Desbloqueie recompensas** ao atingir novos níveis.
- **Monitore seu progresso** através de estatísticas e histórico.

## 🛠️ Tecnologias Utilizadas

- **Backend**: Django
- **Banco de Dados**: PostgreSQL (ou SQLite no início)
- **Frontend**: React Native
- **Autenticação**: Firebase Auth ou Django Auth
- **APIs**: Django REST Framework (DRF) para criação de APIs RESTful
- **Notificações**: Firebase Cloud Messaging
- **Hospedagem**: A definir (VPS, Railway, Render, etc.)

## 🚀 Funcionalidades

- **Cadastro/Login de Usuário**  
  Utilização de Firebase Auth ou Django Auth para autenticação de usuários.
  
- **Criação e Gerenciamento de Tarefas**  
  Usuários podem criar tarefas e marcar como concluídas para ganhar XP.

- **Sistema de XP e Níveis**  
  Cada tarefa completada concede uma quantidade específica de XP, e o usuário sobe de nível conforme acumula XP.

- **Recompensas Desbloqueáveis**  
  Usuários podem resgatar recompensas quando atingem certos marcos de XP.

- **Histórico de Progresso**  
  Acompanhe o progresso das tarefas, níveis e recompensas no painel do usuário.

- **Notificações**  
  Notificações por push sobre tarefas pendentes, conquistas e novos níveis.

## 📝 Decisões Iniciais

1. **Backend com Django**  
   A escolha por Django se dá pela robustez e escalabilidade, além de ser uma escolha sólida para APIs RESTful com o Django REST Framework (DRF).
   
2. **Frontend com React Native**  
   O frontend será desenvolvido em React Native, permitindo o desenvolvimento para Android e iOS com uma única base de código.
   
3. **Tema Visual**  
   O tema visual será definido em conjunto com o cliente. Dependendo do orçamento, podemos oferecer opções de personalização de UI.

4. **Orçamento**  
   O orçamento do projeto está em análise. Dependendo dos recursos disponíveis, poderá ser necessário delegar algumas funcionalidades ou ajustar a complexidade do projeto.

## 🧑‍💻 Como Contribuir

Se você está interessado em contribuir com este projeto, siga as instruções abaixo:

### 1. Fork o Repositório
Clique no botão "Fork" no canto superior direito deste repositório para criar uma cópia pessoal.

### 2. Clone o Repositório
Clone seu fork para a máquina local:
```bash
git clone https://github.com/seu-usuario/xp-vida.git
cd xp-vida
3. Crie uma Nova Branch
Crie uma nova branch para suas alterações:

bash
Copiar
Editar
git checkout -b minha-nova-funcionalidade
4. Faça Suas Alterações
Implemente suas melhorias ou correções.

5. Commit e Push
Faça o commit de suas alterações e envie para o repositório remoto:

bash
Copiar
Editar
git add .
git commit -m "Adiciona nova funcionalidade"
git push origin minha-nova-funcionalidade
6. Abra um Pull Request
Abra um pull request para o repositório principal com suas mudanças.

🛠️ Instalação
Backend (Django)
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/xp-vida.git
cd xp-vida
Crie e ative um ambiente virtual:

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate  # Para Windows
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Configure o banco de dados:

bash
Copiar
Editar
python manage.py migrate
Execute o servidor:

bash
Copiar
Editar
python manage.py runserver
Frontend (React Native)
Clone o repositório do frontend (a ser fornecido pelo responsável pelo frontend).

Instale as dependências:

bash
Copiar
Editar
npm install
Execute o aplicativo:

bash
Copiar
Editar
npm start
Abra o aplicativo em um dispositivo ou simulador para testar.

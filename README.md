# 🍔 Delivery Online

## 📌 Sobre o Projeto

O **Delivery Online** é um sistema completo desenvolvido para facilitar a gestão de pedidos em lanchonetes, restaurantes e outros estabelecimentos gastronômicos.  

Tendo em vista o **aumento constante das taxas cobradas por aplicativos de delivery**, tanto para **pequenos empreendedores quanto para motoboys**, este projeto foi criado com o objetivo de oferecer uma **alternativa mais acessível, justa e eficiente**.

A proposta é entregar o **máximo de funcionalidades que um cardápio online deveria ter**, sem custos abusivos — promovendo autonomia para os estabelecimentos e democratizando o acesso a soluções tecnológicas de qualidade para todos os tipos de negócio, independentemente do tamanho.

Além disso, o sistema conta com recursos robustos tanto para **clientes**, como pedidos online e programas de fidelidade, quanto para **administradores**, com ferramentas completas de gestão de produtos, pedidos e personalização da plataforma.

<table>
  <tr>
    <th>Cliente</th>
    <th>Administrador</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c9be3994-c276-4eab-b007-5d9bf7a9b488" width="400"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/73d1dd6b-7071-4393-9fc9-17d47b1f3eb2" width="400"/>
    </td>
  </tr>
</table>

## 🎯 Funcionalidades

### 🛂 Para Clientes
✅ **Pedidos online**  
✅ **Catálogo intuitivo**  
✅ **Cupom de desconto**  
✅ **Loja da fidelidade**  
✅ **Carrinho de compras**  
✅ **Status do pedido em tempo real**  
✅ **Programa de fidelidade**  
✅ **Roleta de descontos**  
✅ **Avaliação de produtos**  
✅ **Histórico de pedidos**  
✅ **Múltiplos endereços cadastrados**  
✅ **Login e registro de novos clientes**  
✅ **Convidar Amigos com seu codico para ganhar pontos**  
✅ **Avaliar produtos para ganhar pontos**  
✅ **Comprando no estabelecimento para ganhar pontos** 
✅ **Retornar ao Carrinho na Finalização** 

---

### 🏢 Para Administradores

#### ⚙️ Configuração da Home
- Personalização de cores do software
- Personalização do nome do estabelecimento
- Personalização da categoria do estabelecimento (exemplo: pizza)
- Personalização do pedido mínimo
- Personalização do valor da taxa de entrega
- Personalização do tempo mínimo e máximo de entrega
- Personalização da logo
- Personalização do banner
- Personalização da  Localização do estabelecimento (Para busca do Produto)

#### 🔧 Habilitar e desabilitar funcionalidades
- Roleta de descontos
- Loja de Pontos
- Loja da fidelidade
- Avaliação de produtos
- Pagamento por Pix

#### 🛆 Lista de produtos
- Buscar produto por nome
- Colocar produto em promoção
- Excluir produto
- Alterar limites do Açaí
- Alterar preços de produtos e pizzas
- Visualização de todos os produtos cadastrados

✅ **Adicionar Produto**
- Adicionar novos produtos
- Criar combos personalizados (agrupando produtos para formar combos)

#### 🏩 Gestão do Estabelecimento
- Abrir e fechar estabelecimento

#### 📋 Gestão de Pedidos
- Notificação de chegada de pedidos
- Visualização de todas as informações do pedido
- Atualização automática para o usuário ao colocar o pedido em preparo
- Atualização automática para o usuário ao marcar pedido como pronto
- Impressão de notas fiscais
- Cancelamento de pedidos

#### 📋 Gestão de Historico de pedidos
- Visualizar historico de Pedidos
- Buscar Pedido Por Nome
- Exportar os Pedidos (PDF)


---

## 🎖️ Programa de Fidelidade
O programa de fidelidade funciona através de um sistema de pontos:

- **Ganho de Pontos:**
  - Comprando no estabelecimento
  - Avaliando produtos
  - Convidando novos usuários com seu código de convite
- **Uso dos Pontos:**
  - Podem ser usados na loja de fidelidade para trocar por benefícios
- **Ranks do Programa:**
  - 🥇 **Bronze** → Pode trocar pontos por mais tickets para a roleta
  - 🥈 **Prata** → Pode comprar descontos diretamente sem depender da sorte da roleta
  - 🥉 **Ouro** → Pode resgatar prêmios físicos, como produtos do estabelecimento

## 🔧 Configuração da Fidelidade

### **Gerenciamento de tickets para a roleta:**
- Gerenciamento de tickets para a roleta
- Controle de tickets dos usuários

### **Configuração da loja da fidelidade:**
- Adição de tickets para a loja Bronze
- Adição de cupons para a loja Prata
- Adição de itens físicos para a loja Ouro

---

## 🚀 Tecnologias Utilizadas
O projeto foi desenvolvido utilizando as seguintes tecnologias:

🔹 **ReactTS** ⚛️  
🔹 **TailwindCSS** 🎨  
🔹 **Styled-Components** 💅  
🔹 **TypeScript** 📝  
🔹 **CSS** 🎨  
🔹 **Firebase** 🔥  
🔹 **Git & GitHub** 🌍  

---
## 🔐 Configuração do Firebase

Antes de rodar o projeto, é necessário configurar as **chaves do Firebase**, pois o sistema depende dos serviços de autenticação, banco de dados e hospedagem fornecidos pelo Firebase.

---

### 📁 1. Crie um Projeto no Firebase

1. Acesse o [Firebase Console](https://console.firebase.google.com/)
2. Clique em **"Adicionar projeto"**
3. Siga os passos para criar o projeto (você pode pular a ativação do Google Analytics)
4. Após a criação, vá em **Configurações do projeto > Contas de serviço** para SDK Admin (se necessário) ou siga os passos abaixo para integração Web

---

### 🔧 2. Configure seu App Web

1. Na visão geral do projeto, clique no ícone **Web (</>)**
2. Dê um nome para o app e clique em **Registrar app**
3. Copie o trecho de código de configuração que será exibido, parecido com este:

```ts
const firebaseConfig = {
  apiKey: "SUA_API_KEY",
  authDomain: "SEU_DOMINIO.firebaseapp.com",
  projectId: "SEU_PROJECT_ID",
  storageBucket: "SEU_BUCKET.appspot.com",
  messagingSenderId: "SEU_SENDER_ID",
  appId: "SUA_APP_ID"
};
e  Substitua no
/services/firebase.tsx


```
## 🛠 Instalação
Siga os passos abaixo para instalar e rodar o projeto localmente:

1⃣ Clone o repositório:
```bash
git clone https://github.com/herobruno/lanchonete.git
```
2⃣ Acesse o diretório do projeto:
```bash
cd seurepositorio
```
3⃣ Instale as dependências:
```bash
npm install
```
Ou, se estiver usando Yarn:
```bash
yarn install
```
4⃣ Inicie o servidor de desenvolvimento:
```bash
npm run dev
```
Ou, com Yarn:
```bash
yarn dev
```
5⃣ Abra o navegador e acesse:
```bash
http://localhost:4000
```
Agora o projeto está rodando localmente! 🎉

---


## 👨‍💻 Desenvolvedores

Este projeto foi desenvolvido por:

- **Bruno** - [GitHub](https://github.com/herobruno)
- **Alex** - [GitHub](https://github.com/AlexCarneiroo)

---

## 🏢 Licença

Este software é licenciado e distribuído sob os direitos da empresa **Logarithm**.

© 2025 Logarithm. Todos os direitos reservados.




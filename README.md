# SOLUTECH

Aplicativo mobile para empresas e comércios anunciarem produtos e resíduos que seriam descartados, facilitando negociações e redução de desperdícios.

![Logo ou Captura de Tela]() <!-- Adicionar uma imagem posteriormente -->

---

## 🚀 Funcionalidades
- **Autenticação**: Cadastro e login de usuários.
- **Gestão de Itens**: Cadastro, consulta e interesse em itens.
- **Negociações**: Acompanhamento de itens com interesse.
- **Dashboard**: Resumo estatístico de atividades.

---

## 📂 Organização do Projeto
```
/src
│-- assets/         # Ícones e imagens
│-- components/     # Componentes reutilizáveis (Header, ItemList, etc.)
│-- navigation/     # Configuração de navegação (AppNavigator, MainTabs)
│-- screens/        # Telas do app (Login, CadastroItem, ConsultaItens, etc.)
│-- services/       # Lógica do banco de dados (database.js)
```

---

## ⚙️ Dependências
Principais bibliotecas utilizadas:
- `expo`: Framework para desenvolvimento mobile.
- `react-native-sqlite-storage`: Banco de dados SQLite.
- `@react-navigation/native`: Navegação entre telas.
- `react-native-paper`: Componentes UI estilizados.

### Instalação
```bash
npm install @react-navigation/native @react-navigation/stack @react-navigation/bottom-tabs react-native-sqlite-storage react-native-paper
```

---

## 🔧 Instalação e Execução

### Clone o repositório:
```bash
git clone https://github.com/seu-usuario/solutech-app.git
cd solutech-app
```

### Instale as dependências:
```bash
npm install
```

### Inicie o app:
```bash
npx expo start
```

---

## 📋 Como o Sistema Funciona?

### Login/Cadastro
- Usuários se autenticam para acessar o sistema.

### Cadastro de Itens
- Informe nome, descrição e data do item a ser anunciado.

### Consulta de Itens
- Explore itens disponíveis e demonstre interesse.

### Negociações
- Acompanhe itens onde você manifestou interesse.

### Dashboard
- Visualize métricas como "Itens Cadastrados" e "Negociações em Andamento".

---

## 🛠️ Arquitetura Técnica
- **Front-end**: React Native (Expo) + React Navigation.
- **Back-end**: SQLite (banco de dados local).
- **Estilização**: React Native Paper para componentes prontos.

---

## 📄 Notas
- Para debug do banco de dados, use o DB Browser for SQLite (siga o guia no Wiki).
- Dados são persistidos localmente no dispositivo do usuário.

---

## 📝 Licença
Este projeto está sob a licença MIT. Veja `LICENSE` para detalhes.

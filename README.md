# ✈️ Voe - Plataforma de Reservas de Passagens Aéreas

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-13-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.8.4-3178C6?style=for-the-badge&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.2.1-38B2AC?style=for-the-badge&logo=tailwind-css)
![Material-UI](https://img.shields.io/badge/Material--UI-5.10.12-0081CB?style=for-the-badge&logo=mui)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

</div>

---

## 🎯 Sobre o Projeto

**Voe** é uma plataforma moderna e intuitiva para reservas de passagens aéreas, desenvolvida com as melhores tecnologias do mercado. O projeto oferece uma experiência de usuário excepcional, combinando design responsivo com funcionalidades avançadas de busca e reserva.

### ✨ Principais Características

- 🔍 **Busca Inteligente**: Interface intuitiva para busca de voos
- 📱 **Design Responsivo**: Funciona perfeitamente em todos os dispositivos
- 🎨 **UI/UX Moderna**: Interface elegante com Material-UI e Tailwind CSS
- ⚡ **Performance Otimizada**: Desenvolvido com Next.js para máxima velocidade
- 🔐 **Sistema de Autenticação**: Login seguro para usuários
- 💳 **Checkout Integrado**: Processo de pagamento simplificado
- ♿ **Acessibilidade**: Suporte ao VLibras para inclusão

---

## 🚀 Tecnologias Utilizadas

### Frontend
- **[Next.js](https://nextjs.org/)** - Framework React para produção
- **[React 18](https://reactjs.org/)** - Biblioteca JavaScript para interfaces
- **[TypeScript](https://www.typescriptlang.org/)** - Superset JavaScript tipado
- **[Material-UI](https://mui.com/)** - Biblioteca de componentes React
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário

### Acessibilidade
- **[VLibras](https://www.gov.br/governodigital/pt-br/vlibras)** - Tradutor automático para Libras

### Desenvolvimento
- **[PostCSS](https://postcss.org/)** - Ferramenta para transformar CSS
- **[Autoprefixer](https://autoprefixer.github.io/)** - Adiciona prefixos CSS automaticamente

---

## 📁 Estrutura do Projeto

```
ihc-voe/
├── 📁 components/          # Componentes reutilizáveis
│   ├── footer.tsx         # Rodapé da aplicação
│   ├── header.tsx         # Cabeçalho da aplicação
│   ├── mainSearch.tsx     # Componente principal de busca
│   └── ticketCard.tsx     # Card de passagem
├── 📁 pages/              # Páginas da aplicação (Next.js)
│   ├── _app.tsx          # Configuração global
│   ├── index.tsx         # Página inicial
│   ├── login.tsx         # Página de login
│   ├── ticket-list.tsx   # Lista de passagens
│   ├── checkout.tsx      # Página de checkout
│   └── waitingPayment.tsx # Aguardando pagamento
├── 📁 public/             # Arquivos estáticos
│   ├── logo.svg          # Logo da aplicação
│   ├── carousel.png      # Imagens do carrossel
│   └── ...               # Outras imagens
├── 📁 styles/            # Estilos CSS
│   ├── globals.css       # Estilos globais
│   └── checkout.css      # Estilos específicos do checkout
└── 📄 package.json       # Dependências e scripts
```

---

## 🛠️ Instalação e Configuração

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/)

### Passos para Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/MuketaUeda/ihc-voe.git
   cd ihc-voe
   ```

2. **Instale as dependências**
   ```bash
   yarn install
   # ou
   npm install
   ```

3. **Execute o projeto em modo de desenvolvimento**
   ```bash
   yarn dev
   # ou
   npm run dev
   ```

4. **Acesse a aplicação**
   ```
   http://localhost:3000
   ```

### Scripts Disponíveis

```bash
# Desenvolvimento
yarn dev          # Inicia o servidor de desenvolvimento

# Produção
yarn build        # Constrói a aplicação para produção
yarn start        # Inicia o servidor de produção
```

---

## 🎨 Funcionalidades

### 🏠 Página Inicial
- **Busca de Voos**: Interface intuitiva para pesquisa de passagens
- **Destinos em Destaque**: Exibição de ofertas especiais
- **Newsletter**: Cadastro para receber ofertas exclusivas

### 🔐 Sistema de Autenticação
- **Login**: Acesso seguro à conta do usuário
- **Cadastro**: Criação de nova conta

### 🎫 Listagem de Passagens
- **Filtros Avançados**: Busca por preço, horário, companhia aérea
- **Comparação**: Visualização lado a lado de diferentes opções

### 💳 Checkout
- **Resumo da Compra**: Detalhes da passagem selecionada
- **Dados do Passageiro**: Formulário para informações pessoais
- **Pagamento**: Integração com gateway de pagamento

### ⏳ Aguardando Pagamento
- **Status da Transação**: Acompanhamento em tempo real
- **Feedback Visual**: Indicadores de progresso

---

## 🎯 Funcionalidades Principais

| Funcionalidade | Descrição | Status |
|----------------|-----------|--------|
| 🔍 Busca de Voos | Interface completa para pesquisa de passagens | ✅ Implementado |
| 📱 Design Responsivo | Adaptação para mobile, tablet e desktop | ✅ Implementado |
| 🔐 Autenticação | Sistema de login e cadastro | ✅ Implementado |
| 🎫 Listagem | Exibição de resultados de busca | ✅ Implementado |
| 💳 Checkout | Processo de finalização de compra | ✅ Implementado |
| ♿ Acessibilidade | Suporte ao VLibras | ✅ Implementado |
| 🎨 UI Moderna | Interface com Material-UI e Tailwind | ✅ Implementado |

---

## 🚀 Deploy

### Vercel (Recomendado)
```bash
# Instale o Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Outras Plataformas
- **Netlify**: Compatível com Next.js
- **AWS Amplify**: Deploy automático
- **Heroku**: Configuração manual necessária

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. **Fork** o projeto
2. **Crie** uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. **Abra** um Pull Request

### 📋 Padrões de Código

- Use **TypeScript** para todos os novos arquivos
- Siga as **convenções** do ESLint e Prettier
- Mantenha a **cobertura de testes** acima de 80%
- Documente **novas funcionalidades** com JSDoc

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👥 Equipe

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MuketaUeda">
        <img src="https://avatars.githubusercontent.com/MuketaUeda" width="100px;" alt=""/>
        <br />
        <sub><b>Seu Nome</b></sub>
      </a>
      <br />
      <sub>Desenvolvedor Full Stack</sub>
    </td>
  </tr>
</table>

---

## 🙏 Agradecimentos

- [Next.js](https://nextjs.org/) pela excelente documentação
- [Material-UI](https://mui.com/) pelos componentes incríveis
- [Tailwind CSS](https://tailwindcss.com/) pelo framework CSS
- [VLibras](https://www.gov.br/governodigital/pt-br/vlibras) pela inclusão digital

---

<div align="center">

**⭐ Se este projeto te ajudou, considere dar uma estrela!**

[![GitHub stars](https://img.shields.io/github/stars/MuketaUeda/ihc-voe?style=social)](https://github.com/MuketaUeda/ihc-voe/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/MuketaUeda/ihc-voe?style=social)](https://github.com/MuketaUeda/ihc-voe/network)
[![GitHub issues](https://img.shields.io/github/issues/MuketaUeda/ihc-voe)](https://github.com/MuketaUeda/ihc-voe/issues)

</div>

# 🌟 Soares Modas - E-commerce Premium

Uma plataforma de e-commerce elegante para a Soares Modas, desenvolvida com React, TypeScript e design premium em dourado e preto.

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Preparar o Repositório

1. Crie um novo repositório no GitHub
2. Faça upload de todos os arquivos do projeto para o repositório
3. Certifique-se de que o arquivo `.github/workflows/deploy.yml` está presente

### Passo 2: Configurar GitHub Pages

1. Vá nas **Settings** do seu repositório
2. Navegue até **Pages** no menu lateral
3. Em **Source**, selecione **GitHub Actions**
4. O workflow será executado automaticamente quando você fizer push para a branch `main`

### Passo 3: Configurações Importantes

#### Para o Site Estático (Versão Simples)
- O arquivo `public/index.html` contém uma versão estática completa
- Funciona perfeitamente no GitHub Pages sem configurações adicionais
- Inclui integração com WhatsApp para pedidos

#### Para o Site Dinâmico (Versão Completa)
- Requer ajustes para funcionar como SPA no GitHub Pages
- Adicione um arquivo `public/404.html` que redireciona para `index.html`
- Configure o roteamento para funcionar sem servidor

### Passo 4: Personalizar WhatsApp

No arquivo `public/index.html`, substitua `XXXXXXXXXXXXXX` pelo ID do seu chat do WhatsApp:

```javascript
const whatsappUrl = `https://wa.me/message/SEU_ID_WHATSAPP_AQUI?text=${encodeURIComponent(message)}`;
```

### Passo 5: Acessar o Site

Após o deploy, seu site estará disponível em:
```
https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO
```

## 🎨 Características

- **Design Premium**: Tema dourado e preto elegante
- **Responsivo**: Funciona perfeitamente em mobile e desktop
- **WhatsApp Integration**: Botões diretos para compra via WhatsApp
- **SEO Otimizado**: Meta tags e estrutura semântica
- **Performance**: Carregamento rápido e otimizado

## 📱 Funcionalidades

- **Catálogo de Produtos**: Exibição elegante dos produtos
- **Carrinho de Compras**: Sistema de carrinho integrado
- **WhatsApp Checkout**: Finalização de pedidos via WhatsApp
- **Localização**: Endereço e contato da loja
- **Administração**: Painel admin para gerenciar produtos

## 🛠️ Tecnologias

- React.js
- TypeScript
- Tailwind CSS
- Vite
- Drizzle ORM
- PostgreSQL

## 📞 Contato da Loja

**Soares Modas**
- 📍 Rua dos Carmelitas, 62, casa B - Dom Avelar (Pirajá), Salvador - BA
- 📱 WhatsApp: [Configurar no código]
- 📷 Instagram: @soaresmodas2

## 🔧 Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Build para produção
npm run build
```

## 📝 Notas Importantes

1. **WhatsApp**: Configure o número correto no arquivo HTML
2. **Domínio Personalizado**: Você pode configurar um domínio customizado nas configurações do GitHub Pages
3. **SSL**: O GitHub Pages fornece SSL automático
4. **Atualizações**: Qualquer push para a branch main atualiza o site automaticamente

---

✨ **Soares Modas** - Elegância e qualidade em cada peça!
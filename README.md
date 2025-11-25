# 🍔 BetoJou - Hamburgueria Artesanal

Uma loja de hambúrgueres artesanais online com carrinho de compras integrado ao WhatsApp.

## 📋 Sobre o Projeto

**BetoJou** é um website moderno e responsivo para uma hamburgueria artesanal. O site oferece:
- Cardápio dinâmico com filtro por categorias
- Carrinho de compras interativo
- Integração direta com WhatsApp para pedidos
- Design moderno com tema escuro
- Interface intuitiva e responsiva

## ✨ Funcionalidades

### 🛒 Carrinho de Compras
- Adicionar e remover itens
- Controlar quantidade de cada produto
- Visualizar total do pedido
- Carrinho deslizante na lateral da tela

### 🍽️ Cardápio
- **Burgers**: Beto Classic, Jou Bacon, Smash Duplo
- **Acompanhamentos**: Batata Rústica, Onion Rings
- **Bebidas**: Coca-Cola

### 🔍 Filtros
- Todos os produtos
- Apenas burgers
- Apenas acompanhamentos
- Apenas bebidas

### 📋 Modal de Checkout
- Campo de forma de pagamento (dropdown com opções)
- Campo de endereço de entrega (textarea)
- Validação de campos obrigatórios
- Envio automático do pedido via WhatsApp com todas as informações

### 📲 Integração WhatsApp
- Envio automático do pedido via WhatsApp
- Resumo dos itens e total
- Campos para forma de pagamento e endereço

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do site
- **CSS3**: Estilos e responsividade
- **JavaScript**: Lógica interativa
- **Phosphor Icons**: Ícones modernos
- **Google Fonts**: Tipografia (Oswald e Poppins)
- **Unsplash API**: Imagens de produtos

## 🎨 Design

### Paleta de Cores
- **Primária**: `#ff6b00` (Laranja)
- **Fundo Escuro**: `#121212`
- **Cards**: `#1e1e1e`
- **Texto Principal**: `#f5f5f5`
- **Texto Secundário**: `#a0a0a0`
- **Sucesso/WhatsApp**: `#25d366`

### Fontes
- **Oswald**: Títulos (Marca)
- **Poppins**: Corpo do texto

## 📁 Estrutura de Arquivos

```
BetoJou Hamburgueria Artesanal/
├── index.html          # Arquivo principal (HTML + CSS + JavaScript)
├── index.js            # Arquivo JavaScript (referenciado, pode ser separado)
├── index.css           # Arquivo CSS (referenciado, pode ser separado)
└── README.md          # Este arquivo
```

## 🚀 Como Usar

### 1. Abrir o Site
Simplesmente abra o arquivo `index.html` em um navegador web.

### 2. Navegar pelo Menu
- Use os filtros para visualizar categorias específicas
- Clique em "VER CARDÁPIO" ou na seção de menu

### 3. Adicionar Itens ao Carrinho
- Clique no ícone de "+" em cada produto
- O item será adicionado automaticamente ao carrinho

### 4. Gerenciar Carrinho
- Clique no ícone do carrinho (topo direito) para visualizar
- Use "+" e "-" para aumentar ou diminuir quantidades
- Clique no "X" para fechar o carrinho

### 5. Finalizar Pedido
- Clique em "FINALIZAR PEDIDO"
- Preencha o modal com:
  - **Forma de Pagamento**: Selecione entre Dinheiro, Débito, Crédito, PIX ou Outro
  - **Endereço de Entrega**: Digite o endereço completo
- Clique em "Enviar Pedido"
- Será aberto uma conversa no WhatsApp com o resumo completo incluindo forma de pagamento e endereço

## ⚙️ Configuração

### Alterar Número do WhatsApp
Localize a linha no JavaScript e substitua o número:
```javascript
window.open(`https://wa.me/5511999999999?text=${encodedMessage}`, '_blank');
```
Altere `5511999999999` para o número desejado (com código do país + DDD + número).

### Adicionar Novos Produtos
No array `products` do JavaScript, adicione um novo objeto:
```javascript
{
  id: 7,
  name: "Nome do Produto",
  price: 29.90,
  desc: "Descrição do produto",
  category: "burger", // "burger", "side" ou "drink"
  image: "URL_DA_IMAGEM"
}
```

## 📱 Responsividade

O site é totalmente responsivo para:
- 📱 Dispositivos móveis (até 768px)
- 💻 Tablets (768px - 1024px)
- 🖥️ Desktop (acima de 1024px)

## 🎯 Segmentos do Site

### Header
- Logo com ícone de hambúrguer
- Navegação (Home, Cardápio, Sobre)
- Botão do carrinho com contador

### Hero Section
- Background com imagem de hambúrguer
- Título chamativo: "MORDIDAS QUE TRANSFORMAM SEU DIA"
- Botão de call-to-action (CTA)

### Menu Section
- Título e descrição
- Botões de filtro
- Grid de produtos com cards

### Cart Sidebar
- Lista de itens adicionados
- Controles de quantidade
- Total do pedido
- Botão de checkout WhatsApp

### Modal de Checkout
- Formulário com campos obrigatórios
- Dropdown de formas de pagamento (Dinheiro, Débito, Crédito, PIX, Outro)
- Textarea para endereço de entrega
- Validação de preenchimento
- Botões de cancelar ou confirmar

### Footer
- Copyright e informação da marca

## 🔧 Customizações Possíveis

1. **Cores**: Altere as variáveis CSS (`:root`)
2. **Tipografia**: Mude as fontes do Google Fonts
3. **Imagens**: Substitua as URLs das imagens
4. **Preços**: Modifique os valores no array de produtos
5. **Textos**: Personalize mensagens e descrições

## 🌐 Hospedagem

Para hospedar o site:
1. GitHub Pages (gratuito)
2. Vercel (gratuito)
3. Netlify (gratuito)
4. Servidor próprio ou alugado
5. Serviços de hospedagem tradicionais

## 📝 Licença

© 2024 Hamburgueria BetoJou. Todos os direitos reservados.

---

**Desenvolvido com 🧡 e muito bacon!**

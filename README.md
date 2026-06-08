Sistema web para controle de vendas e caixa do mini mercado do **Encontro de Jovens com Cristo (EJC)**.

Desenvolvido para substituir o controle manual em caderno, tornando o registro de vendas mais rápido e organizado durante o evento.

---

## ✨ Funcionalidades

- **Cadastro de produtos** — registre nome e preço de todos os itens vendidos
- **Carrinho de compras** — adicione múltiplos produtos em uma única venda
- **Formas de pagamento** — Dinheiro, Pix, Cartão de Crédito e Cartão de Débito
- **Resumo do caixa** — total geral e breakdown por forma de pagamento
- **Cancelamento de venda** — remova qualquer venda registrada
- **Exportar PDF** — relatório formatado pronto para impressão
- **Exportar XLSX** — planilha Excel com resumo e detalhamento das vendas
- **Dados persistidos** — tudo salvo automaticamente no dispositivo (localStorage)

---

## 🚀 Como usar

1. Abra o arquivo `index.html` no navegador (Chrome recomendado)
2. Vá em **Produtos** e cadastre os itens com nome e preço
3. Na aba **Venda**, toque nos produtos para montar o pedido
4. Ajuste as quantidades no carrinho, escolha a forma de pagamento e clique em **Registrar Venda**
5. Acompanhe o caixa em tempo real na aba **Caixa**
6. Ao final do evento, exporte o relatório em PDF ou XLSX

---

## 📱 Acesso no celular

O sistema é responsivo e funciona em qualquer dispositivo. Para usar no celular:

1. Envie o arquivo `index.html` para o celular (via WhatsApp, e-mail, etc.)
2. Abra com o navegador Chrome
3. Opcional: no Chrome, toque em **⋮ → Adicionar à tela inicial** para instalar como app

---

## 📤 Exportação de relatórios

| Formato | Como funciona | Requer internet? |
|---------|--------------|-----------------|
| PDF | Abre janela de impressão do browser — escolha "Salvar como PDF" | Não |
| XLSX | Baixa arquivo Excel com duas abas: Resumo e Vendas | Sim (SheetJS via CDN) |

---

## 🗂️ Estrutura do arquivo XLSX

**Aba Resumo**
- Total geral do caixa
- Total por forma de pagamento (Dinheiro, Pix, Crédito, Débito)

**Aba Vendas**
- Lista completa de todas as vendas com hora, produto(s), forma de pagamento e valor

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** — puro, sem frameworks
- **localStorage** — persistência de dados no navegador
- **SheetJS (xlsx.js)** — geração de arquivos Excel (carregado via CDN)

---

## 📁 Estrutura do projeto

```
Sistema-mini-mercado/
└── index.html    # Aplicativo completo em arquivo único
```

---

## ⚠️ Observações

- Os dados ficam salvos **somente no dispositivo** onde o app foi aberto
- Ao clicar em **Fechar Caixa / Zerar**, todas as vendas são apagadas permanentemente
- Para usar em múltiplos dispositivos simultaneamente, seria necessário um servidor back-end

---

## 👤 Autor

Desenvolvido para o mini mercado do **EJC — Encontro de Jovens com Cristo**.

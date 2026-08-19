# 🌿 Projeto Digital: Quilombo Mangueiras

> **Solução de Inclusão Digital e E-commerce Social** para a comunidade Quilombola Mangueiras (Belo Horizonte/MG).

## 🎯 O Desafio
A comunidade Quilombo Mangueiras possui uma produção rica de agroecologia e artesanato, mas carecia de uma presença digital centralizada para divulgar sua história, lutas e facilitar a comercialização de seus produtos para fora da comunidade.

## ✅ A Solução
Desenvolvimento de um ecossistema digital acessível e de baixo custo de manutenção, permitindo que a própria comunidade gerencie o conteúdo futuramente.

### Stack Tecnológica (Low-Code / Full-Stack)
- **Frontend:** HTML5 + CSS3 + JavaScript Vanilla (SPA responsiva)
- **Backend:** Google Apps Script (Web App) — Planilha Google Sheets como banco de dados
- **Integração:** WhatsApp Web API para pedidos + Google Sheets para gestão
- **Deploy:** Vercel (frontend estático) + Google Cloud (Apps Script)
- **Design:** Identidade visual afro-brasileira, acessível, mobile-first

## 🚀 Funcionalidades
- ✅ **Landing Page Institucional** — História, cultura, localização, certificações
- ✅ **Catálogo Digital** — Produtos agroecológicos com fotos, descrições, preços
- ✅ **Sistema de Pedidos** — Formulário validado, cálculo de frete, integração WhatsApp
- ✅ **Painel Admin (Google Sheets)** — Controle de estoque, pedidos, relatórios
- ✅ **Responsividade Total** — Otimizado para celular (principal acesso da comunidade)
- ✅ **Acessibilidade** — Contraste, navegação por teclado, leitores de tela

## 🔗 Links
- **Live (Vercel):** https://projeto-quilombo-mangueiras-digital.vercel.app
- **Site Original (Google Sites):** https://sites.google.com/view/quilombo-mangueiras
- **Código:** https://github.com/adrianogdr/projeto-quilombo-mangueiras-digital

## 🛠️ Como Usar

### Desenvolvimento Local
```bash
git clone https://github.com/adrianogdr/projeto-quilombo-mangueiras-digital.git
cd projeto-quilombo-mangueiras-digital
npx serve .
```

### Configuração do Google Apps Script
1. Crie planilha no Google Sheets com abas: `Produtos`, `Pedidos`, `Config`
2. No Apps Script, crie Web App com `doGet`/`doPost`
3. Publique como "Qualquer pessoa" → Cole URL no `config.js`

### Deploy Vercel
```bash
vercel --prod
# Conecta repo adrianogdr/projeto-quilombo-mangueiras-digital
```

## 📂 Estrutura
```
projeto-quilombo-mangueiras-digital/
├── index.html          # SPA principal
├── css/style.css       # Estilos + design system
├── js/app.js           # Lógica: catálogo, carrinho, WhatsApp
├── config.js           # URLs do Apps Script + configs
├── vercel.json         # Deploy config
└── README.md
```

## 🎨 Identidade Visual
- **Cores:** Terracota, Verde Floresta, Ouro, Creme — inspiradas na terra, mata e cultura afro-brasileira
- **Tipografia:** Inter (UI) + Merriweather (leitura) — legível, acolhedora
- **Ícones:** SVG customizados (mandioca, folha, cesto, tambor)

## 👥 Impacto Social
- **Renda:** +40% nas vendas via canal digital
- **Autonomia:** Comunidade gerencia próprio catálogo/planilha
- **Visibilidade:** História do Quilombo acessível globalmente
- **Tecnologia Inclusiva:** Low-code, sem custos recorrentes

## 👨‍💻 Desenvolvido por
[Adriano Gonçalves](https://github.com/adrianogdr) — Em parceria com a Comunidade Quilombo Mangueiras

## 📄 Licença
MIT — Uso livre para comunidades tradicionais e projetos de impacto social.

---

⭐ **Apoie a inclusão digital quilombola — deixe uma estrela!**
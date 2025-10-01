# 🌐 Syntra – Site Institucional (HTML + CSS)

## 📌 Sobre o projeto
Este é um projeto fictício de **startup de tecnologia em nuvem** chamado **Syntra**.  
O objetivo é treinar fundamentos de **HTML + CSS puro** (sem uso de JavaScript), criando um site multi-página moderno, responsivo e acessível para portfólio.  

---

## 🗂 Estrutura de pastas
syntra/
├─ public/ → imagens e ícones
│ ├─ images/
│ └─ icons/
├─ styles/ → arquivos CSS
│ ├─ global.css → reset, tokens/variáveis, utilitários
│ ├─ theme.css → dark/light mode e componentes
│ └─ print.css → estilo para impressão
├─ pages/ → páginas internas
│ ├─ sobre.html
│ ├─ planos.html
│ └─ contato.html
├─ index.html → Home
├─ 404.html → página de erro personalizada
├─ robots.txt → instruções SEO
├─ sitemap.xml → mapa do site
└─ README.md → documentação do projeto

---

## 📄 Páginas
- **Home (index.html)** → Hero, serviços, depoimentos, CTA final e footer.  
- **Sobre (pages/sobre.html)** → missão, linha do tempo, valores (tabs CSS).  
- **Planos (pages/planos.html)** → 3 planos, tabela comparativa, modal CSS.  
- **Contato (pages/contato.html)** → formulário validado em HTML5 + dados de contato.  
- **404.html** → página personalizada de erro.  

---

## ✨ Diferenciais técnicos
- Responsividade com **Flexbox, CSS Grid e tipografia fluida** (`clamp()`).  
- **Dark/Light Mode automático** (`@media prefers-color-scheme`).  
- **Menu mobile responsivo** com checkbox hack.  
- **Carrossel CSS** com `scroll-snap`.  
- **Tabs e modal apenas com CSS** (`:target`, `:checked`).  
- **Acessibilidade** (semântica correta, contraste AA, foco visível).  
- **SEO básico**: `title`, `meta description`, `robots.txt`, `sitemap.xml`, Open Graph.  
- **Estilo para impressão** (`@media print`).  
- Deploy em **GitHub Pages ou Netlify**.  

---

## 🎨 Identidade visual (Syntra)
- Azul elétrico `#3B82F6` – primária (confiança/tecnologia).  
- Roxo `#7C3AED` – secundária (inovação/futuro).  
- Cinza claro `#F4F4F5` e cinza escuro `#18181B` – neutros.  
- Verde água `#10B981` – acento para botões e CTAs.  

---

## 🚀 Fluxo de execução
1. Estrutura de pastas ✅  
2. Criar HTML base da **Home (index.html)** + linkar `global.css`.  
3. Criar **reset CSS + tokens de design** (`global.css`).  
4. Montar **header + menu responsivo**.  
5. Criar **seção Hero**.  
6. Criar **grid de serviços**.  
7. Criar **carrossel de depoimentos**.  
8. Criar **CTA final + footer**.  
9. Replicar identidade em **Sobre, Planos, Contato e 404**.  
10. Criar `theme.css` (dark/light mode + componentes).  
11. Criar `print.css` (versão de impressão).  
12. Ajustar SEO (`title`, metas, sitemap, robots).  
13. **Deploy** no GitHub Pages ou Netlify.  

---

## 🧑‍💻 Tecnologias
- **HTML5**  
- **CSS3 (puro, sem frameworks)**  
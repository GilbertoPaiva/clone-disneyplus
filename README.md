# Landing Page - O Homem da Terra

Landing page para o filme "O Homem da Terra" (The Man from Earth), criada como projeto educacional demonstrando boas práticas de desenvolvimento web.

## 📖 Sobre o Projeto

Este projeto é uma landing page responsiva para o filme de ficção científica "O Homem da Terra" (2007). A página foi desenvolvida com foco em:

- Design responsivo e mobile-first
- Uso de SASS para estilização
- JavaScript vanilla para interatividade
- Build automatizado com Gulp
- Placeholder images com proporções corretas para substituição futura

## 🎬 Sobre o Filme

"O Homem da Terra" é um filme de ficção científica filosófico dirigido por Richard Schenkman. A história acompanha John Oldman, um professor universitário que revela aos seus colegas que é um Cro-Magnon de 14.000 anos de idade.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **SASS/SCSS** - Pré-processador CSS
- **JavaScript** - Interatividade (vanilla JS)
- **Gulp** - Automatização de tarefas
  - Compilação de SASS
  - Minificação de JavaScript
  - Otimização de imagens

## 📁 Estrutura do Projeto

```
.
├── src/
│   ├── images/          # Imagens originais
│   ├── scripts/         # Arquivos JavaScript
│   │   └── main.js
│   └── styles/          # Arquivos SCSS
│       ├── _header.scss
│       ├── _hero.scss
│       ├── _shows.scss
│       ├── _plans.scss
│       ├── _available-devices.scss
│       ├── _faq.scss
│       ├── _footer.scss
│       ├── _variaveis.scss
│       └── main.scss
├── dist/                # Arquivos compilados (gerado automaticamente)
├── assets/              # Recursos estáticos (fontes, etc)
├── index.html           # Página principal
├── gulpfile.js          # Configuração do Gulp
├── package.json         # Dependências do projeto
└── README.md            # Este arquivo
```

## 🛠️ Instalação e Uso

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm (geralmente vem com o Node.js)

### Passos para instalação

1. Clone o repositório:
```bash
git clone https://github.com/GilbertoPaiva/clone-disneyplus.git landing-page-homem-da-terra
cd landing-page-homem-da-terra
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o build de desenvolvimento com watch:
```bash
npm run dev
```

4. Ou faça o build de produção:
```bash
npm run build
```

## 📦 Scripts Disponíveis

- `npm run dev` - Inicia o modo de desenvolvimento com watch (recompila automaticamente ao salvar)
- `npm run build` - Compila todos os arquivos para produção

## 🎨 Recursos da Landing Page

### Seções Implementadas

1. **Header** - Navegação com scroll effect
2. **Hero** - Banner principal com CTA
3. **Abas de Conteúdo** - Sistema de tabs para:
   - Personagens
   - Bastidores
   - Críticas
4. **Planos** - Opções de locação e compra
5. **Seções Informativas** - Sobre o filme e disponibilidade
6. **Dispositivos** - Plataformas disponíveis
7. **FAQ** - Perguntas frequentes com accordion
8. **Footer** - Links e informações

### Funcionalidades JavaScript

- Sistema de tabs interativo
- Accordion no FAQ
- Header que aparece/desaparece com scroll
- Design totalmente responsivo

## 🖼️ Sobre as Imagens Placeholder

As imagens atuais são placeholders do serviço `via.placeholder.com` com as proporções corretas para cada tipo de conteúdo:

- **Logos**: 200x50px
- **Hero branding**: 400x100px
- **Combos**: 300x150px
- **Personagens/Cards**: 300x450px (proporção 2:3)
- **Planos**: 200x100px
- **Hero scenes**: 1920x1080px (16:9)
- **Mobile scenes**: 768x1024px (3:4)
- **Dispositivos**: 150x150px

**Importante**: Todas as imagens placeholder devem ser substituídas por imagens reais do filme antes do deploy final.

## 🌐 Deploy

Este projeto está configurado para ser facilmente publicado em várias plataformas:

### GitHub Pages (Automático com GitHub Actions)

O projeto já está configurado com GitHub Actions para deploy automático:

1. Vá em Settings > Pages no seu repositório
2. Em "Source", selecione "GitHub Actions"
3. Faça push para a branch main/master
4. O workflow `.github/workflows/deploy.yml` será executado automaticamente
5. Sua página estará disponível em `https://[seu-usuario].github.io/[nome-do-repo]`

### Netlify (Deploy Automático)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

Ou manualmente:
1. Faça login no [Netlify](https://netlify.com)
2. Conecte seu repositório GitHub
3. O arquivo `netlify.toml` já está configurado
4. Clique em "Deploy site"
5. Deploy automático a cada push na branch principal

### Vercel (Deploy Rápido)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Ou via CLI:
```bash
npm i -g vercel
vercel
```

O arquivo `vercel.json` já está configurado para o build correto.

### Cloudflare Pages

1. Faça login no [Cloudflare Pages](https://pages.cloudflare.com/)
2. Conecte seu repositório GitHub
3. Configure:
   - Build command: `npm run build`
   - Build output directory: `/`
4. Clique em "Save and Deploy"

## 📝 Boas Práticas Seguidas

- ✅ Código semântico e acessível
- ✅ Design mobile-first e responsivo
- ✅ Separação de concerns (HTML, CSS, JS)
- ✅ Uso de pré-processador CSS (SASS)
- ✅ Minificação e otimização de assets
- ✅ Build automatizado
- ✅ Comentários em código quando necessário
- ✅ Estrutura de arquivos organizada

## 🤝 Contribuindo

Este é um projeto educacional. Sugestões e melhorias são bem-vindas!

## 📄 Licença

Este projeto é para fins educacionais. O filme "O Homem da Terra" e todos os direitos relacionados pertencem aos seus respectivos proprietários.

---

**Nota**: Este é um projeto de demonstração criado para fins educacionais. Todas as referências ao filme são usadas apenas para ilustração de conceitos de desenvolvimento web.

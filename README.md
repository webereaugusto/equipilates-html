# Equipilates - Equipamentos de Pilates

[![Website](https://img.shields.io/badge/website-online-brightgreen)](https://webereaugusto.github.io/equipilates-html/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Performance](https://img.shields.io/badge/PageSpeed-85+-success)](https://pagespeed.web.dev/)

Site institucional da **Equipilates**, líder em fabricação de equipamentos de Pilates na América Latina desde 2006. Fábrica própria em Resende-RJ com exportação para 24+ países.

🌐 **[Ver Site ao Vivo](https://webereaugusto.github.io/equipilates-html/)**

---

## 📋 Sobre o Projeto

Landing page moderna e responsiva desenvolvida para apresentar as linhas de produtos Equipilates, com foco em conversão e experiência do usuário.

### ✨ Características Principais

- 🎨 **Design Moderno** - Interface clean com animações suaves e transições elegantes
- 📱 **Totalmente Responsivo** - Otimizado para mobile, tablet e desktop
- 🌍 **Multilíngue** - Suporte para Português, Inglês, Espanhol e Alemão
- 🚀 **Alta Performance** - PageSpeed 85+ com lazy loading e otimizações
- ♿ **Acessibilidade** - ARIA labels e navegação por teclado
- 🎯 **SEO Otimizado** - Meta tags, Schema.org, Open Graph completos
- 📸 **Galeria Inteligente** - Sistema de filtros com carregamento progressivo
- 🎪 **Carrosséis Modernos** - Navegação touch, autoplay e dots interativos

---

## 🛠️ Tecnologias

O projeto foi desenvolvido com tecnologias web puras, sem frameworks pesados:

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Flexbox, Grid, animações nativas, gradientes
- **JavaScript (Vanilla)** - Sem dependências externas
- **WebP** - Imagens otimizadas para web
- **i18n** - Sistema de internacionalização custom

---

## 🎯 Funcionalidades

### 🏠 Hero Section
- Slider automático com 3 slides
- Navegação por dots e setas
- Conteúdo dinâmico em 4 idiomas
- CTA destacado para WhatsApp

### 🖼️ Galeria de Produtos
- **4 categorias**: Linha Clássica, Contemporânea, Acessórios
- Filtros dinâmicos com animação
- Carregamento progressivo (2 linhas por vez)
- Embaralhamento aleatório a cada visita
- Lazy loading para performance

### 🎠 Carrosséis de Produtos
- **Linha Clássica** - 10 produtos com carrossel responsivo
- **Linha Contemporânea** - 10 produtos com carrossel responsivo
- Autoplay automático
- Controles laterais + dots de navegação
- Suporte a touch/swipe em mobile

### 📊 Seção Institucional
- Processo de fabricação em timeline
- Estatísticas da empresa
- Diferenciais competitivos
- Valores e missão

### 🌐 Internacionalização
Sistema de troca de idioma com persistência:
- 🇧🇷 Português (padrão)
- 🇺🇸 English
- 🇪🇸 Español
- 🇩🇪 Deutsch

### 📞 Formulário de Contato
- Integração com WhatsApp
- Validação em tempo real
- Mensagens personalizadas por idioma

---

## 🚀 Como Usar

### Visualizar Localmente

1. **Clone o repositório**
```bash
git clone https://github.com/webereaugusto/equipilates-html.git
cd equipilates-html
```

2. **Inicie um servidor local**

**Opção A - Python:**
```bash
python -m http.server 8080
```

**Opção B - Node.js:**
```bash
npx http-server -p 8080
```

**Opção C - PHP:**
```bash
php -S localhost:8080
```

3. **Acesse no navegador**
```
http://localhost:8080
```

> ⚠️ **Importante:** Não abra diretamente o arquivo `index.html` no navegador. Use sempre um servidor local para evitar problemas com CORS e recursos externos.

---

## 📁 Estrutura do Projeto

```
equipilates-html/
├── index.html              # Página principal
├── styles.css              # Estilos globais
├── script.js               # Lógica JavaScript
├── i18n.js                 # Sistema de internacionalização
├── images/                 # Diretório de imagens
│   ├── linha-classic/      # Produtos linha clássica
│   ├── linha-contemporanea/# Produtos linha contemporânea
│   ├── acessorios/         # Acessórios de Pilates
│   ├── bg/                 # Backgrounds e banners
│   └── logos/              # Logotipos
├── locales/                # Arquivos de tradução
│   ├── pt-BR.json
│   ├── en.json
│   ├── es.json
│   └── de.json
└── README.md               # Este arquivo
```

---

## ⚡ Otimizações de Performance

O site foi otimizado para máxima performance:

- ✅ **Lazy Loading** em todas as imagens da galeria
- ✅ **Defer** nos scripts para não bloquear renderização
- ✅ **Preload** de recursos críticos (CSS e JS)
- ✅ **WebP** para imagens 30% menores
- ✅ **Minificação** CSS e JavaScript
- ✅ **Compressão** de assets

### 📊 Métricas PageSpeed

- **Performance**: 85+ (Mobile)
- **Acessibilidade**: 90+
- **Melhores Práticas**: 96+
- **SEO**: 100

---

## 🎨 Paleta de Cores

```css
--primary:   #1a1a1a    /* Cinza escuro */
--caramel:   #D4A574    /* Dourado/caramelo */
--accent:    #FFD700    /* Amarelo vibrante */
--bg-dark:   #0a0a0a    /* Fundo escuro */
--text:      #ffffff    /* Texto claro */
```

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você encontrar bugs ou tiver sugestões:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'feat: Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

### 📝 Padrões de Commit

Seguimos [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` Nova funcionalidade
- `fix:` Correção de bug
- `perf:` Melhoria de performance
- `style:` Mudanças de formatação/estilo
- `refactor:` Refatoração de código
- `docs:` Mudanças na documentação

---

## 📱 Compatibilidade

Testado e otimizado para:

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📞 Contato

**Equipilates**
- 🌐 Website: [equipilates.com.br](https://www.equipilates.com.br)
- 📧 Email: contato@equipilates.com.br
- 📱 WhatsApp: +55 21 96732-9318
- 📍 Endereço: Resende, Rio de Janeiro, Brasil

---

## 🙏 Agradecimentos

Desenvolvido com ❤️ para revolucionar o mercado de equipamentos de Pilates.

**Equipilates** - Referência em Equipamentos de Pilates desde 2006

---

<div align="center">
  
  **[⬆ Voltar ao topo](#equipilates---equipamentos-de-pilates)**
  
</div>


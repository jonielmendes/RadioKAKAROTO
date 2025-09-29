# 📻 Rádio KAKAROTO - Site Institucional

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

**Site institucional responsivo da Rádio KAKAROTO** - Sua rádio online favorita de Corrente-PI!

## 🎯 Sobre o Projeto

Portal web completo para a Rádio KAKAROTO, desenvolvido seguindo as melhores práticas de acessibilidade, SEO e performance. O projeto visa expandir a audiência online da rádio através de uma plataforma moderna e responsiva.

### ✨ Funcionalidades

- 🎵 **Player de áudio ao vivo** (HTML5)
- 📅 **Programação semanal** organizada em abas
- 🎙️ **Perfis dos locutores** com redes sociais
- 🎧 **Podcasts exclusivos** com players integrados
- 📰 **Notícias locais** de Corrente-PI
- 📞 **Formulário de contato** via email
- 🔒 **Política de privacidade** completa
ℹ️ **Página institucional** com história da rádio

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade
- **Bootstrap 5.3.3** - Framework CSS
- **Bootstrap Icons** - Iconografia
- **Google Fonts (Inter)** - Tipografia

## 📂 Estrutura do Projeto

```
radio-kakaroto/
├── index.html              # Página principal
├── programacao.html         # Programação semanal
├── locutores.html          # Perfis dos locutores
├── podcasts.html           # Lista de podcasts
├── noticias.html           # Notícias locais
├── contato.html            # Formulário de contato
├── sobre.html              # História da rádio
├── politica-privacidade.html # Política de privacidade
├── video.mp4               # Vídeo do hero
├── audio/                  # Arquivos de áudio
│   ├── grupoforroboysoficial-hashtag-forro-boys-b12c3e92.mp3
│   └── podcast.mp3
├── img/                    # Imagens
│   ├── expo.jpg
│   ├── image.png
│   └── image3.png
└── style/
    └── style.css           # Estilos personalizados
```

## 🚀 Como Executar

1. **Clone o repositório:**
```bash
git clone https://github.com/seu-usuario/radio-kakaroto.git
cd radio-kakaroto
```

2. **Abra no navegador:**
```bash
# Método 1: Diretamente
open index.html

# Método 2: Servidor local (recomendado)
python -m http.server 8000
# Acesse: http://localhost:8000
```

3. **Ou use Live Server (VS Code):**
   - Instale a extensão "Live Server"
   - Clique direito em `index.html` → "Open with Live Server"

## 📋 Requisitos Atendidos

### ✅ Funcionalidades Implementadas
- [x] Player de áudio HTML5 sem autoplay
- [x] Programação semanal com nav-pills Bootstrap
- [x] Cards de locutores com redes sociais
- [x] Lista de podcasts com players individuais
- [x] Notícias em formato de cards
- [x] Formulário de contato com `mailto:`
- [x] Páginas de Sobre e Política de Privacidade

### ✅ Tecnologias e Restrições
- [x] HTML5 + CSS3 + Bootstrap 5.x
- [x] Apenas Bootstrap JS bundle oficial
- [x] Sem JavaScript personalizado
- [x] Responsivo para mobile
- [x] Imagens otimizadas

### ✅ Acessibilidade
- [x] `lang="pt-br"` em todos os HTMLs
- [x] Skip links para navegação
- [x] Alt text em todas as imagens
- [x] Contraste adequado
- [x] Estrutura semântica
- [x] ARIA labels nos elementos interativos

### ✅ SEO
- [x] Títulos únicos por página
- [x] Meta descriptions relevantes
- [x] Hierarchy de headings (h1, h2, h3...)
- [x] URLs descritivas
- [x] Breadcrumbs em todas as páginas

## 🎨 Design System

### Cores Principais
- **Primary:** `#0d6efd` (Bootstrap Blue)
- **Success:** `#198754` (Bootstrap Green)
- **Warning:** `#ffc107` (Bootstrap Yellow)
- **Dark:** `#212529` (Bootstrap Dark)

### Tipografia
- **Fonte:** Inter (400, 600, 700)
- **Fallback:** Sans-serif

### Componentes Bootstrap Utilizados
- Navbar responsiva
- Cards e Card Groups
- Nav Pills/Tabs
- Modals
- Forms e Input Groups
- Buttons e Button Groups
- Progress Bars
- Badges
- Accordions
- Alerts

## 📱 Responsividade

O site é totalmente responsivo e foi testado em:
- ✅ Desktop (1920px+)
- ✅ Laptop (1024px - 1920px)
- ✅ Tablet (768px - 1024px)
- ✅ Mobile (320px - 768px)

## 🔧 Configurações Especiais

### Player de Áudio
```html
<audio class="w-100" controls preload="none">
    <source src="audio/musica.mp3" type="audio/mpeg">
    Seu navegador não suporta o elemento de áudio.
</audio>
```

### Formulário de Contato
```html
<form action="mailto:equipe-ti@radiokakarotinho.com" method="post" enctype="text/plain">
    <!-- Campos do formulário -->
</form>
```

## 📊 KPIs de Referência

- **Objetivo:** ≥ 70% das visitas acessam o player
- **Tempo médio:** ≥ 2:30 min
- **Bounce rate:** ≤ 55%
- **Core Web Vitals:** LCP < 2,5s

## 🤝 Como Contribuir

1. Fork o projeto
2. Crie sua branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📝 Notas de Desenvolvimento

- **Sem CMS:** Conteúdo estático por design
- **Sem Backend:** Formulários via `mailto:`
- **Sem JavaScript:** Apenas Bootstrap bundle oficial
- **Performance:** Imagens otimizadas e CSS minificado
- **Compatibilidade:** Testado nos principais navegadores

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Equipe

- **Cliente:** Rádio KAKAROTO Comunicação Ltda.
- **Contato Técnico:** equipe-ti@radiokakarotinho.com
- **Desenvolvimento:** [Seu Nome]

---

**🎵 Rádio KAKAROTO - O ritmo do Brasil, ao vivo 24h!**

# Landing Page - Corporius Pilates e Personal

Uma landing page elegante para bio do Instagram da academia de pilates Corporius, com design responsivo e cores rosa e branco.

## 🎨 Características

- Design responsivo (funciona em todos os dispositivos)
- Cores rosa e branco conforme solicitado
- Retângulo transparente central com efeito glass morphism
- Imagem de background de pilates
- Links para WhatsApp e Instagram
- Link para localização no rodapé
- Animações suaves e efeitos hover

## 📱 Como personalizar

### 1. Links de contato
No arquivo `index.html`, atualize os seguintes links:

```html
<!-- WhatsApp - substitua o número -->
<a href="https://wa.me/5511999999999" class="social-link whatsapp" target="_blank">

<!-- Instagram - substitua o username -->
<a href="https://instagram.com/corporius" class="social-link instagram" target="_blank">

<!-- Localização - substitua o endereço -->
<a href="https://maps.google.com/?q=Studio+Corporius" class="location-link" target="_blank">
```

### 2. Logo
- Substitua o arquivo `logo.svg` pela logo real da academia
- Ou use uma imagem PNG/JPG e atualize a referência no HTML

### 3. Cores
Para alterar as cores, edite o arquivo `styles.css`:

```css
/* Gradient de fundo */
background: linear-gradient(135deg, #ff6b9d 0%, #ffc0e0 50%, #ff6b9d 100%);

/* Cor do logo SVG */
fill="#ff6b9d"
```

### 4. Imagem de background
A imagem atual é do Unsplash. Para usar uma imagem própria:
1. Adicione sua imagem na pasta do projeto
2. Atualize a URL no CSS:

```css
background-image: url('sua-imagem.jpg');
```

## 🚀 Como usar

1. Faça o upload dos arquivos para seu servidor web
2. Acesse através do domínio/subdomínio
3. Use o link na bio do Instagram

## 📁 Estrutura de arquivos

```
landingPageCorporius/
├── index.html      # Página principal
├── styles.css      # Estilos e layout
├── logo.svg        # Logo placeholder
└── README.md       # Este arquivo
```

## 🎯 Elementos incluídos

✅ Imagem de background de pilates  
✅ Retângulo transparente central  
✅ Espaço para logo  
✅ Nome "Corporius Pilates e Personal"  
✅ Link do WhatsApp  
✅ Link do Instagram  
✅ Link de localização clicável no rodapé  
✅ Cores rosa e branco  
✅ Design responsivo  

## 📞 Personalização recomendada

1. **WhatsApp**: Substitua `5511999999999` pelo número real
2. **Instagram**: Substitua `corporius` pelo username real
3. **Localização**: Substitua pelo endereço real do studio
4. **Logo**: Adicione a logo oficial da academia

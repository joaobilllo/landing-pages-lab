# Landing Pages Lab 🚀

Repositório centralizado para todas as landing pages de clientes.

## 📁 Estrutura do Projeto

Este é um monorepo contendo múltiplas landing pages:

- **landingPageCorporius/** - Landing page da Corporius
- **landingPageMarias/** - Landing page da Marias
- **landingPagePamela/** - Landing page da Pamela (múltiplas páginas)
- **landingPageRafael/** - Landing page do Rafael

## 🚀 Deploy na Vercel

### Como fazer deploy de cada landing page:

1. **Faça push deste repositório para o GitHub**

2. **Para cada landing page, crie um projeto separado na Vercel:**
   - Acesse [vercel.com](https://vercel.com)
   - Clique em "Add New Project"
   - Selecione o repositório `landing-pages-lab`
   - Em **Root Directory**, selecione a pasta da landing page (ex: `landingPageCorporius`)
   - Clique em "Deploy"

3. **Configurações importantes:**
   - Framework Preset: `Other` (HTML estático)
   - Build Command: (deixe vazio)
   - Output Directory: (deixe vazio ou `.`)
   - Install Command: (deixe vazio)

### Exemplo de configuração para cada projeto:

#### Projeto: Corporius
- Root Directory: `landingPageCorporius`
- Domain: `corporius.vercel.app` (ou domínio customizado)

#### Projeto: Marias
- Root Directory: `landingPageMarias`
- Domain: `marias.vercel.app` (ou domínio customizado)

#### Projeto: Pamela
- Root Directory: `landingPagePamela`
- Domain: `pamela.vercel.app` (ou domínio customizado)

#### Projeto: Rafael
- Root Directory: `landingPageRafael`
- Domain: `rafael.vercel.app` (ou domínio customizado)

## 🔄 Atualizações

Quando você fizer push de alterações para o GitHub, a Vercel automaticamente:
- Detecta qual pasta foi modificada
- Faz redeploy apenas do projeto correspondente

## 📝 Notas

- Cada landing page funciona de forma independente
- Você pode ter domínios customizados diferentes para cada uma
- Os deploys são automáticos quando você faz push para o branch principal

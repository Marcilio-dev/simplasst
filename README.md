# Simpla SST — Site Institucional

Landing page da **Simpla SST**, consultoria especializada em Saúde e Segurança do Trabalho (SST).

## 🗂️ Estrutura do Projeto

```
simplasst/
├── index.html              ← Página principal (single-page)
├── logo-simpla.svg         ← Logo escudo da marca ⚠️ adicionar
├── text-simpla-sst.svg     ← Texto "Simpla SST" em SVG ⚠️ adicionar
├── og-image.png            ← Imagem de compartilhamento (1200×630px) ⚠️ adicionar
├── apple-touch-icon.png    ← Ícone para iPhone (180×180px) ⚠️ adicionar
├── vercel.json             ← Configuração de deploy Vercel
└── .gitignore
```

> ⚠️ **Assets pendentes:** Adicione os arquivos de logo e imagens antes do deploy para que a marca apareça corretamente no site e nas redes sociais.

## 🚀 Deploy

### GitHub → Vercel

1. Adicione os arquivos de logo ao repositório
2. Acesse [vercel.com/new](https://vercel.com/new)
3. Importe o repositório `Marcilio-dev/simplasst`
4. Clique em **Deploy** — sem configuração adicional necessária

### Deploy manual (Vercel CLI)

```bash
npm i -g vercel
vercel --prod
```

## 📱 Tecnologias

- HTML5 semântico
- CSS puro (sem frameworks)
- JavaScript inline mínimo
- Font: Inter (Google Fonts via CSS system-ui fallback)

## 📞 Contato

- WhatsApp: [+55 21 99082-0269](https://wa.me/5521990820269)
- E-mail: comercial@simplasst.com.br
- Site: [simplasst.com.br](https://simplasst.com.br)

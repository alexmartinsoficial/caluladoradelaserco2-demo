# 🧮 Calculadora de Ganhos - Laser CO₂ Reversi

Calculadora interativa para simular o potencial de faturamento com o Laser CO₂ Ultrapulsado com Microcoring da Fismatek.

## 🚀 Deploy Rápido

### Opção 1: Netlify (Recomendado)

1. Faça fork ou clone este repositório
2. Acesse [Netlify](https://www.netlify.com/)
3. Clique em "Add new site" → "Import an existing project"
4. Conecte seu repositório do GitHub
5. Configure:
   - **Build command:** (deixe vazio)
   - **Publish directory:** `.` ou `/`
6. Clique em "Deploy"

✅ Seu site estará online em segundos!

### Opção 2: Vercel

1. Acesse [Vercel](https://vercel.com/)
2. Clique em "New Project"
3. Importe seu repositório do GitHub
4. Configure:
   - **Framework Preset:** Other
   - **Build Command:** (deixe vazio)
   - **Output Directory:** `.`
5. Clique em "Deploy"

### Opção 3: GitHub Pages

1. No seu repositório, vá em **Settings** → **Pages**
2. Em "Source", selecione a branch `main` e pasta `/root`
3. Salve e aguarde alguns minutos
4. Seu site estará disponível em: `https://seu-usuario.github.io/nome-do-repo/`

## 📁 Estrutura do Projeto

```
calculadora-laser-co2/
├── index.html          # Arquivo principal (único necessário!)
└── README.md           # Este arquivo
```

## 🎨 Funcionalidades

- ✅ Seleção de categoria (Popular, Premium, Luxo)
- ✅ Simulação de quantidade de procedimentos/mês
- ✅ Distribuição customizável entre tipos de procedimento
- ✅ Cálculo automático de faturamento mensal e anual
- ✅ ROI estimado com base no investimento
- ✅ Tabela completa de preços (expansível)
- ✅ CTA direto para WhatsApp
- ✅ Design responsivo para mobile

## 🛠️ Tecnologias

- HTML5
- JavaScript Vanilla
- Tailwind CSS (via CDN)
- Sem dependências ou build necessário!

## 📱 Responsividade

A calculadora é totalmente responsiva e funciona perfeitamente em:
- 📱 Smartphones
- 📱 Tablets
- 💻 Desktops

## 🔧 Personalização

### Alterar valores do investimento

No arquivo `index.html`, localize a seção JavaScript e modifique:

```javascript
const investimento = {
    total: 199900,      // Valor total do equipamento
    parcela: 6108.33    // Valor da parcela mensal
};
```

### Alterar preços dos procedimentos

Localize o objeto `precos` e `preciosMedios`:

```javascript
const precos = {
    popular: 2000,
    premium: 3000,
    luxo: 5000
};
```

### Alterar contatos

Procure por:
- WhatsApp: `https://wa.me/5562983160209`
- Instagram: `@alextecnologiamedica`

## 📊 Como Funciona

1. **Seleção de Categoria**: Usuário escolhe entre Popular, Premium ou Luxo
2. **Quantidade**: Define quantos procedimentos realiza por mês (5-100)
3. **Mix**: Distribui percentualmente entre facial, cirúrgico e outros
4. **Cálculo**: Sistema calcula automaticamente:
   - Faturamento mensal
   - Projeção anual
   - ROI (tempo para retorno do investimento)
   - Lucro líquido (após desconto da parcela)

## 🎯 Exemplo de Uso

Com configuração padrão (20 procedimentos/mês, categoria Premium):
- 40% Facial completo → 8 procedimentos × R$ 3.000 = R$ 24.000
- 30% Cirúrgicos → 6 procedimentos × R$ 5.000 = R$ 30.000
- 30% Outros → 6 procedimentos × R$ 4.000 = R$ 24.000
- **Total mensal:** R$ 78.000
- **Lucro líquido:** R$ 71.891,67 (após parcela)

## 📞 Contato

- **WhatsApp:** (62) 9 8316-0209
- **Instagram:** [@alextecnologiamedica](https://instagram.com/alextecnologiamedica)

## 📄 Licença

Este projeto é de uso exclusivo para demonstração comercial do equipamento Laser CO₂ Reversi da Fismatek.

---

**Desenvolvido para Alex Tecnologia Médica** 🏥✨

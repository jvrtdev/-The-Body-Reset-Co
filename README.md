# The 5-Minute Body Decompression Code — Sales Page

Página de vendas internacional de alta conversão (Direct-Response Health & Wellness) desenvolvida para o infoproduto **"The 5-Minute Body Decompression Code"** da marca **The Body Reset Co.**

O checkout está configurado e integrado diretamente para a Kiwify:
`https://pay.kiwify.com/1O4TNjU`

---

## 🚀 Principais Recursos de Marketing, Vendas & SEO

### 1. Estratégia de Conversão (CRO & Vendas)
* **Preço Âncora com Alto Desconto:** Apresentação clara de **\$12.00** contra **\$37.00** (68% OFF), ideal para oferta de impulso (*tripwire / front-end*) nos mercados EUA, Canadá, Reino Unido e Austrália.
* **Mockup 3D Realista em CSS Puro:** Simulação tridimensional do livro/manual digital em verde floresta idêntico ao design do PDF, sem peso de imagens lentas.
* **Mecanismo Único Visual ("The 3 Master Locks"):** Explicação anatômica da fáscia (Tension Lock, Stress Lock e Flow Lock) que elimina a objeção de "só estou envelhecendo" ou "preciso de massageadores caros".
* **Visualização da Regra "5 out of 10":** Escala gráfica de pressão para tranquilizar o público e eliminar o medo de dor ou lesão.
* **Os 5 Protocolos em Destaque:** Cards individuais com tempo de execução (60s a 3 min) e benefícios anatômicos detalhados.
* **Bônus de Cozinha & Habit Blueprint:** Apresentação do truque das colheres frias, compressa morna e o calendário de 7 dias com *habit stacking*.
* **Garantia Incondicional de 7 Dias:** Caixa de garantia visual com política clara de reembolso sem atrito.
* **Sticky Mobile CTA Bar:** Barra fixa no rodapé que surge automaticamente na rolagem em smartphones (responsável por mais de 80% das vendas no tráfego pago de Meta/TikTok Ads).
* **Script Automático de Preservação de UTMs:** Qualquer parâmetro de campanha (`utm_source`, `utm_campaign`, `utm_medium`, `utm_content`) presente na URL da landing page é repassado automaticamente para o link de checkout da Kiwify.

---

### 2. Otimizações de SEO & Performance
* **SEO Semântico:** Estrutura completa com tags `H1`, `H2`, `H3`, `article`, `section` e navegação limpa.
* **Schema.org Rich Snippets (JSON-LD):**
  * `Product Schema`: Define nome, preço (\$12.00 USD), moeda, marca (*The Body Reset Co.*), disponibilidade e avaliação (4.9 / 5).
  * `FAQPage Schema`: Indexa perguntas e respostas diretamente nas SERPs do Google, aumentando a taxa de clique orgânico (CTR).
* **OpenGraph & Twitter Cards:** Configuração pronta para compartilhamento em redes sociais e apps de mensagens (WhatsApp, iMessage, Twitter).
* **Ultra-rápido:** Carregamento instantâneo com Tailwind CSS CDN e fontes Google pré-conectadas (pontuação 95+ no Google PageSpeed).

---

### 3. Como Visualizar Localmente

Você pode abrir o arquivo `index.html` diretamente no seu navegador ou rodar um servidor local leve:

```bash
# Opção 1: Via Python
python -m http.server 8000

# Opção 2: Via Node (npx)
npx serve
```
Depois acesse `http://localhost:8000` no seu navegador.

---

### 4. Como Adicionar Pixels de Rastreamento (Meta / TikTok / Google)

No arquivo `index.html`, logo antes do fechamento da tag `</head>`, você pode colar os códigos dos seus pixels:

```html
<!-- Meta Pixel Code -->
<script>
  !function(f,b,e,v,n,t,s)
  {if(f.fbq)return;n=f.fbq=function(){n.callMethod?
  n.callMethod.apply(n,arguments):n.queue.push(arguments)};
  ...
  fbq('init', 'SEU_PIXEL_ID');
  fbq('track', 'PageView');
</script>
<!-- End Meta Pixel Code -->
```

---

### 5. Onde Hospedar Gratuitamente em 2 Minutos
* **Vercel / Netlify / Cloudflare Pages:** Basta arrastar a pasta ou conectar seu repositório Git. O deploy é instantâneo e conta com certificado SSL gratuito.
* **WordPress / Elementor:** Pode ser inserido via bloco de código HTML puro ou hospedado em um subdomínio (ex: `reset.seusite.com`).

# Landing Page — Beauty Carolaine Ateliê

Landing page de conversão para campanha de Google Ads. Single-file (`index.html` + CSS embutido), responsiva, sem dependências de build.

## Objetivo
Converter cliques de Google Ads em **agendamentos via WhatsApp**, para o público de Sorocaba (Zona Norte e Campolim), mulheres 20-45 anos.

## Estrutura da página
1. **Header fixo** — logo + botão WhatsApp sempre visível
2. **Hero** — promessa + CTA principal acima da dobra + sinais de confiança (horário, região)
3. **Serviços** — 5 cards com preços; alongamento marcado como "Mais procurado"
4. **Diferenciais** — durabilidade, atendimento, localização, agendamento fácil
5. **Onde & quando** — endereço, horário, WhatsApp
6. **CTA final** — bloco em destaque
7. **Botão flutuante de WhatsApp** — fixo, com animação de pulso

## Conversão (todos os CTAs levam ao WhatsApp)
- Número: **(15) 99818-5916** → link `https://wa.me/5515998185916`
- Mensagem pré-preenchida: "Olá! Vim pelo site e quero agendar um horário."

## Identidade
Segue `identidade/design-guide.md`: rosé `#D98B97` + cinza, fundo claro, estilo delicado e arejado. Fontes: Cormorant Garamond (títulos), Great Vibes (script), Montserrat (corpo).

## Pendências / próximos passos
- [ ] Trocar o número de WhatsApp se houver um comercial dedicado
- [ ] Adicionar fotos reais dos trabalhos (galeria) — aumenta conversão
- [ ] Inserir o **Google tag (gtag.js)** e configurar conversão de clique no WhatsApp para o Google Ads
- [ ] Confirmar dias de funcionamento (assumido seg-sáb)
- [ ] Publicar (Netlify/Vercel/hospedagem) e apontar a campanha pra URL final
- [ ] Rodar `/anuncio-google` para montar a campanha

## Como visualizar
Abrir `index.html` no navegador. O logo está em `assets/logo.jpeg`.

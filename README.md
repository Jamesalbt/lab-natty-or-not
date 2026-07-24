# AtacaDisk: Um Mercado que Nunca Existiu

## 📒 Descrição
Este projeto explora o poder das IAs generativas para criar uma cena hiper-realista do zero: uma cliente sorridente em frente a um supermercado fictício chamado "AtacaDisk". A partir de uma imagem estática, o projeto evoluiu para um vídeo com avatar falante, dando "vida" à personagem através de locução sincronizada.

## 🤖 Tecnologias Utilizadas
- Google Gemini (geração da imagem)
- [Nome da ferramenta usada para animar o avatar/gerar o vídeo — ex: HeyGen, D-ID, Hedra, Kling]
- FFmpeg (pós-produção: normalização de áudio, corte de silêncio, fades)

## 🧐 Processo de Criação
1. **Imagem**: criei um prompt detalhado no Gemini pedindo uma cena de "street photography" em frente a um supermercado fictício, com iluminação natural, pessoas ao fundo e uma fachada de loja com nome e promoções.
2. **Roteiro/Locução**: escrevi uma fala curta e comercial ("Olá! Seja bem-vindo ao AtacaDisk...") para dar voz à personagem.
3. **Vídeo**: usei [ferramenta] para animar a imagem estática em um vídeo com avatar falante, sincronizando a locução com os movimentos labiais.
4. **Pós-produção**: identifiquei e corrigi problemas técnicos no vídeo final — corte de silêncio no início, normalização de volume (loudness) e fades de áudio, usando FFmpeg.

## 🚀 Resultados
O resultado final é um vídeo de 10 segundos com boa consistência visual (luz, sombra, composição) e áudio equilibrado. A imagem estática por si só já é convincente à primeira vista; o vídeo evolui isso adicionando movimento e fala.

**Limitações identificadas:**
- Pequena dessincronia labial em alguns momentos da fala
- Textos nos cartazes de fundo ficam distorcidos quando ampliados
- Movimento do fundo (outras pessoas/carrinhos) é mais estático que em um vídeo real

## 💭 Reflexão (Opcional)
Esse projeto mostrou que hoje é possível ir de uma simples ideia até um vídeo com avatar falante realista, apenas combinando diferentes ferramentas de IA generativa. Ao mesmo tempo, ficou claro que os detalhes finos — sincronia labial, texto legível, movimento natural de fundo — ainda são os pontos onde a IA "entrega o jogo", e onde entra o trabalho humano de revisão e pós-produção pra deixar tudo mais "natty"

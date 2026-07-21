# Guia Completo de Prompts & Nomenclatura de Arquivos de Imagem (IA — Nano Banana / Flux)
**Projeto:** Landing Page Ateliê do Mauricinho 3D  
**Documento:** `05-image-prompts.md`  
**Objetivo:** Especificação de nomenclatura de arquivos (SEO/Developer Friendly) e engenharia de prompts para geração no Freepik Spaces / Nano Banana.

---

## 📁 Convenção de Nomenclatura dos Arquivos (Filenames)

Todas as imagens salvas para o site devem seguir o padrão **kebab-case** (letras minúsculas separadas por hífen), no formato moderno **`.webp`**, com palavras-chave de SEO locais (`mauricinho`, `pet`, `3d`, `cascavel`, `impressao-3d`):

| Imagem | Posição | Nome Recomendado do Arquivo (`.webp`) |
| :--- | :--- | :--- |
| **Hero Principal (Gato Laranja)** | Hero (Seção 1) | `hero-mauricinho-gato-real-escultura-3d.webp` |
| Hero Variação A (Gato Persa) | Hero (Seção 1) | `hero-gato-persa-homenagem-3d.webp` |
| Hero Variação B (Gato Malhado) | Hero (Seção 1) | `hero-gato-tabby-escultura-3d.webp` |
| Hero Variação C (Gato Preto) | Hero (Seção 1) | `hero-gato-preto-litofania-3d.webp` |
| **Infográfico Comparativo** | O Problema (Seção 2) | `comparativo-presente-comum-vs-homenagem-3d.webp` |
| **Card 1 (Linha Pet)** | A Solução (Seção 3) | `card-linha-pet-chaveiro-mauricinho-3d.webp` |
| Card 1 Variação (Patinha) | A Solução (Seção 3) | `card-linha-pet-chaveiro-patinha-3d.webp` |
| Card 1 Variação (Coleção) | A Solução (Seção 3) | `card-linha-pet-colecao-plaquinhas-3d.webp` |
| **Card 2 (Decoração)** | A Solução (Seção 3) | `card-decoracao-luminaria-litofania-gato-3d.webp` |
| Card 2 Variação (Vaso Gato) | A Solução (Seção 3) | `card-decoracao-vaso-geometrico-gato-3d.webp` |
| **Card 3 (Cortadores)** | A Solução (Seção 3) | `card-utilidades-cortadores-biscoito-patinha-3d.webp` |
| Card 3 Variação (Organizador) | A Solução (Seção 3) | `card-utilidades-organizador-mesa-gato-3d.webp` |
| **Equipe & Mascote** | Quem Somos (Seção 5) | `quem-somos-fran-alice-gato-mauricinho-atelie-3d.webp` |
| Equipe Variação (Chefe Miau) | Quem Somos (Seção 5) | `quem-somos-gato-mauricinho-chefe-atelie-3d.webp` |

---

## 📌 Regras Globais de Geração Visual & Copy das Peças

1. **Protagonismo Felino (Gatos):** Sendo a mascote oficial da marca o gatinho Mauricinho (`@mauricinhoogatomaluquinho`), cada imagem de produto ou cena pet destaca variações com gatos (gato laranja persa/tabby, gato preto elegante, gato malhado e tricolor).
2. **Textos em Português Únicos & Criativos:**
   * **Homenagens / Afeto:** *"Minha melhor saudade tem 4 patinhas 🐾"*, *"O céu ganhou a patinha mais linda 🌈"*, *"Eterno no meu coração e na minha estante"*, *"Pra sempre no meu colo 🐾"*, *"Um amor que nem o tempo apaga 🤍"*.
   * **Divertidas / Humor Pet:** *"Mauricinho 🐾 — O Rei do Sachê"*, *"O verdadeiro dono da casa 👑"*, *"10% Anjo, 90% Sapeca"*, *"Dono do meu coração (e do sofá)"*, *"Mãe de Gato com Orgulho"*, *"Cadê meu sachê?"*.
3. **Palette & Mood:** Fundo escuro elegante (`#09080F`), com acentos de iluminação neon em **Roxo Elétrico** (`#8B3DFF`) e **Dourado/Amarelo Quente** (`#F59E0B`).

---

## 🎨 Especificação, Nomes e Prompts Detalhados por Imagem

---

### **Imagem 1: Hero Image (Gato Real + Réplica 3D Impressa)**
- **Nome do arquivo:** `hero-mauricinho-gato-real-escultura-3d.webp`
- **Seção da página:** Seção 1 — Hero
- **Dimensões recomendadas:** 1200 x 800 px
- **Aspect ratio:** 3:2
- **Propósito na página:** Impacto emocional instantâneo. Mostrar a conexão entre o gato real e sua réplica minuciosa impressa em 3D, com uma frase carinhosa e divertida na base.

**Prompt principal (Nano Banana — Gato Laranja Mauricinho):**
> Side-by-side portrait of an adorable fluffy orange tabby cat (Mauricinho) sitting curiously next to its miniature 3D-printed figurine replica on a sleek dark slate table. The 3D-printed figurine features a tiny engraved golden plaque on its base with clear readable text in Portuguese spelling "Mauricinho 🐾 - O Rei do Sachê". High-detail textured surface showing delicate 3D print layer lines with hand-painted finish. Background is a cozy studio with subtle purple ambient neon glow (#8B3DFF) and warm golden key light from the right. Shot on 85mm f/1.4 lens, shallow depth of field, sharp focus on the cat's face and the 3D figurine, eye-level angle. Commercial studio product photography, rich vibrant contrast, deep black background (#09080F), electric violet and warm golden amber (#F59E0B) highlights, hyper-realistic, 8k resolution, award-winning photography.

**Variação A (`hero-gato-persa-homenagem-3d.webp`):**
> Close-up shot of a majestic white fluffy Persian cat inspecting a custom 3D-printed pet portrait figurine of itself. On the small 3D pedestal, there is a clear embossed inscription in Portuguese that reads "Minha melhor saudade tem 4 patinhas 🐾". Soft cinematic lighting with electric purple backlighting (#8B3DFF) and warm amber rim light. Shot on 50mm f/1.8 macro lens, creamy bokeh, intimate angle. Premium photography style, vibrant violet and gold palette, heartwarming atmosphere, ultra detailed, photorealistic.

**Variação B (`hero-gato-tabby-escultura-3d.webp`):**
> A cute fluffy cat lying down next to a 3D-printed custom figurine featuring clear Portuguese text reading "O verdadeiro dono da casa 👑". Dark slate backdrop (#12111A), cyan and purple neon rim lighting. Shot on 35mm lens, sharp print filament textures, vibrant contrast, 8k resolution.

**Variação C (`hero-gato-preto-litofania-3d.webp`):**
> A sleek black cat looking at a glowing 3D-printed litophane cat sculpture. Small metal tag attached with Portuguese text reading "Dono do meu coração (e do sofá)". Dramatic side lighting in electric violet (#8B3DFF) and golden amber (#F59E0B), 85mm f/1.4 lens, photorealistic studio lighting, 8k.

---

### **Imagem 2: Infográfico Comparativo da Dor**
- **Nome do arquivo:** `comparativo-presente-comum-vs-homenagem-3d.webp`
- **Seção da página:** Seção 2 — O Problema
- **Dimensões recomendadas:** 800 x 400 px
- **Aspect ratio:** 2:1

**Prompt principal (Nano Banana):**
> Split-screen conceptual composition comparing generic mass-produced items and custom 3D printed cat keepsakes. On the left side, dull grey mass-produced plastic objects on a cold sterile shelf under flat neutral light. On the right side, a vibrant hand-finished 3D-printed cat portrait plaque glowing with warm ambient light, with readable engraved Portuguese text reading "Eterno no meu coração e na minha estante 🐾", surrounded by soft purple (#8B3DFF) neon reflections on a dark wooden surface. Shot on 35mm tilt-shift lens, sharp focus on the right side with left side desaturated. Conceptual photography, dark obsidian background (#09080F), high contrast, 8k resolution.

**Variação A (`comparativo-escultura-gato-afeto-3d.webp`):**
> Side-by-side visual comparison. Left side: monochrome dusty plastic mug. Right side: a colorful 3D-printed sculpture of a sleeping cat with a customized plaque in Portuguese saying "Um amor que nem o tempo apaga 🤍", with a real orange cat sitting beside it. Warm amber and electric purple lighting (#8B3DFF), high angle shot, clean studio setting, photorealistic.

---

### **Imagem 3: Card 1 — Linha Pet Memorável (Plaquinha / Chaveiro Gato)**
- **Nome do arquivo:** `card-linha-pet-chaveiro-mauricinho-3d.webp`
- **Seção da página:** Seção 3 — A Solução (Card 1)
- **Dimensões recomendadas:** 600 x 400 px
- **Aspect ratio:** 3:2

**Prompt principal (Nano Banana):**
> Macro studio product shot of a custom 3D-printed cat identification tag keychain shaped like a cat head, made from high-grade eco-friendly PLA filament. The surface reveals delicate 3D print layer patterns with clear raised Portuguese text spelling "Mauricinho 🐾 — 10% Anjo, 90% Sapeca". Resting on a dark textured slate surface (#12111A). Illuminated by a soft purple spotlight (#8B3DFF) from above and a warm golden side light (#F59E0B). Shot on 100mm macro lens, f/2.8, extreme detail on print layers and text typography, shallow depth of field. High-end commercial product photography, ultra-realistic, 8k.

**Variação A (`card-linha-pet-chaveiro-patinha-3d.webp`):**
> Close-up photograph of a custom 3D printed cat tag in vibrant purple and gold PLA, featuring embossed Portuguese text reading "Proibido passar sem fazer carinho 🐾". Dark stone backdrop, dramatic rim lighting in violet (#8B3DFF), 85mm lens, crisp details, 8k.

**Variação B (`card-linha-pet-colecao-plaquinhas-3d.webp`):**
> Flat lay collection of colorful 3D printed cat tags with engraved Brazilian Portuguese phrases ("Mãe de Gato com Orgulho 🐾", "Ronronando desde 2021", "Cadê meu Sachê? 🐟") arranged on a dark slate surface. Soft studio lighting with electric purple accent glow, 50mm lens, clean commercial product layout.

---

### **Imagem 4: Card 2 — Decoração Criativa (Luminária Litofania Gato / Vaso 3D)**
- **Nome do arquivo:** `card-decoracao-luminaria-litofania-gato-3d.webp`
- **Seção da página:** Seção 3 — A Solução (Card 2)
- **Dimensões recomendadas:** 600 x 400 px
- **Aspect ratio:** 3:2

**Prompt principal (Nano Banana):**
> A warm glowing 3D-printed lithophane cube lamp displaying a detailed 3D photo of a cat, with a small subtle engraved Portuguese message on the wooden frame reading "Cantinho do Mauricinho 🐾 — Onde a preguiça reina". Sitting on a minimalist dark oak desk beside a modern geometric 3D-printed planter vase. Background is a cozy dark room with subtle electric purple ambient backlight (#8B3DFF). Shot on 50mm f/1.8 lens, natural warm glow, eye-level perspective. Interior product photography, dark slate tones (#12111A), warm golden lighting (#F59E0B), cozy, modern, 8k.

**Variação A (`card-decoracao-vaso-geometrico-gato-3d.webp`):**
> A modern geometric 3D-printed vase shaped like a stylized sitting cat, holding a small succulent plant. Dark desk setting, neon purple rim light (#8B3DFF), 85mm lens, sharp focus, elegant decor photography.

---

### **Imagem 5: Card 3 — Cortadores & Utilidades (Cortadores Patinha de Gato)**
- **Nome do arquivo:** `card-utilidades-cortadores-biscoito-patinha-3d.webp`
- **Seção da página:** Seção 3 — A Solução (Card 3)
- **Dimensões recomendadas:** 600 x 400 px
- **Aspect ratio:** 3:2

**Prompt principal (Nano Banana):**
> Action shot of 3D-printed cookie cutters in cute cat paw shapes resting on a dark marble kitchen counter covered with light flour dusting and freshly cut cookie dough. One cookie cutter features a stamped Portuguese text label reading "Biscoito de Patinha 🐾 — Cadê meu Sachê?". The 3D printed cutters are made of vibrant food-safe purple (#8B3DFF) and orange PLA plastic. Warm side kitchen lighting with soft purple ambient glow. Shot on 50mm f/2.0 lens, 45-degree angle, sharp focus on dough texture and cutter edges. Commercial food photography, warm, inviting, 8k.

**Variação A (`card-utilidades-organizador-mesa-gato-3d.webp`):**
> A cute 3D printed cat-shaped desk organizer holding pens and cables on a dark office desk setup. Small embossed Portuguese label reading "Organizador do Miau 🐾". Neon purple ambient lighting, 50mm lens, highly detailed.

---

### **Imagem 6: Foto da Equipe & Mascote (Fran, Alice e o Gatinho Mauricinho)**
- **Nome do arquivo:** `quem-somos-fran-alice-gato-mauricinho-atelie-3d.webp`
- **Seção da página:** Seção 5 — Prova Social / Quem Somos
- **Dimensões recomendadas:** 500 x 500 px
- **Aspect ratio:** 1:1 (Quadrado)

**Prompt principal (Nano Banana):**
> Warm and welcoming candid portrait of two friendly South American women in their late 20s (Fran and Alice), smiling warmly while holding their beloved fluffy orange cat (Mauricinho) in their creative 3D printing workshop. In the background, desktop 3D printers are softly glowing with purple indicator lights (#8B3DFF) alongside shelves filled with 3D printed cat sculptures and a small glowing neon sign in Portuguese reading "Ateliê do Mauricinho 🐾 — Onde a Saudade vira Presença". Soft natural window light mixed with warm interior ambient lighting. Shot on 50mm f/1.4 portrait lens, shallow depth of field, sharp focus on their smiling faces and the cat. Environmental portrait photography, cozy, authentic, trustworthy, dark background with warm violet and gold accents, 8k resolution.

**Variação A (`quem-somos-gato-mauricinho-chefe-atelie-3d.webp`):**
> Close-up portrait of the fluffy orange cat (Mauricinho) sitting proudly next to a 3D printed replica of itself with a mini gold tag in Portuguese reading "Mauricinho — O Chefe Supremo do Ateliê 👑", with two smiling female creators visible in the soft blurred background. 85mm portrait lens, f/1.8, creamy background blur, warm cinematic lighting, heart-warming, 8k.

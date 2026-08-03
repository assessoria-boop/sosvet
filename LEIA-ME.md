# SOS Vet Clínica Veterinária · Landing Page

Pasta do projeto: `C:\Users\Gaabs\sosvet`

## Imagens que você precisa adicionar nesta pasta (todas em .webp)

| Arquivo | Para que serve | Tamanho sugerido |
|---|---|---|
| `logo.webp` | Logo da clínica (hero, cabeçalho e favicon) | 400x400 px, fundo branco ou transparente |
| `1.webp` a `5.webp` | Prints reais das avaliações do Google (carrossel de depoimentos) | largura ~800 px |
| `clinica1.webp` a `clinica4.webp` | Fotos da clínica (slideshow com fade) | 1200x900 px (proporção 4:3) |

As fotos da clínica ficam em um quadro de proporção fixa 4:3 com recorte central,
então não esticam e não perdem qualidade. Se quiser mais fotos, é só duplicar uma
linha `<img>` dentro de `<div class="galeria" id="galeria">` no `index.html`.

Para converter imagens em webp: https://squoosh.app (qualidade 80 já é suficiente).

## Configurações já aplicadas

- WhatsApp: +55 64 3442-4227 (número não aparece em texto, só nos botões)
- Mensagem automática: "Olá encontrei vocês pelo Google, gostaria de atendimento."
- Google Tag Manager: GTM-MWM2NJSC
- Mapa: embed oficial da SOS Vet Clínica Veterinária
- Fontes do sistema, zoom e arraste lateral bloqueados no mobile
- Todos os botões em verde WhatsApp, texto "Atendimento Imediato"
- Botão do cabeçalho: "Entre em contato" (nome da clínica oculto no mobile)

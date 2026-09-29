# Direções estéticas candidatas

Três direções para avaliação, todas sob os mesmos princípios, o mesmo modelo de dados e o mesmo sistema de cor: três matizes semânticos (Location, Character, Episode) + uma escala neutra. Seleção usa contraste máximo dentro da escala neutra; filtrado usa luminância e opacidade; status do Character usa preenchimento; tipo de relação usa estilo de linha.

As três variam em luminância de fundo, gramática de formas, representação do tempo e tipografia. Todas partem da sensação de "estou mapeando um universo desconhecido". A avaliação usa os 9 estados do Processo de definição em `brainstorming.md`, no protótipo `prototypes/direcoes-esteticas/`.

## Gramática comum

| Elemento | Tratamento |
| --- | --- |
| Status Alive | Forma preenchida |
| Status Dead | Forma vazada (só contorno) |
| Status unknown | Contorno tracejado |
| Relação location atual | Linha contínua |
| Relação origin | Linha pontilhada |
| Relação episódio | Linha fina, só em contexto temporal |
| Viagem origin → location (entre Locations) | Linha fina contínua, espessura ∝ nº de characters |
| Tamanho da Location | ∝ √ residents |
| Posição | Locations agrupadas por dimensão |

## A — Carta celeste

Metáfora: atlas astronômico. O multiverso é um céu ainda não catalogado; o usuário é quem traça as constelações. O tempo é uma órbita: os episódios são marcas num anel externo, e a série inteira dá uma volta.

| Papel | Hex |
| --- | --- |
| Fundo | `#101B2E` azul-tinta |
| Retícula de coordenadas | `#1F3048` |
| Linha em repouso | `#3A4C66` |
| Texto secundário | `#8FA0B8` |
| Texto principal | `#E6E9EF` |
| Location (A) | `#D9B872` latão |
| Character (B) | `#9CC7E6` azul-aço claro |
| Episode (C) | `#C99BD8` lilás |
| Seleção | `#FFFFFF` + anel |

- **Formas**: Location = círculo com anel fino e preenchimento baixo; Character = ponto sólido; Episode = traço radial no anel externo.
- **Tipografia**: IBM Plex Sans (algarismos tabulares para contagens) + IBM Plex Mono para códigos (S01E01, IDs, dimensões).
- **A retícula tem função**: é o sistema de coordenadas do espaço navegável. Ela se move com o zoom e dá orientação.

## B — Placa de laboratório

Metáfora: lâmina de microscopia e caderno de espécimes. O multiverso é uma amostra sob observação; cada entidade é um espécime catalogado. O tempo é linear: os episódios são barras num trilho inferior, como a escala de uma régua.

| Papel | Hex |
| --- | --- |
| Fundo | `#E4E8E6` cinza mineral |
| Superfície | `#F2F4F3` |
| Linha em repouso | `#A9B1AE` |
| Texto secundário | `#5B6468` |
| Texto principal | `#15191B` |
| Location (A) | `#1E5E66` petróleo |
| Character (B) | `#7A3B5C` ameixa |
| Episode (C) | `#A9761C` ocre |
| Seleção | `#000000` + contorno grosso |

- **Formas**: Location = quadrado de cantos suaves (lâmina, recipiente); Character = círculo pequeno; Episode = barra vertical curta.
- **Tipografia**: Source Serif 4 para nomes de entidades (registro editorial de catálogo) + Source Sans 3 para UI e dados, com algarismos tabulares, sem monoespaçada.
- Única direção clara: testa se o grafo mantém a hierarquia sem depender de brilho sobre fundo escuro.

## C — Instrumento de campo

Metáfora: levantamento topográfico e sismógrafo. O multiverso é um terreno instável sendo medido; as Locations são elevações e os characters são marcos de campo. O tempo é um registro lateral, lido como um sismograma.

| Papel | Hex |
| --- | --- |
| Fundo | `#2C3437` ardósia |
| Superfície | `#353E42` |
| Linha em repouso | `#56625F` |
| Texto secundário | `#A7B0AE` |
| Texto principal | `#EEF0EA` |
| Location (A) | `#D8C49A` areia |
| Character (B) | `#86C2B4` sálvia |
| Episode (C) | `#E08FB0` rosa |
| Seleção | `#FFFFFF` + retícula de mira |

- **Formas**: Location = anéis concêntricos (curvas de nível; quantidade de anéis cresce com residents); Character = marca em cruz; Episode = losango no trilho lateral.
- **Tipografia**: Archivo (eixo de largura; condensada para rótulos densos) + DM Mono para dados e códigos.
- Fundo de tom médio: testa um espaço "profundo" sem ir ao escuro total.

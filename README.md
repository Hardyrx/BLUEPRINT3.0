# Blueprint 3.0 — Algoritmo Secreto

Página de captação. HTML puro, sem build, sem dependência.

## Arquivos

```
index.html          página completa
prova-adsense.png   print do painel de pagamentos
```

## Subir no GitHub Pages

1. Cria um repositório novo no GitHub
2. Sobe os dois arquivos na raiz do repo
3. Vai em **Settings → Pages**
4. Em **Source**, escolhe `Deploy from a branch`
5. Branch: `main` · pasta: `/ (root)` · salva
6. Em 1 minuto o site tá no ar

## Domínio próprio

Em **Settings → Pages → Custom domain**, coloca o domínio.
No seu provedor de DNS, cria um registro CNAME apontando para `SEUUSUARIO.github.io`.

## O que editar

| O quê | Onde procurar no index.html |
|---|---|
| Data do lançamento | `new Date('2026-09-15T00:00:00')` |
| Chave Pix | `tiepoag2@gmail.com` (aparece 2x — no HTML e no script) |
| WhatsApp | `wa.me/555192556100` (aparece 2x) |
| Preço | `R$397` |
| Blocos e aulas | seção `// CONTEÚDO` |
| Escada de produtos | seção `// ESTEIRA` |

## Antes de publicar

- Confere se o número do WhatsApp tem 9 dígitos depois do DDD. O link está montado como `555192556100`.
- Borra o nome do titular no print antes de subir. É uma página pública.

# Como contribuir com o Guia pessoal de estudos

Obrigado pelo interesse! Este repositório é o **diário público de estudos** de [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e faz parte da rede [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil). Ele segue o **Padrão de Qualidade GDB v2** naquilo que se aplica a um guia pessoal — mas, diferente dos guias temáticos da rede, **a stack listada aqui é uma escolha pessoal do autor**. Contribuições são tratadas como **sugestões ao diário**, e a decisão final sobre o que entra é do autor.

## O que você pode sugerir

- **Link quebrado ou desatualizado:** abra uma issue com o template *Link quebrado*, de preferência já com um substituto (a documentação ou o site oficial da tecnologia).
- **Documentação oficial melhor** para um item que já está na stack (por exemplo, uma versão em português da mesma documentação): abra uma issue com o template *Sugestão de recurso* ou envie um pull request.
- **Recurso de apoio aos estudos** (ferramenta de anotação, roadmap, currículo gratuito) para a seção "🆕 Recursos de apoio aos estudos": mesma via.
- **Correção de texto** (ortografia, descrição imprecisa, categoria errada): pull request direto.

Sugestões de **novas tecnologias para a stack** são bem-vindas como issue, mas podem ser recusadas sem que isso signifique que a tecnologia é ruim — apenas que ela não faz parte deste plano de estudos. Para guias completos por tema, contribua nos [guias da rede](https://github.com/arthurspk/guiadevbrasil).

## Critérios de aceitação

Um link só entra no diário se cumprir **todos** os itens:

1. **Link funcionando** — resposta HTTP 200 no momento da revisão (verificamos com [lychee](https://github.com/lycheeverse/lychee); o `lychee.toml` na raiz exclui apenas o LinkedIn, que bloqueia verificadores).
2. **Fonte oficial ou legitimamente gratuita** — documentação oficial, site do projeto, curso gratuito do próprio autor. Nada de cursos pagos redistribuídos, PDFs de livros protegidos ou "drives" de terceiros.
3. **Descrição de 1 linha** dizendo o que é e por que vale o clique.
4. **Marcadores corretos:** 💰 pago · 🇺🇸 em inglês · 🆕 publicado/atualizado em 2024–2026.
5. **Ordem:** dentro de cada seção, a ordem existente é a do autor; recursos em português e gratuitos têm preferência quando houver alternativa equivalente.

Formato de cada item:

```markdown
- [Nome do recurso](https://url-verificada) — 1 linha objetiva do que é e por que vale. 🆕 💰 🇺🇸
```

Itens cujo site oficial bloqueia verificadores automáticos (por exemplo, `adobe.com`, `canva.com`, `mysql.com`) ficam **sem link**, com o nome e uma linha de descrição — não substitua por links de terceiros.

## Fluxo de pull request

1. Faça um fork e crie uma branch a partir da `main` (ex.: `fix/link-docker`).
2. Edite o `README.md`.
3. Rode a verificação de links antes de abrir o PR:
   ```bash
   lychee --no-progress './**/*.md'
   ```
4. Abra o PR preenchendo o checklist do template. Descreva o que mudou e por quê.
5. O autor revisa; ajustes podem ser pedidos antes do merge.

## Tradução

Este repositório **não mantém tradução**: é um diário pessoal em português, e o custo de sincronizar uma versão em inglês não se justifica. Não abra PRs de tradução.

## Código de conduta

Ao participar, você concorda com o nosso [Código de Conduta](./CODE_OF_CONDUCT.md).

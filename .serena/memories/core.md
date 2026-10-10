# architecture-diagram-generator

**Nao e um servico**: repositorio de distribuicao de uma **Skill do Claude.ai** que gera diagramas de arquitetura (HTML dark-theme standalone) a partir de descricao em texto.

- Conteudo: `architecture-diagram/` e `architecture-diagram (2)/` (variantes empacotadas com `assets/`), `architecture-diagram.zip` (artefato de instalacao), `examples/images`.
- Uso: usuario baixa o `.zip`, instala em claude.ai (Settings -> Capabilities -> Skills) e usa via prompt.

## Invariantes
- Repo publico (tem remote `architecture-diagram-generator.git`) - conteudo e a propria skill, nao um app rodando.
- Ha uma pasta duplicada `architecture-diagram (2)/` com espaco no nome - checar qual e a versao atual antes de editar (nome sugere export/backup acidental).

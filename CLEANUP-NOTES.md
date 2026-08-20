# WorkAdventure - versão limpa

Esta cópia foi preparada para repositório/deploy, removendo itens que não participam da execução normal:

- configurações de Claude/Codex/VS Code/Husky
- GitHub Actions do projeto original
- benchmarks
- documentação de desenvolvimento
- desktop/Electron
- infraestrutura de CI/CD do projeto oficial
- suites de testes/E2E e mapas de teste
- arquivos de contribuição e relatórios

Foram mantidos os componentes de runtime e integrações opcionais (por exemplo: `synapse`, LiveKit e configurações Docker) para evitar perda de funcionalidades.

## Colisão dos mapas

Os mapas reais incluídos nesta distribuição (`maps/starter/map.json` e `maps/Tuto/tutoV3.json`) já usam o padrão de colisão do WorkAdventure/Tiled: tile de colisão com a propriedade booleana `collides=true`. Essa configuração foi preservada e validada.

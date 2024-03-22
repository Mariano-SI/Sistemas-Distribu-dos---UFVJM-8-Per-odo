# Sistemas-Distribuidos-UFVJM

## Padronização de commits nesse repositório:

### Estrutura do Commit

Nossos commits seguem a seguinte estrutura:

```
<tipo>[escopo opcional]: <descricao>
```

- **tipo**: Indica a operação que está sendo feita. Ex: feat, fix, test…
- **escopo**: (Opcional) Indica o contexto em que estamos trabalhando, como uma funcionalidade.
- **descrição**: Texto descrevendo o que foi realizado.

**Nota**: É importante lembrar que a descrição deve estar no modo imperativo. Por exemplo, fazendo uso do verbo "adicionar":

- “adicionar tal coisa” | infinitivo (errado)
- “adicionando tal coisa” | gerúndio (errado)
- “adicionado tal coisa” | particípio passado (errado)
- “adiciona tal coisa” |imperativo afirmativo (certo)

A seguir, apresentamos os tipos de commit que adotamos em nossa convenção:

- **test**: Indica a criação ou modificação dos códigos de teste.
- **feat**: Sinaliza a criação ou modificação de uma feature ou regra de negócio.
- **style**: Utilizado quando há mudanças de formatação e estilo do código.
- **refactor**: Indica uma refatoração de código que não impacta na lógica ou nas regras de negócio.
- **perf**: Utilizado quando há uma melhoria de performance no código. Similar ao refactor, mas voltado para melhorias de performance.
- **fix**: Sinaliza a correção ou eliminação de bugs.
- **wip**: Indica um desenvolvimento em progresso (Work In Progress).
- **revert**: Utilizado quando há a reversão de um commit.
- **chore**: Sinaliza mudanças nos arquivos de desenvolvimento que não têm relação com arquivos de testes. Também é utilizado para adição ou alteração de dependências de desenvolvimento (como moment, date-fns, etc).
- **build**: Indica mudanças que afetam o processo de build do projeto ou a adição de dependências comuns ao projeto.
- **docs**: Utilizado quando há mudanças na documentação do projeto.
- **ci**: Sinaliza mudanças nos arquivos de configuração de CI.

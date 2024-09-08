Aqui está uma versão aprimorada da sua explicação sobre mensagens de commit semânticas:

---

# Mensagens de Commit Semânticas

Melhore suas habilidades de programação com uma pequena mudança no estilo de suas mensagens de commit.

Formato: `<tipo>(<escopo>): <assunto>`

`<escopo>` é opcional.

## Exemplo

```
feat: adicionar efeito de balanço no chapéu
^--^  ^--------------------------^
|     |
|     +-> Resumo no tempo presente.
|
+-------> Tipo: chore, docs, feat, fix, refactor, style ou test.
```

Mais Exemplos:

- `feat`: (nova funcionalidade para o usuário, não uma nova funcionalidade para o script de construção)
- `fix`: (correção de bug para o usuário, não uma correção para um script de construção)
- `docs`: (alterações na documentação)
- `style`: (formatação, pontos e vírgulas ausentes, etc.; sem alteração no código de produção)
- `refactor`: (refatoração do código de produção, por exemplo, renomeação de variável)
- `test`: (adição de testes ausentes, refatoração de testes; sem alteração no código de produção)
- `chore`: (atualização de tarefas auxiliares, etc.; sem alteração no código de produção)

Referências:

- [Conventional Commits](https://www.conventionalcommits.org/)
- [Semantic Commit Messages - Sparkbox](https://seesparkbox.com/foundry/semantic_commit_messages)
- [Karma Runner - Git Commit Msg](http://karma-runner.github.io/1.0/dev/git-commit-msg.html)

---

Essa versão foca em clareza e uniformidade, e as referências estão formatadas para fácil acesso.

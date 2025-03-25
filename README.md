# Convenção de Commits

A convenção de commits é um conjunto de regras para criar mensagens de commit mais claras e informativas. Seguir essa convenção ajuda a manter um histórico de commits organizado e facilita a compreensão das alterações no projeto.

## ✨ **Estrutura da Mensagem**

A estrutura básica de uma mensagem de commit é:

```
<tipo>: <descrição>

[Corpo opcional]

[Footer opcional (para referenciar issues ou breaking changes)]
```

- **`tipo`**: Identifica a categoria da alteração.
- **`descrição`**: Resumo curto e objetivo sobre a modificação.
- **`corpo`** *(opcional)*: Explicação detalhada da alteração.
- **`footer`** *(opcional)*: Utilizado para referenciar issues ou indicar mudanças significativas.

---

## 📝 **Tipos de Commits**

| Tipo           | Descrição                                                       | Exemplo                                   |
|----------------|-----------------------------------------------------------------|------------------------------------------|
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                     | `feat: adiciona botão de login`         |
| `fix`          | Corrige um bug.                                                 | `fix: corrige erro no carregamento`     |
| `docs`         | Alterações na documentação.                                  | `docs: atualiza README`                  |
| `style`        | Ajustes de formatação e estilo, sem alterar o funcionamento.  | `style: ajusta indentacão`              |
| `refactor`     | Refatoração de código sem mudar comportamento.              | `refactor: melhora performance da API`  |
| `test`         | Adiciona ou modifica testes.                                    | `test: adiciona testes unitários`      |
| `chore`        | Tarefas de suporte, como atualização de dependências.           | `chore: atualiza versão do eslint`     |
| `perf`         | Melhoria de desempenho.                                        | `perf: otimiza algoritmo de busca`      |
| `build`        | Mudanças que afetam o sistema de build ou dependências externas. | `build: configura webpack`              |
| `ci`           | Ajustes em configurações de integração contínua.                | `ci: adiciona workflow de testes`       |

---

## 🛠 **Exemplos de Commits**

1. Adicionando uma nova funcionalidade:
```bash
feat: adiciona funcionalidade de compartilhamento nas redes sociais
```

2. Corrigindo um bug:
```bash
fix: corrige erro no envio de formulário
```

3. Atualizando documentação:
```bash
docs: atualiza documentação da API
```

4. Melhorando a performance:
```bash
perf: otimiza algoritmo de busca em grandes bases de dados
```

5. Adicionando testes:
```bash
test: adiciona testes unitários para LoginService
```

---

## 📖 Boas Práticas

- **Seja descritivo:** Forneça uma descrição clara e objetiva da alteração realizada.
- **Use o tempo imperativo:** Como se estivesse dando uma instrução. Ex: `adicionar`, `corrigir`, `ajustar`.
- **Evite commits grandes:** Divida alterações em pequenos commits sempre que possível.
- **Adicione contexto:** Quando relevante, inclua detalhes adicionais no corpo do commit.

---

## 🔎 Referências
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Angular Commit Guidelines](https://github.com/angular/angular/blob/main/CONTRIBUTING.md)
- [GitHub Docs - Criar commits](https://docs.github.com/pt/get-started/using-git/committing-changes-to-your-project)
- [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/)
- [Git Commit Message Guidelines](https://cbea.ms/git-commit/)

---

Seguir uma convenção de commits ajuda toda a equipe a entender rapidamente as mudanças no código e melhora a gestão do projeto. 🚀


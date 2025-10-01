# Relatório — Criando meu primeiro Copilot (Microsoft Copilot Studio)

## Resumo do conteúdo prático

Este relatório documenta o aprendizado sobre as três formas principais de criar um Copilot no Microsoft Copilot Studio.

### 1. Copilot baseado em **modelo**

- **O que é:** Utiliza templates pré-configurados oferecidos pelo Copilot Studio (ex.: FAQ, suporte, assistente interno).
- **Vantagens:** Rápida implementação; configurações iniciais já definidas; bom para casos de uso comuns.
- **Quando usar:** Quando você precisa de agilidade e o caso de uso é padrão ou recorrente.
- **Principais passos práticos:** Escolher template → revisar intenções e respostas pré-criadas → ajustar texto e variáveis → testar fluxo.

### 2. Copilot baseado em **descrição com IA**

- **O que é:** Você descreve em linguagem natural o que espera do copiloto e a IA gera automaticamente uma estrutura inicial (fluxos, intenções, exemplos).
- **Vantagens:** Permite prototipagem rápida sem necessidade de conhecimento técnico profundo; a IA sugere diálogos e variáveis.
- **Quando usar:** Ideal para prototipação e para quem quer que a IA gere a estrutura base do assistente.
- **Principais passos práticos:** Escrever descrição clara do objetivo → revisar e editar os fluxos gerados → complementar com exemplos e regras de negócio → testar e ajustar.

### 3. Copilot **em branco**

- **O que é:** Construção manual do copiloto desde o zero — definir intents, entidades, fluxos, variáveis e integrações manualmente.
- **Vantagens:** Controle total sobre o comportamento e lógica; melhor para casos altamente customizados.
- **Quando usar:** Quando requisitos são específicos e os templates/descrição automatizada não atendem ao necessário.
- **Principais passos práticos:** Planejar fluxo conversacional → criar intents e respostas → definir variáveis e ações → integrar APIs (se necessário) → testar exaustivamente.

## Lições aprendidas

- Comece por um **modelo** se quer entrega rápida; migre para ajustes manuais se precisar de especificidade.
- Use a **descrição com IA** para gerar um primeiro rascunho — economiza muito tempo em projetos exploratórios.
- Desenvolva um fluxo de testes (casos positivos e negativos) para validar comportamentos inesperados.
- Documente as perguntas/respostas customizadas e as variáveis usadas — facilita manutenção.

---

**Conclusão**: O Microsoft Copilot Studio oferece caminhos tanto para quem busca rapidez (modelos e descrição com IA) quanto para quem precisa de total controle (copilot em branco).

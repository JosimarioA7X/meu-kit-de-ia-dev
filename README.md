# Meu Kit de IA na Prática — Desenvolvimento & AppSec

Repositório criado como entrega prática do Bootcamp DIO, contendo atalhos reutilizáveis de IA adaptados à rotina de desenvolvimento de software e o registro de uma tarefa real delegada com controle humano (*Human-in-the-Loop*).

---

## Minha Entrega

### Contexto do Meu Trabalho
Atuo na área de Análise e Desenvolvimento de Sistemas (ADS), construindo aplicações web e APIs. Na minha rotina semanal de desenvolvimento, preciso organizar tarefas técnicas, revisar trechos de código antes de subir para repositórios remotos e redigir notas de atualização (*Release Notes*) claras a partir de históricos brutos de commits. O meu objetivo com este kit é padronizar essas entregas técnicas mantendo controle total sobre o que é publicado.

---

### Meus Atalhos Adaptados

#### Atalho 1: Gerador de Release Notes Profissionais a partir de Commits
**Quando uso:** Ao finalizar uma entrega ou sprint de desenvolvimento, para transformar uma lista desorganizada de commits em um comunicado técnico claro para a equipe ou documentação do projeto.

```text
Atue como um Tech Lead redigindo notas de lançamento (Release Notes) para um projeto de software.

Vou fornecer abaixo uma lista bruta de mensagens de commit e alterações feitas no código. Transforme esse histórico em um documento estruturado e objetivo em português.

Regras obrigatórias:
1. Separe estritamente o que foi **Implementado/Corrigido (Fatos do histórico)** do que são **Pontos de Atenção / Próximos Passos Sugeridos** (suas recomendações técnicas).
2. Não invente funcionalidades, correções ou métricas de performance que não estejam descritas nos commits enviados.
3. Agrupe as alterações nas categorias: Novas Funcionalidades, Correções de Bugs e Melhorias Internas.
4. Oculte ou generalize qualquer menção a nomes de arquivos internos sensíveis ou credenciais.

Objetivo: Estruturar um documento de Release Notes (v1.2.0) e um checklist de validação pós-deploy a partir do histórico bruto de commits de um sistema web de gestão de tarefas.

Contexto: Sou desenvolvedor e preciso publicar a atualização semanal do projeto no repositório oficial, garantindo que a documentação reflita exatamente o que foi alterado no código, sem suposições.

Recursos fornecidos: A lista bruta de commits da semana (que enviarei somente após validar o seu plano).

Limites e Regras de Controle (Human-in-the-Loop):
1. NÃO redija o documento final ainda.
2. Apresente primeiro apenas o Plano de Execução, detalhando como você vai estruturar as seções, como vai filtrar as informações e quais riscos vai verificar.
3. Aguarde explicitamente a minha aprovação do plano e o envio dos commits antes de gerar qualquer texto final.
4. Não invente melhorias ou correções que não constem nos registros fornecidos.

Critério de Sucesso: Um plano objetivo para minha aprovação, seguido (após o meu aval) de um documento Markdown limpo, técnico, sem dados sensíveis e com separação clara entre o que foi entregue no código e o que é sugestão de melhoria.

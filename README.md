# GUIA
GUIA - Uma proposta de styleguide para ser usado em projetos.

**Branchs**
```
    • develop: versão que contém todas as novas features desenvolvidas (onde todo o ciclo de teste e validação foram feitos), não deve conter desenvolvimentos não aprovados e desenvolvimentos incompletos, ou seja, tudo que está preparado e aprovado para ir pra próxima release em produção. caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em develop
    
    • master: última versão estável, contém todos os recursos entregues em produção, caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em master
    
    • feature/xxxx: uma branch temporária que contém a implementação candidata na próxima release, onde seu ciclo de vida fica limitado à sua aprovação e validação, na sua finalização deve ir para o branch develop
    
    • bugfix/xxxx: uma branch temporária que contém uma correção que não é emergencial e pode ser levada para a próxima release. seu ciclo de vida é semelhante ao feature, somente muda o nome por respeito à nomenclatura da classificação da implementação
    
    • hotfix/xxxx: uma branch temporária que contém uma correção que é emergencial, devido à sua operação, deve ser definido por toda a equipe se a correção é uma hotfix. Seu ciclo de vida termina na validação da correção do erro e seu conteúdo deve ir para master e develop. 
```

**Commits**
```
    • feat: nova feature
    
    • fix: correção de código
    
    • docs: melhoria de comentário de código ou edição da parte de documentação da sua base de código;
    
    • style: melhorias de formatação de texto, mudança de estilo de codificação;
    
    • refactor: uma vez trabalhando com boa cobertura de teste ou não (o risco é por sua conta), esse commit é quando for apenas refatorar seu código;
    
    • perf: quase a mesma pegada do refactor mas esse ajuste resulta em maior performance da solução;
    
    • test: inclusão ou manuntenção de testes do software;
    
    • chore: se o que alterou não está associado a algum listado acima, utilize ele para classificar.
    
    • ci: para alterações no script de integração contínua
```

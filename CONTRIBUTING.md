# Contributing

## Contribuição

Ao contribuir para este repositório, por favor, discuta a alteração que deseja realizar via *issue*, e-mail ou qualquer outro método com os proprietários do repositório antes de fazer a modificação. Para cada modificação, verifique se já existe uma *issue* relacionada. Se não houver, crie uma nova *issue*, atribua um responsável, uma label e crie uma branch a partir dessa *issue*. **Essas diretrizes se aplicam a todos os colaboradores, incluindo a equipe de desenvolvimento.**

Lembramos que temos um código de conduta, que deve ser seguido em todas as interações no projeto.

## Relatando Bugs
Esta seção orienta você sobre como enviar um relatório de bug para o grupo responsável pelo projeto EvenTour. Seguir essas diretrizes ajuda os mantenedores e a comunidade a entender seu relato, reproduzir o comportamento e encontrar relatórios relacionados. **Essas diretrizes devem ser seguidas por todos os colaboradores do projeto.**

Antes de criar relatórios de bug, verifique a lista de problemas existentes; pode ser que não seja necessário criar um novo. Quando criar um relatório de bug, inclua o máximo de detalhes possível e preencha o [template obrigatório], pois as informações solicitadas ajudam a resolver problemas mais rapidamente.

### Como Enviar um (Bom) Relatório de Bug?
Os bugs são rastreados como *issues* no GitHub. Crie uma *issue* no repositório e forneça as seguintes informações, preenchendo o template:

- Explique o problema e inclua detalhes adicionais para ajudar os mantenedores a reproduzir o problema.
- Use um título claro e descritivo para a *issue* para identificar o problema.
- Descreva os passos exatos que reproduzem o problema com o máximo de detalhes possível. Por exemplo, explique como você iniciou o módulo, incluindo o comando usado no terminal.
- Forneça exemplos específicos para demonstrar os passos. Inclua links para arquivos ou projetos no GitHub, ou trechos copiáveis que você usa nos exemplos. Se estiver fornecendo trechos no *issue*, use blocos de código Markdown.
- Descreva o comportamento observado após seguir os passos e aponte qual é exatamente o problema com esse comportamento.
- Se o problema não foi desencadeado por uma ação específica, descreva o que você estava fazendo antes do problema ocorrer e compartilhe mais informações usando as orientações abaixo.

### Responda a estas perguntas para fornecer mais contexto:
- O problema começou recentemente ou sempre ocorreu?
- Se começou recentemente, você consegue reproduzi-lo em uma versão anterior? Qual é a versão mais recente em que o problema não ocorre?
- Consegue reproduzir o problema de forma consistente? Em caso negativo, informe a frequência e as condições em que o problema geralmente ocorre.
- Se o problema está relacionado ao trabalho com arquivos (abrir e editar arquivos), ele acontece em todos os arquivos e projetos ou apenas em alguns? Ele ocorre apenas ao trabalhar com arquivos locais ou remotos (por exemplo, em unidades de rede), arquivos de um tipo específico, arquivos grandes ou com linhas muito longas, ou arquivos em uma codificação específica? Há algo especial sobre os arquivos usados?

## Sugestões de Melhorias
Esta seção orienta você sobre como enviar sugestões de melhorias para os módulos do EvenTour, incluindo novas funcionalidades e pequenas melhorias na funcionalidade existente. Seguir essas diretrizes ajuda os mantenedores e a comunidade a entender sua sugestão e encontrar sugestões relacionadas. **Essas diretrizes devem ser seguidas por todos os colaboradores, incluindo a equipe de desenvolvimento.**

Antes de criar uma sugestão de melhoria, verifique as *issues* existentes; pode ser que não seja necessário criar uma nova. Ao criar uma sugestão, inclua o máximo de detalhes possível e preencha o template, incluindo os passos que você imagina que faria se a funcionalidade solicitada existisse.

### Como Enviar uma (Boa) Sugestão de Melhoria?
Sugestões de melhoria são rastreadas como *issues* no GitHub. Crie uma *issue* no repositório e forneça as seguintes informações:

- Use um título claro e descritivo para a *issue* para identificar a sugestão.
- Descreva passo a passo a sugestão de melhoria com o máximo de detalhes possível.
- Forneça exemplos específicos para demonstrar os passos. Inclua trechos copiáveis que você usa nos exemplos, como blocos de código em Markdown.
- Descreva o comportamento atual e explique qual comportamento você esperava ver e por quê.
- Inclua capturas de tela e GIFs animados que ajudem a demonstrar os passos ou destacar a parte do código relacionada à sugestão.
- Especifique o nome e a versão do sistema operacional que você está usando.

## Contribuindo com Documentação
A documentação é uma parte essencial do projeto, e suas contribuições são muito valorizadas. Ao contribuir com documentação, siga as diretrizes abaixo:

### Requisitos para Contribuição
1. **Título**: Cada documento deve ter um título claro e descritivo.
2. **Histórico de Versões**: Inclua uma seção de histórico de versões, detalhando as mudanças feitas e as datas correspondentes.
3. **Descrição**: Forneça uma descrição que explique o objetivo do documento e o público-alvo.
4. **Versionamento**: Utilize um sistema de versionamento consistente para acompanhar as alterações e melhorias feitas no documento.

### Como Contribuir com a Documentação?
- Crie uma nova *issue* para discutir a alteração ou adição à documentação que você gostaria de fazer.
- Prepare suas alterações em uma branch separada e faça um Pull Request quando estiver pronto.
- Certifique-se de que a documentação siga os padrões de estilo e formatação estabelecidos pelo projeto.

## Mensagens de Commit
Para facilitar o entendimento e o histórico das alterações, é necessário que as mensagens dos commits contenham informações completas e claras sobre o que foi alterado. As mensagens devem incluir o número da *issue* correspondente para contextualizar o commit. Exemplo de formatação para mensagens de commit:

```
(#324): realizando correções no README
```

Assim, todos podem compreender o objetivo do commit sem precisar de explicações adicionais.

## Processo de Pull Request
O processo descrito aqui possui vários objetivos:

- Corrigir problemas importantes para os usuários.
- Atualizar o README.md com detalhes das mudanças na interface, incluindo novas variáveis de ambiente, portas expostas, locais úteis de arquivos e parâmetros de contêiner.
- Aumentar os números de versão em quaisquer arquivos de exemplo e no README.md para a nova versão representada pelo Pull Request.
- Você pode mesclar o Pull Request após obter o aval de outros dois desenvolvedores ou, se não tiver permissão para fazer isso, pode solicitar ao segundo revisor que o mescle para você.
- Siga todas as instruções no template.
- Siga os guias de estilo.
- Após enviar seu Pull Request, verifique se todas as verificações de status foram aprovadas.

### E se as verificações de status falharem?
Embora os pré-requisitos acima devam ser atendidos antes da revisão do Pull Request, o(s) revisor(es) podem solicitar trabalho de design adicional, testes ou outras alterações antes que seu Pull Request seja aceito.


[Ex de contibuting](https://github.com/DNXLabs/terraform-aws-ecs/blob/master/CONTRIBUTING.md)
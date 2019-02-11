> **Tipo**

Tipos se resumem em feat, fix, refactor, style, chore, doc e test

**feat** => são quaisquer adições ao código, Enquanto elas podem alterar parte do código já existente, o foco dela é a implementação de features novas ao ecossistema

**fix** => refere-se ás correções de bugs. Caso seu time trabalhe com issues ou com Jira, é possível com smart commits associar seu commit a uma issue e alterar seu estado com keywords como resolve, fix, solves. Em geral, essas marcações devem vir na descrição ou no footer.

**refactor** => refere-se a quaisquer mudanças que atinjam o código, porém não alterem a sua funcionalidade . Alterou o formato de como é o processamento em determinada parte da sua tela, mas manteve a mesma funcionalidade? Declare como refactor

**style** => Alterações referentes a formatações de código, semicolons, trailing spaces e lint em geral.

**project** => todo o escopo de versões e pacotes ficam inseridos nele

**env** => Atualizações de arquivos de CI, docker, build files, task runners ou configurações.

**doc** => Conteúdo relativo a documentação

**test** => Modificações e adições aos testes

> **Escopos**

Podem ser quaisquer partes do projeto; é importante que eles sejam compreendidos de uma maneira quase automática para alguém que não conhece o projeto. Em geral, a utilização de um escopo é bem generica, especificando apenas o primeiro contexto (login, middleware, profile). No entanto, prefiro ser mais especifico e definir um segundo escopo (containers/login, por exemplo).

Supondo que você tenha feito uma refatoração nas rotas relativas as settings do projeto, uma possiblidade de commit seria:

refactor(routes/settings): adjust settings to be called in any screen.

> **Descrição**

Devem ser suficientemente claras, utilizando seu espaço até o máximo permitido na linha. Caso você veja que a explicação não foi suficiente. sinta-se á vontade para adicionar conteúdo ao corpo

> **Corpo**

Vai conter descrições mais precisas do que está contido naquele commit, mostrando as razões ou consequências geradas por esse código, assim como instruções futuras.

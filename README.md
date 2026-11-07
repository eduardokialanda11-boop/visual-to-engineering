Visual-to-Engineering — Da imagem à fabricação

Plataforma de engenharia assistida por IA que transforma imagens, esboços e desenhos técnicos em projetos estruturados, permitindo definir dimensões, identificar componentes e orientar visualmente a fabricação e a montagem.

Página pública: https://eduardokialanda11-boop.github.io/visual-to-engineering/
Repositório: https://github.com/eduardokialanda11-boop/visual-to-engineering
Hackathon: Hack Brasil 2026 — Logística & Automação

---

1. O problema

Empresas e profissionais que fabricam, montam, instalam ou fazem manutenção frequentemente recebem apenas uma fotografia, um esboço ou uma referência visual de um produto.

Transformar essa referência em um projeto técnico exige identificar componentes, definir dimensões, selecionar materiais, calcular quantidades e planejar as etapas de fabricação.

Esse processo pode ser demorado, depender de trabalho manual e gerar erros quando as informações estão incompletas ou são interpretadas incorretamente.

O problema afeta, entre outros:

- Indústrias e fábricas;
- Empresas de logística;
- Construtoras e montadoras;
- Serralherias e oficinas;
- Equipes de manutenção;
- Profissionais de fabricação de estruturas e equipamentos.

2. A solução

O Visual-to-Engineering propõe uma plataforma que conecta a interpretação visual à engenharia e à fabricação.

O usuário envia uma imagem de um objeto industrial. A plataforma analisa sua estrutura, identifica componentes e organiza as informações necessárias para desenvolver um projeto técnico.

O objetivo não é apenas gerar um desenho: é permitir que o usuário compreenda como o objeto é composto e seja orientado na fabricação e montagem daquele mesmo objeto, desde a primeira etapa até a conclusão.

3. Como funciona

Etapa 1 — Entrada do objeto

O usuário poderá enviar:

- Fotografias;
- Esboços feitos à mão;
- Desenhos técnicos;
- Imagens de referências industriais.

Etapa 2 — Interpretação e decomposição

A IA analisa a imagem e procura identificar:

- Estrutura geral;
- Componentes individuais;
- Chapas, tubos, perfis e conexões;
- Quantidade aparente de peças;
- Geometria e relações entre componentes;
- Dimensões que possam ser observadas ou calculadas.

O objeto será representado digitalmente e poderá ser apresentado em uma visualização desmontada, destacando cada componente.

Etapa 3 — Definição e edição das medidas

O usuário terá controle sobre as dimensões do projeto.

Poderá:

- Informar altura, largura e profundidade do objeto;
- Definir medidas específicas de cada componente;
- Informar espessuras e outras dimensões relevantes;
- Corrigir medidas identificadas pela IA;
- Adicionar dimensões que não aparecem na imagem;
- Alterar valores e visualizar as consequências no projeto.

Quando uma medida não puder ser determinada com segurança, a plataforma deverá solicitar essa informação ao usuário ou identificá-la como pendente.

Etapa 4 — Dois modos de operação

Modo Automático

A plataforma interpreta a imagem, identifica os componentes e organiza o projeto com as informações disponíveis. Quando faltar uma dimensão ou informação essencial, solicita a intervenção do usuário.

Modo Assistido

O usuário participa diretamente da construção do projeto, respondendo às perguntas da plataforma, definindo medidas, selecionando materiais e corrigindo a interpretação da IA.

Os dois modos utilizarão o mesmo núcleo de engenharia e deverão produzir um projeto estruturado e coerente.

Etapa 5 — Projeto técnico

A plataforma deverá organizar os resultados em:

- Desenho técnico com cotas;
- Representação digital do objeto;
- Vista explodida com identificação dos componentes;
- Lista de materiais e quantidades;
- Especificações dimensionais;
- Informações sobre conexões e montagem;
- Plano de fabricação;
- Documentação técnica exportável.

Etapa 6 — Orientação visual de fabricação e montagem

Esta é uma das funcionalidades centrais do projeto.

A plataforma deverá orientar o usuário passo a passo na fabricação e montagem do objeto que foi analisado.

Cada etapa deverá apresentar, conforme aplicável:

- Qual componente será fabricado ou instalado;
- Quais são suas dimensões;
- Qual material deverá ser utilizado;
- Qual operação deverá ser realizada;
- Como o componente se conecta às demais peças;
- Qual é a próxima etapa do processo.

A orientação deverá acompanhar o projeto específico do usuário, e não apresentar apenas instruções genéricas.

4. Confiabilidade das informações

O sistema deverá distinguir claramente a origem e o nível de confiança de cada informação:

Classificação| Significado
Observada| Informação identificada diretamente na imagem ou desenho
Calculada| Informação obtida por cálculo a partir de dados disponíveis
Estimada| Valor aproximado que ainda precisa de confirmação
Informada pelo usuário| Dado inserido manualmente pelo usuário
Pendente| Informação necessária que ainda não foi definida
Validada| Informação conferida e aprovada conforme os critérios do projeto

Uma imagem, isoladamente, não permite determinar com segurança todas as dimensões, materiais, espessuras ou características ocultas de um objeto.

Por isso, a plataforma não deverá apresentar estimativas como medidas confirmadas nem considerar automaticamente um projeto pronto para fabricação.

Projetos que envolvam riscos estruturais, vasos de pressão, reservatórios ou outros equipamentos críticos exigirão verificações técnicas, normas aplicáveis e validação de profissional habilitado.

5. Exemplo ilustrativo — Rack industrial

O rack industrial é utilizado como exemplo ilustrativo para demonstrar o funcionamento proposto.

O usuário envia uma imagem do rack e informa as dimensões gerais que conhece. Em seguida, poderá definir ou corrigir as dimensões de cada componente.

A plataforma deverá organizar a estrutura, identificar suas peças, apresentar uma representação desmontada e atualizar o desenho técnico conforme as medidas fornecidas.

Por fim, deverá orientar visualmente a fabricação e a montagem daquele rack específico.

Observação: este exemplo demonstra o conceito da solução. Não representa um projeto industrial já validado, um produto fabricado ou resultados de testes comprovados.

6. Objetivo do projeto

O objetivo do Visual-to-Engineering é reduzir a distância entre uma referência visual e um processo estruturado de engenharia e fabricação.

A proposta é tornar mais acessível a transformação de imagens em projetos técnicos, oferecendo ao usuário controle sobre as dimensões, compreensão dos componentes e orientação durante a execução.

7. Tecnologias

Implementação atual do repositório:

- HTML;
- CSS;
- JavaScript;
- GitHub;
- GitHub Pages.

Tecnologias que poderão integrar a evolução da plataforma:

- Inteligência artificial multimodal e visão computacional;
- Backend em Python;
- Banco de dados e armazenamento;
- Ferramentas de modelagem e geometria 3D;
- Geração de desenhos e arquivos CAD;
- Exportação de documentação técnica.

As tecnologias futuras representam possibilidades de desenvolvimento, não funcionalidades já implementadas nesta versão estática.

8. Como executar a versão atual

A versão atual é uma página estática de apresentação do projeto.

Online:
Acesse https://eduardokialanda11-boop.github.io/visual-to-engineering/

Localmente:

1. Baixe ou clone o repositório:
   "git clone https://github.com/eduardokialanda11-boop/visual-to-engineering.git"
2. Abra a pasta do projeto.
3. Abra o arquivo "index.html" em um navegador.

A página de apresentação pode ser aberta localmente, mas isso não significa que o processamento por IA, a modelagem técnica ou a orientação de fabricação já estejam implementados.

9. Equipe

Kialanda e Debora
Hack Brasil 2026 — Logística & Automação
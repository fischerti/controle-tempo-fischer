# Controle de Tempo de Máquinas — Fischer®

Sistema web corporativo desenvolvido para registrar, acompanhar e analisar o tempo de operação, uso, pausa e manutenção de máquinas industriais.

O projeto foi criado para apoiar o acompanhamento operacional da Fischer, permitindo registrar as atividades realizadas em cada máquina e consolidar os tempos por máquina, ação, processo, operador e período.

## Visão Geral

O **Controle de Tempo de Máquinas — Fischer®** permite acompanhar as atividades das máquinas em tempo real, registrar períodos manualmente e visualizar os tempos acumulados em um dashboard operacional.

O sistema foi desenvolvido em **HTML, CSS e JavaScript puro**, sem necessidade de instalação de dependências ou servidor próprio nesta versão.

Os dados são armazenados localmente no navegador por meio de `localStorage`.

## Funcionalidades

- Cadastro e gerenciamento das máquinas monitoradas.
- Registro de operação, uso, pausa e manutenção.
- Cronômetro individual para cada máquina.
- Apontamento do operador ou responsável.
- Seleção do turno de trabalho.
- Registro do processo executado.
- Campo para observações.
- Encerramento automático do período anterior ao trocar a ação da máquina.
- Finalização conjunta de todas as atividades em andamento.
- Inclusão manual de períodos anteriores.
- Correção e edição de registros.
- Exclusão de registros.
- Consulta do histórico completo de apontamentos.
- Filtros por máquina, ação e período.
- Dashboard por dia, mês ou intervalo personalizado.
- Consolidação do tempo total registrado.
- Distribuição do tempo por ação.
- Ranking de tempo acumulado por máquina.
- Consolidação do tempo por processo.
- Resumo operacional por máquina e ação.
- Exportação dos registros em arquivo CSV.
- Cadastro de novas máquinas.
- Alteração das informações das máquinas.
- Desativação de máquinas sem exclusão do histórico.
- Geração de dados de demonstração.
- Limpeza da base local de registros.
- Relógio em tempo real no cabeçalho.
- Layout responsivo para computadores, notebooks, tablets e celulares.
- Identidade visual corporativa Fischer®.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- LocalStorage
- GitHub Pages

## Estrutura do Projeto

```text
controle-tempo-fischer/
│
├── index.html
└── README.md
```

### `index.html`

Arquivo principal do sistema. Contém toda a estrutura da página, estilos, scripts, regras de registro, cronômetros, dashboard, histórico e armazenamento local.

### `README.md`

Arquivo de apresentação e documentação inicial do projeto.

## Como Acessar

O sistema pode ser acessado pelo GitHub Pages:

https://fischerti.github.io/controle-tempo-fischer/

## Como Utilizar

1. Cadastre as máquinas que serão monitoradas.
2. Informe o operador ou responsável pelo apontamento.
3. Selecione o turno de trabalho.
4. Escolha a máquina e informe o processo executado.
5. Inicie uma das ações disponíveis:
   - Operação
   - Uso
   - Pausa
   - Manutenção
6. Ao trocar a ação, o período anterior será encerrado automaticamente.
7. Consulte os registros no histórico.
8. Utilize o dashboard para analisar os tempos acumulados.
9. Exporte os dados em CSV quando necessário.

## Como Publicar no GitHub Pages

1. Criar um repositório no GitHub.
2. Adicionar o arquivo principal com o nome:

```text
index.html
```

3. Adicionar o arquivo de documentação:

```text
README.md
```

4. Acessar:

```text
Settings > Pages
```

5. Em **Build and deployment**, selecionar:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

6. Salvar e aguardar a publicação.

## Como Atualizar o Sistema

Para atualizar a página publicada:

1. Acesse o repositório no GitHub.
2. Substitua o arquivo `index.html` pela nova versão.
3. Faça o commit da alteração.
4. Aguarde o GitHub Pages republicar o site automaticamente.

## Armazenamento dos Dados

Nesta versão, os registros são armazenados no `localStorage` do navegador.

Isso significa que:

- Os dados permanecem salvos no mesmo navegador e perfil utilizado.
- Os registros não são compartilhados automaticamente entre computadores.
- A limpeza dos dados do navegador pode apagar os registros.
- O modo anônimo ou privativo não deve ser utilizado para registros permanentes.
- Recomenda-se exportar periodicamente os dados em CSV.
- Esta versão ainda não possui autenticação, API ou banco de dados central.

## Limitação da Versão Atual

O sistema funciona como um protótipo funcional de uso local.

Para utilização simultânea por vários operadores, máquinas ou computadores, será necessário implementar:

- API de backend.
- Banco de dados central.
- Autenticação de usuários.
- Controle de permissões.
- Registro de auditoria no servidor.
- Backup automático.
- Sincronização em tempo real.
- Hospedagem da aplicação e da API em ambiente corporativo.

## Finalidade

Este sistema tem como objetivo facilitar o apontamento e a análise dos tempos das máquinas, tornando o acompanhamento operacional mais rápido, padronizado e acessível.

Os dados consolidados podem apoiar análises relacionadas a:

- Tempo produtivo.
- Tempo de parada.
- Tempo de manutenção.
- Utilização das máquinas.
- Distribuição das atividades por processo.
- Histórico operacional.
- Identificação de gargalos e períodos de indisponibilidade.

## Identidade Visual

O sistema utiliza a identidade visual da Fischer®, com cores institucionais, logotipo corporativo, cartões informativos, elementos responsivos e apresentação compatível com o padrão dos sistemas internos da empresa.

## Direitos Reservados

**Fischer® 2026 — Todos os direitos reservados.**

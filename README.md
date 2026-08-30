# SGLE — Sistema de Gestão de Lista de Espera

🇧🇷 Português | [🇺🇸 English](README.en.md) | [🇪🇸 Español](README.es.md)

**Início:** 2025  
**Versão:** 1.0.0  
**Status:** Em desenvolvimento contínuo  
**Desenvolvedor:** Filipe G Morais

## 💼 Origem do projeto

O SGLE surgiu em **2025** a partir da identificação de uma **demanda reprimida** e da necessidade de melhorar a organização e o acompanhamento de pessoas aguardando vagas em atividades e serviços.

A necessidade foi discutida inicialmente em uma **reunião de colegiado da gestão**. A partir desse contexto, o planejamento da solução foi desenvolvido em conjunto com a **coordenação pedagógica**, e a elaboração das regras e necessidades do fluxo contou com a colaboração de **duas profissionais da área de serviço social**.

O desafio prático de transformar um processo predominantemente manual em um fluxo digital estruturado foi um dos fatores que impulsionaram o aprofundamento nos estudos de **automação, Google Workspace e Google Apps Script**.

Assim, o SGLE passou a reunir duas dimensões:

- uma resposta a uma necessidade real de gestão e organização;
- um projeto prático de aprendizagem e evolução em automação.

Para preservar a privacidade e a identidade da organização original, este repositório utiliza uma abordagem genérica e não identifica a instituição onde a demanda foi observada.

## Objetivo

O Sistema de Gestão de Lista de Espera (SGLE) tem como objetivo digitalizar e organizar o cadastro de educandos que aguardam disponibilidade de vagas em atividades e serviços com disponibilidade limitada.

O sistema substitui o preenchimento manual da lista de espera por um fluxo integrado entre Google Forms e Google Sheets, com evolução planejada para automações em Google Apps Script, indicadores, dashboard e apoio à gestão de vagas.

O SGLE **não substitui a matrícula presencial**. O formulário registra o educando na lista de espera; a matrícula continua sendo realizada presencialmente e as oficinas são definidas de acordo com a disponibilidade de vagas no momento da matrícula.

## Missão

Transformar o processo manual de cadastro da lista de espera em um sistema simples, padronizado e automatizado, reduzindo retrabalho, erros de preenchimento e tempo administrativo, ao mesmo tempo em que melhora a qualidade dos indicadores de gestão.

## Público-alvo

- ONGs e OSCs
- Projetos sociais
- Instituições educacionais
- Centros comunitários
- Secretarias e órgãos públicos

## Objetivos específicos

- Digitalizar o cadastro da lista de espera.
- Padronizar os dados coletados pela equipe.
- Registrar automaticamente data e hora do cadastro.
- Calcular idade automaticamente.
- Organizar a fila por data de inscrição.
- Apoiar a convocação para matrícula presencial.
- Registrar status do processo.
- Gerar indicadores de demanda reprimida.
- Apoiar a análise da ocupação e disponibilidade das oficinas.
- Permitir evolução futura para módulos de matrícula, frequência e gestão de oficinas.

## Fluxo operacional

```text
Responsável / família
        ↓
Equipe responsável
        ↓
Cadastro na Lista de Espera
        ↓
Google Forms
        ↓
Google Sheets
        ↓
Tratamento e organização dos dados
        ↓
Lista de Espera / Demanda Reprimida
        ↓
Surgimento de vaga
        ↓
Convocação
        ↓
Processo de ingresso presencial
        ↓
Definição das oficinas conforme disponibilidade
```

## Arquitetura prevista

```text
Google Forms
      ↓
Google Sheets
      ↓
Google Apps Script
      ↓
Camada de dados / regras de negócio
      ↓
Dashboard administrativo
      ↓
Relatórios
      ↓
PWA (futuro)
```

## Tecnologias

- Google Forms
- Google Sheets
- Google Apps Script
- HTML5
- CSS3
- JavaScript
- Google Charts
- Material Icons

## Estrutura planejada

```text
SGLE/
├── README.md
├── CHANGELOG.md
├── ROADMAP.md
├── DOCUMENTACAO.md
├── .gitignore
│
├── backend/
│   ├── Code.gs
│   ├── Config.gs
│   ├── Data.gs
│   ├── Dashboard.gs
│   └── Utils.gs
│
├── frontend/
│   ├── index.html
│   ├── css.html
│   ├── javascript.html
│   └── charts.html
│
└── documentacao/
    ├── arquitetura.md
    ├── formulario.md
    ├── planilha.md
    ├── regras-negocio.md
    ├── indicadores.md
    ├── seguranca.md
    └── fluxo.md
```

Na fase inicial, a prioridade é documentação e funcionamento do fluxo Forms → Sheets. Os arquivos de código serão adicionados conforme as automações forem implementadas.

## Regra fundamental

**Lista de Espera ≠ Matrícula.**

O SGLE registra a intenção de ingresso e organiza a demanda reprimida. A matrícula é presencial e somente ocorre quando houver disponibilidade e após os procedimentos definidos pela equipe responsável.

## Privacidade e proteção de dados

O projeto poderá tratar dados pessoais e informações potencialmente sensíveis, incluindo deficiência e uso de medicação. O repositório público deve conter somente código, documentação e dados fictícios/de exemplo.

Nunca devem ser publicados no GitHub:

- nomes reais de educandos;
- nomes de responsáveis;
- telefones;
- endereços ou dados que permitam identificação indevida;
- informações de deficiência ou saúde;
- planilhas reais utilizadas no contexto de origem;
- credenciais, tokens ou chaves de API.

A implementação deve observar as políticas e procedimentos aplicáveis ao contexto de implementação e os princípios aplicáveis da LGPD, especialmente necessidade, finalidade, segurança e controle de acesso.

## Licença

Projeto desenvolvido a partir de uma necessidade real de gestão e organização, com finalidade prática, educacional e de demonstração técnica. A definição de licença aberta específica será realizada em etapa posterior, caso necessário.

---

## Author

**Filipe G Morais**

GitHub: https://github.com/sayjinblackbelt  
Repository: https://github.com/sayjinblackbelt/waiting-list-management-system

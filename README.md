# SGLE — Sistema de Gestão de Lista de Espera

**Versão:** 1.0.0  
**Status:** Em desenvolvimento  
**Desenvolvedor:** Filipe Gimenes de Morais

## Objetivo

O Sistema de Gestão de Lista de Espera (SGLE) tem como objetivo digitalizar e organizar o cadastro de educandos que aguardam disponibilidade de vagas nas atividades da instituição.

O sistema substitui o preenchimento manual da lista de espera por um fluxo integrado entre Google Forms e Google Sheets, com evolução planejada para automações em Google Apps Script, indicadores, dashboard e apoio à gestão de vagas.

O SGLE **não substitui a matrícula presencial**. O formulário registra o educando na lista de espera; a matrícula continua sendo realizada presencialmente e as oficinas são definidas de acordo com a disponibilidade de vagas no momento da matrícula.

## Missão

Transformar o processo manual de cadastro da lista de espera em um sistema simples, padronizado e automatizado, reduzindo retrabalho, erros de preenchimento e tempo administrativo, ao mesmo tempo em que melhora a qualidade dos indicadores institucionais.

## Público-alvo

- Fundação Eufraten
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

## Fluxo institucional

```text
Responsável / família
        ↓
Equipe da instituição
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
Matrícula presencial
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

O SGLE registra a intenção de ingresso e organiza a demanda reprimida. A matrícula é presencial e somente ocorre quando houver disponibilidade e após os procedimentos institucionais definidos pela equipe.

## Privacidade e proteção de dados

O projeto poderá tratar dados pessoais e informações potencialmente sensíveis, incluindo deficiência e uso de medicação. O repositório público deve conter somente código, documentação e dados fictícios/de exemplo.

Nunca devem ser publicados no GitHub:

- nomes reais de educandos;
- nomes de responsáveis;
- telefones;
- endereços ou dados que permitam identificação indevida;
- informações de deficiência ou saúde;
- planilhas reais da instituição;
- credenciais, tokens ou chaves de API.

A implementação deve observar as políticas internas da instituição e os princípios aplicáveis da LGPD, especialmente necessidade, finalidade, segurança e controle de acesso.

## Licença

Projeto desenvolvido para uso educacional e institucional. A definição de licença aberta específica será realizada em etapa posterior, caso necessário.

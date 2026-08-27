# Regras de Negócio

## RN01 — Lista de Espera

O cadastro realizado pelo formulário representa uma inscrição na Lista de Espera, não uma matrícula.

## RN02 — Matrícula presencial

A matrícula continua sendo realizada presencialmente pela instituição.

## RN03 — Disponibilidade de oficinas

A oficina frequentada pelo educando é definida no processo de matrícula conforme disponibilidade de vagas e critérios institucionais.

## RN04 — Data de inscrição

A data/hora de inscrição deve ser registrada automaticamente pelo Google Forms e não digitada pelo profissional.

## RN05 — Idade

A idade deve ser derivada da data de nascimento e atualizada automaticamente.

## RN06 — Contatos

O cadastro deve possuir pelo menos dois meios de contato do responsável ou da rede familiar, conforme procedimento institucional.

## RN07 — Status

O acompanhamento poderá utilizar, inicialmente, os estados:

- Lista de espera
- Convocado
- Matriculado
- Não compareceu
- Desistiu
- Inativo

A lista definitiva de status será validada com a equipe antes da automação.

## RN08 — Histórico

Mudanças relevantes de status devem preservar as datas correspondentes para permitir auditoria e indicadores.

## RN09 — Duplicidade

O sistema deverá futuramente identificar possíveis cadastros duplicados por combinação de dados, sem apagar automaticamente registros.

## RN10 — Dados sensíveis

Informações sobre deficiência e medicação devem ter acesso restrito e tratamento compatível com a finalidade institucional. Nunca devem ser expostas em dashboards públicos ou repositórios de código.

## RN11 — Dados do formulário

A aba de respostas originais deve ser preservada. Processamentos posteriores devem utilizar camadas derivadas.

## RN12 — Prioridade

A ordem cronológica de inscrição não deve ser interpretada automaticamente como prioridade social enquanto não houver uma regra institucional formalizada.

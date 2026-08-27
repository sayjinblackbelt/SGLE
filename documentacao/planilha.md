# Planilha — Arquitetura de Dados

## Princípio

A aba criada automaticamente pelo Google Forms deve ser considerada a fonte de entrada bruta das respostas. A equipe não deve depender de edição manual dessa aba para o funcionamento do formulário.

## Abas previstas

### 1. Respostas do Formulário

Aba gerenciada pelo Google Forms.

Contém o carimbo de data/hora e as respostas do formulário.

Não utilizar essa aba como área principal de trabalho administrativo.

### 2. Lista de Espera

Área operacional para organização e acompanhamento da demanda reprimida.

Campos derivados/administrativos previstos:

- Número da inscrição;
- Data de inscrição;
- Nome do educando;
- Sexo;
- Data de nascimento;
- Idade;
- Bairro;
- Escola;
- Período escolar;
- Responsável;
- Contato principal;
- Contato reserva;
- Deficiência;
- Informação complementar de deficiência, quando aplicável;
- Medicação, quando aplicável;
- Status;
- Data de convocação;
- Resultado da convocação;
- Data da matrícula;
- Observações.

### 3. Oficinas

Cadastro das oficinas, vagas e informações de gestão.

### 4. Config

Listas auxiliares, parâmetros e constantes utilizadas pelas automações.

### 5. Dados

Tabelas auxiliares e dados normalizados necessários às rotinas do sistema.

### 6. Dashboard

Indicadores gerenciais e gráficos.

## Dados derivados

### Idade

Calculada automaticamente a partir da data de nascimento. Não deve ser digitada pelo profissional.

### Data de inscrição

Obtida do carimbo de data/hora gerado pelo Google Forms.

### Ordem da lista

A ordem inicial deve considerar a data/hora de inscrição. Regras de prioridade institucional, se existirem, deverão ser documentadas antes de automatizadas.

### Tempo de espera

Pode ser calculado em dias a partir da data de inscrição até a data atual ou até a convocação.

## Integridade

A resposta original do formulário deve permanecer preservada. Tratamentos, filtros e indicadores devem ocorrer em abas derivadas ou por meio de Apps Script.

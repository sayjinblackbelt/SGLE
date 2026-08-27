# Arquitetura do SGLE

## Arquitetura inicial

O SGLE será desenvolvido em camadas, permitindo começar com ferramentas já disponíveis e evoluir sem reconstruir o projeto.

```text
[Profissional]
      ↓
[Google Forms]
      ↓
[Google Sheets — respostas]
      ↓
[Camada de dados / Apps Script]
      ↓
[Lista de Espera]
      ↓
[Dashboard / Relatórios]
```

## Camadas

### Entrada

Google Forms, utilizado como interface padronizada para cadastro.

### Persistência

Google Sheets, utilizado inicialmente como base de dados operacional.

### Lógica

Google Apps Script, responsável por cálculos, validações, sincronização, indicadores e automações futuras.

### Apresentação

Inicialmente a própria planilha. Em fase posterior, dashboard HTML/CSS/JavaScript publicado como Web App.

### Visualização

Google Charts ou biblioteca equivalente para indicadores e gráficos.

## Backend planejado

### Code.gs

Ponto de entrada das funções e gatilhos.

### Config.gs

Constantes, nomes de abas, listas e parâmetros.

### Data.gs

Leitura, escrita, normalização e consulta de dados.

### Dashboard.gs

Preparação dos indicadores para a interface.

### Utils.gs

Funções utilitárias compartilhadas.

## Frontend planejado

### index.html

Estrutura da interface.

### css.html

Estilos.

### javascript.html

Interações e chamadas ao backend.

### charts.html

Gráficos e componentes de visualização.

## Princípios técnicos

- Separar entrada, tratamento e apresentação.
- Evitar lógica duplicada.
- Centralizar constantes em Config.gs.
- Não expor dados sensíveis no frontend sem necessidade.
- Não colocar credenciais no código.
- Preservar a fonte original dos dados.
- Preferir funções pequenas e reutilizáveis.
- Documentar alterações relevantes.

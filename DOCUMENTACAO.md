# Documentação Geral — SGLE

## 1. Contexto

A instituição utiliza uma planilha para registrar manualmente educandos que procuram atendimento e permanecem em lista de espera quando não há vaga disponível.

O processo atual depende do preenchimento manual por profissionais, o que pode gerar retrabalho, inconsistências de formato, campos esquecidos e dificuldade para produzir indicadores.

O SGLE nasce para digitalizar essa etapa sem alterar, inicialmente, o processo de matrícula presencial.

## 2. Escopo da V1

A primeira versão contempla:

1. Cadastro padronizado na Lista de Espera por meio de Google Forms.
2. Registro automático de data e hora.
3. Armazenamento automático das respostas em Google Sheets.
4. Organização da lista de espera.
5. Preparação de campos administrativos para acompanhamento.
6. Base para indicadores de demanda reprimida.

O cálculo automático da idade será implementado na **Fase 3 — Automação básica**, conforme o ROADMAP.md.

## 3. Fora do escopo inicial

- Matrícula online.
- Escolha definitiva de oficinas pelo responsável.
- Confirmação automática de vaga.
- Controle de frequência.
- Alteração automática de turma.
- Prontuário social completo.
- Integração com sistemas municipais externos.

## 4. Princípio de funcionamento

O formulário é preenchido por profissionais da instituição a partir das informações fornecidas pelo responsável.

A data de inscrição é gerada automaticamente pelo Google Forms por meio do carimbo de data/hora. A idade não deve ser digitada manualmente; será calculada a partir da data de nascimento durante a etapa de automação.

## 5. Relação com as oficinas

As oficinas não são escolhidas como matrícula definitiva no cadastro da Lista de Espera. A oferta depende da existência de vagas no momento da matrícula presencial.

Oficinas atualmente consideradas no sistema:

- EducArte
- Vencendo Desafios
- Refletir e Brincar
- Yoga com Histórias
- Educação Ambiental
- Artes Plásticas
- Ballet
- Contação de Histórias
- Informática Educacional
- Informática PMT
- Mídias Digitais & Design Gráfico
- Teatro
- Canto Coral
- Música (Instrumentos)
- Vôlei
- Futebol
- Comunicação PMT
- Judô
- Desenho Artístico
- Jazz
- Em Cena

Essas oficinas serão mantidas como cadastro/configuração do sistema, mas a atribuição efetiva ao educando pertence ao processo presencial de matrícula.

## 6. Evolução planejada

Após estabilizar a V1, o sistema poderá receber módulos para:

- convocação;
- matrícula presencial;
- controle de oficinas frequentadas;
- quantidade de dias/vezes de participação;
- origem do atendimento (PMT/projeto);
- vagas por oficina;
- frequência;
- indicadores institucionais;
- dashboard;
- relatórios.

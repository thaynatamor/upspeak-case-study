# Visão de dados e informações

[← Voltar à apresentação](../README.md)

## Por que os dados fazem parte do produto

Uma plataforma educacional precisa preservar o contexto de cada informação: de quem é uma entrega, a qual proposta ela responde e como ela se relaciona ao acompanhamento do estudante.

Esta página descreve conceitos do domínio. Não representa o esquema físico do banco, nomes reais de tabelas ou suas políticas de acesso.

| Conceito | Papel no domínio | Relação que precisa ficar clara |
| --- | --- | --- |
| Aluno | Pessoa que participa do aprendizado | Seu vínculo de atendimento |
| Turma ou atendimento particular | Contexto das aulas | Os estudantes atendidos |
| Material | Conteúdo de apoio | O contexto de aprendizagem |
| Atividade ou avaliação | Proposta pedagógica | O público a que se destina |
| Entrega | Resposta do estudante | O aluno e a proposta correspondentes |
| Correção | Retorno sobre a entrega | A resposta que está sendo analisada |
| Boletim | Acompanhamento pedagógico | O estudante e o período correspondente |

## Decisões que ajudam a interpretar as informações

**Identificação.** A interface precisa apresentar nomes compreensíveis, enquanto identificadores internos preservam os relacionamentos.

**Contexto de atendimento.** Aulas particulares e turmas são contextos diferentes. O produto deve apresentar essa distinção com clareza.

**Período e status.** Informações de período, entrega e correção ajudam a localizar o que precisa de atenção. Seus significados devem permanecer consistentes entre as telas.

**Origem do resultado.** Notas de tarefas e registros manuais de acompanhamento têm origens diferentes, mesmo quando aparecem no mesmo boletim.

## Perguntas para uma evolução analítica

- Quais propostas recebem mais entregas dentro do prazo?
- Quais temas concentram dificuldades recorrentes?
- Como a participação varia entre os períodos?
- Quais exercícios complementares são mais utilizados?

Essas perguntas são possibilidades de análise futura. Este repositório não contém bases de alunos, dashboards analíticos ou indicadores medidos.

## Dados para apresentação

Qualquer exemplo público deve utilizar registros inteiramente fictícios, criados para demonstração. Retirar apenas o nome de um registro real não é suficiente para tornar todo o seu conteúdo apropriado para divulgação.

# Estudo de caso — UpSpeak

## Contexto

A UpSpeak nasceu para apoiar o trabalho da professora Isadora Amorim. O desafio era reunir a apresentação do curso e a organização das aulas em uma experiência acessível para adultos, crianças e responsáveis.

**Idealização e desenvolvimento: Thayná Tamor.** A definição do conteúdo e o acompanhamento pedagógico pertencem à professora.

## Problema e solução

| Necessidade | Resposta no produto |
| --- | --- |
| Apresentar o trabalho da professora | Site com informações do curso, conteúdo e avaliações |
| Atender turmas e alunos particulares | Organização de matrículas e vínculos de atendimento |
| Disponibilizar materiais e tarefas | Portal com atividades, avaliações e anexos |
| Acompanhar entregas e correções | Fluxos de resposta do aluno e revisão pela professora |
| Acompanhar o aprendizado | Boletins e informações de desempenho |
| Incentivar a prática | English Lab com atividades organizadas por conteúdo |
| Usar em diferentes dispositivos | Interface responsiva para computador, celular e tablet |

## Decisões de implementação

**Separação de experiências.** A página pública apresenta a escola; o portal concentra as operações pedagógicas. Os perfis de professora e aluno têm necessidades diferentes de navegação e acesso.

**Dados persistentes.** A aplicação utiliza Supabase para autenticação, dados e arquivos do portal. As avaliações públicas do site utilizam Cloudflare D1. Essas avaliações públicas são distintas das avaliações pedagógicas dos alunos.

**Fluxos de acompanhamento.** Atividades, respostas e correções fazem parte do mesmo processo de aprendizagem. A organização dessas informações permite acompanhar o aluno em turma ou em atendimento particular.

**Responsividade.** A adaptação para telas menores faz parte do produto, inclusive nos formulários e na navegação do portal.

## Competências demonstradas

- Transformação de requisitos de uma usuária real em funcionalidades.
- Desenvolvimento de interfaces com React e Tailwind CSS.
- Integração de autenticação, banco de dados e armazenamento.
- Organização de entidades e relacionamentos para um domínio educacional.
- Integração de geração de PDF e recursos de interação.
- Preparação de build e configuração de hospedagem.
- Evolução do produto a partir de feedback.

## Limites da apresentação

Este material é descritivo e foi preparado a partir do projeto fornecido. Não constitui auditoria de segurança nem validação independente de todos os fluxos em produção. Não são divulgados dados de alunos, credenciais ou configurações operacionais.

## Próximas evoluções possíveis

Indicadores de acompanhamento pedagógico, análise de uso dos exercícios e testes adicionais dos principais fluxos podem apoiar a evolução do produto. São possibilidades, não resultados já implementados ou medidos.

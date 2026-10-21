<p align="center"><img src="assets/logo.svg" alt="UpSpeak" width="260"></p>

# UpSpeak — plataforma de ensino de inglês

**Idealização e desenvolvimento: Thayná Tamor**  
**Professora e responsável pedagógica: Isadora Amorim**

Uma solução criada para uma necessidade real: organizar as aulas de inglês da minha esposa, Isadora, e aproximar a experiência da professora da rotina de cada estudante.

A UpSpeak reúne a apresentação do curso e um portal com experiências para professora e alunos, incluindo atendimento em turmas e aulas particulares.

[Acessar o site público](https://upspeak.isadoraamorim.workers.dev) · [Ler o estudo de caso](docs/estudo-de-caso.md) · [Conhecer a arquitetura](docs/arquitetura.md)

## O que o projeto contempla

- Site responsivo para apresentar a professora, o curso e avaliações públicas.
- Portal com autenticação e acesso conforme o perfil do usuário.
- Gestão de alunos, matrículas em turmas e atendimento particular.
- Organização de aulas, materiais e links de encontros ao vivo.
- Atividades e avaliações, envio de respostas e anexos, correção pela professora.
- Boletins com resultados e acompanhamento pedagógico.
- English Lab com exercícios organizados para a prática de inglês.
- Geração de documentos em PDF e interfaces adaptadas para celular e tablet.

## Tecnologias

| Camada | Tecnologias utilizadas |
| --- | --- |
| Interface | React, Tailwind CSS, componentes de interface e Lucide |
| Aplicação e build | Vinext, Vite e estrutura compatível com o App Router |
| Autenticação e dados do portal | Supabase Auth, PostgreSQL e Storage |
| Hospedagem e execução | Cloudflare Workers |
| Avaliações públicas do site | Cloudflare D1 e Drizzle |
| Documentos | pdf-lib |

## Meu papel

Trabalhei na tradução das necessidades da professora em fluxos de interface, organização das informações, integração com serviços de autenticação e persistência e preparação para publicação. O projeto evoluiu a partir do uso e das necessidades pedagógicas.

## Sobre este repositório

Este é um **estudo de caso para portfólio**. A documentação descreve o produto e suas decisões técnicas. O código-fonte da aplicação permanece em repositório privado.

O site vinculado é o ambiente público da escola; não há credenciais de demonstração neste material. Telas internas e dados de alunos não são publicados aqui.

Não são apresentados números de usuários, ganhos de produtividade ou resultados comerciais sem medição.

© 2026 Thayná Tamor. Consulte [NOTICE.md](NOTICE.md).

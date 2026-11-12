<p align="center">
  <img src="docs/01-inicio.jpg" alt="Rumo ao Embarque — página inicial" width="100%">
</p>

<h1 align="center">🛢️ Rumo ao Embarque</h1>

<p align="center">
  <b>Plataforma gamificada de preparação para o concurso de nível técnico da Petrobras.</b><br>
  Questões reais, simulados cronometrados, material de estudo e um avatar 3D que evolui junto com o aluno.
</p>

<p align="center">
  <a href="https://rumoaoembarque.pages.dev"><img alt="Acessar a plataforma" src="https://img.shields.io/badge/acessar-rumoaoembarque.pages.dev-f97316?style=for-the-badge"></a>
  <img alt="Status" src="https://img.shields.io/badge/status-em%20produção-22c55e?style=for-the-badge">
  <img alt="Código" src="https://img.shields.io/badge/código-privado-64748b?style=for-the-badge">
</p>

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
  <img alt="Firebase" src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black">
  <img alt="three.js" src="https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white">
  <img alt="Cloudflare Pages" src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
</p>

> **Este repositório é uma vitrine.** O código-fonte da plataforma é privado; aqui estão a descrição do projeto, as telas e as decisões técnicas.

---

## 📌 Sobre o projeto

O concurso da Petrobras para nível técnico tem muitos candidatos e um edital longo, dividido em 16 ênfases. Estudar sozinho por PDF cansa rápido. O **Rumo ao Embarque** transforma essa preparação em um jogo: cada questão resolvida, meta diária cumprida e desafio vencido dá XP, o aluno sobe de nível (1 a 80) e libera equipamentos para o seu avatar, como crachá, botas e óculos de proteção, até o uniforme completo de quem embarca.

A plataforma está **no ar e com usuários reais**. Foi idealizada, desenhada e desenvolvida por mim, do conteúdo ao deploy.

## 📊 Em números

| | |
|---|---|
| **3.334** questões | 2.035 de provas reais e 1.299 inéditas comentadas |
| **648** simulados | provas completas, por assunto, só específicas, só básicas e relâmpago |
| **1.058** questões rápidas | exclusivas para desafios entre colegas |
| **330** flashcards | inéditos, além dos itens das provas reais |
| **28** resumos | Português e Matemática, organizados por área e assunto |
| **16** ênfases | todas as do último edital, com mapa do edital por ênfase |
| **80** níveis | com itens de avatar liberados por progresso |

## ✨ Funcionalidades

**Estudo**
- 📝 **Banco de questões** com filtros por disciplina, assunto, banca, ano e ênfase, e comentário em cada questão inédita
- ⏱️ **Simulados cronometrados** com correção automática e desempenho por disciplina
- 📖 **Material de estudo** organizado em disciplina → área → assunto (ex.: *Português → Interpretação de texto*), com botão "Praticar este assunto" que leva direto às questões
- 🗂️ **Flashcards** de certo/errado para revisão rápida
- 📅 **Plano de estudos** gerado a partir da data da prova, do tempo disponível por dia e da ênfase do aluno
- 🗺️ **Mapa do edital** e painel de desempenho por tópico

**Gamificação**
- 🎮 XP, níveis, missões diárias e sequência de dias estudados
- 🧍 **Avatar 3D** personalizável (corpo, rosto, cabelo, roupa, acessórios, pets), renderizado com three.js
- 🛍️ Loja de itens do avatar com pagamento via **Pix**: o BR Code (com CRC16) é gerado no próprio app

**Social**
- 🏆 Ranking semanal, mensal e geral, com filtro por ênfase
- 💬 Mural da turma, chat, colegas de estudo, desafios 1×1 e duplas
- 🔔 Central de notificações (amizades, desafios, novidades, compras)
- 🛡️ Moderação: denunciar, bloquear e painel da monitoria para tratar denúncias

**Plataforma**
- 👩‍💼 Painel administrativo da monitoria: alunos, acessos, pedidos da loja, novidades e denúncias
- 📱 **PWA**: instalável na tela inicial do celular (Android e iPhone)
- 🔐 Login com Google e e-mail, 7 dias de teste grátis e planos de assinatura
- ⚖️ Política de privacidade alinhada à **LGPD**

## 🖼️ Telas

<table>
  <tr>
    <td><img src="docs/02-painel.jpg" alt="Painel do dia"><p align="center"><sub>Painel do dia: meta, nível e avatar</sub></p></td>
    <td><img src="docs/03-banco.jpg" alt="Banco de questões"><p align="center"><sub>Banco de questões com filtros</sub></p></td>
  </tr>
  <tr>
    <td><img src="docs/04-material.jpg" alt="Material de estudo"><p align="center"><sub>Material de estudo por área</sub></p></td>
    <td><img src="docs/05-resumo.jpg" alt="Resumo"><p align="center"><sub>Leitura de um resumo</sub></p></td>
  </tr>
  <tr>
    <td><img src="docs/06-simulados.jpg" alt="Simulados"><p align="center"><sub>Simulados por tipo</sub></p></td>
    <td><img src="docs/07-avatar.jpg" alt="Avatar 3D"><p align="center"><sub>Editor do avatar 3D</sub></p></td>
  </tr>
  <tr>
    <td><img src="docs/08-ranking.jpg" alt="Ranking"><p align="center"><sub>Ranking e mural da turma</sub></p></td>
    <td><img src="docs/09-plano.jpg" alt="Plano de estudos"><p align="center"><sub>Plano de estudos</sub></p></td>
  </tr>
</table>

<p align="center">
  <img src="docs/10-celular.jpg" alt="Versão para celular" width="300"><br>
  <sub>Versão para celular (PWA)</sub>
</p>

## 🧱 Arquitetura e tecnologias

| Camada | Tecnologia | Uso |
|---|---|---|
| Front-end | **React 18 + Vite** | SPA com roteador por hash e estado global próprio (`useSyncExternalStore`) |
| 3D | **three.js** | Avatar em voxel, com animações e itens equipáveis |
| Autenticação | **Firebase Auth** | Login com Google e e-mail/senha |
| Banco de dados | **Cloud Firestore** | Progresso, perfis, social e loja, protegidos por regras de segurança validando cada campo |
| Hospedagem | **Cloudflare Pages** | Deploy estático com `_worker.js` para rotas especiais |
| Pagamentos | **Pix (BR Code)** | Payload EMV e CRC16 gerados no cliente, com confirmação pela monitoria |
| Conteúdo | **Python** | Pipeline que gera, valida e monta o banco de questões, simulados e resumos em JSON |
| Testes | **Playwright** | Testes ponta a ponta dos fluxos principais, com Firebase simulado |

**Algumas decisões técnicas**
- **Conteúdo como dados.** Questões, simulados e resumos são JSON carregados sob demanda. O app não precisa ser reconstruído para crescer o banco.
- **Geração validada.** As questões inéditas saem de geradores em Python que conferem gabarito único, alternativas sem repetição e distratores plausíveis antes de entrar no banco.
- **Segurança no servidor.** As regras do Firestore limitam o que cada aluno pode gravar: só o próprio progresso, sem alterar XP de outros, com tamanhos e tipos validados.
- **Renderização segura.** O material de estudo usa um renderizador de Markdown próprio, sem HTML cru.
- **Notificações sem custo extra.** As notificações são derivadas dos dados que o app já escuta, e o estado de "lida" fica no aparelho.

## 🗺️ Próximos passos

- [ ] Material de estudo das disciplinas específicas por ênfase
- [ ] Página "Reta final" com revisão intensiva
- [ ] Pagamento por cartão

## 👤 Autor

**Plinio Martins**: idealização, design, desenvolvimento e conteúdo.

[![GitHub](https://img.shields.io/badge/GitHub-pliniomartins-181717?style=flat-square&logo=github)](https://github.com/pliniomartins)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Plinio_Martins-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/pl%C3%ADnio-marcus-546652179)
[![Instagram](https://img.shields.io/badge/Instagram-@rumoaoembarquepetro-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/rumoaoembarquepetro)

## ⚖️ Licença

© 2026 Plinio Martins. **Todos os direitos reservados.**

Este repositório existe apenas para apresentar o projeto. O código-fonte, o banco de questões, os textos e as imagens da plataforma não estão licenciados para cópia, modificação ou redistribuição.

*Projeto independente, sem vínculo com a Petrobras.*

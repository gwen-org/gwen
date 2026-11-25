<!-- Banner opcional: suba a imagem neste repositório (público) e cole o caminho aqui. Não use o .github-private: as imagens não carregam para quem não é membro. -->

<div align="center">

<h3> G.W.E.N. · Gestão de Wellness, Eficiência e Navegação </h3>

<p>Seu ambiente de trabalho em um clique. Sua pausa levada a sério.</p>

![Tipo](https://img.shields.io/badge/tipo-aplicativo-121214?style=for-the-badge)
![Status](https://img.shields.io/badge/status-beta-171717?style=for-the-badge)
![Escopo](https://img.shields.io/badge/escopo-pessoal-171717?style=for-the-badge)
![Plataforma](https://img.shields.io/badge/plataforma-windows-171717?style=for-the-badge)
![Versão](https://img.shields.io/badge/versão-0.9.3-171717?style=for-the-badge)
![Licença](https://img.shields.io/badge/licença-proprietária-171717?style=for-the-badge)
![Recife](https://img.shields.io/badge/Recife%20%C2%B7%20Brazil-171717?style=for-the-badge)

<a href="https://github.com/gwen-org/gwen/releases/latest">
  <img src="https://img.shields.io/badge/Baixar-instalador%20Windows-121214?style=for-the-badge&logo=windows&logoColor=FFFFFF" />
</a>
<a href="https://github.com/gwen-org/gwen/issues/new/choose">
  <img src="https://img.shields.io/badge/Abrir-issue-121214?style=for-the-badge&logo=github&logoColor=FFFFFF" />
</a>

</div>

<br>

<h3> $ sobre o projeto </h3>

A **G.W.E.N.** é um assistente desktop para quem trabalha com muitos projetos ao mesmo tempo. Ela junta três coisas que normalmente ficam espalhadas: **abrir o ambiente de cada projeto com um clique**, **contar o tempo dedicado a cada um** e **tratar a pausa como parte do trabalho**.

Um projeto é um conjunto de pastas, links e apps. Por isso serve a quem programa, estuda, escreve ou desenha. O que a diferencia é o descanso: a barra de pausa **enche** em vez de contar para trás.

O app nasceu de uma necessidade real e segue em uso diário. Cada versão sai de um problema que apareceu na prática.

<div align="center">

| | **Local** | **Nuvem (opcional)** |
|:---:|:---:|:---:|
| **Dados** | SQLite no computador, sem conta e sem internet | seu próprio Supabase, com login Google ou e-mail |
| **Backup** | JSON manual e cópia automática a cada versão | os dados ficam na nuvem, e sair da conta não apaga nada |
| **Situação** | padrão do app | avançado, para quem quiser |

</div>

<br>

<h3> $ o que ela faz </h3>

<div align="center">

| **PROJETOS** | **TEMPO** | **DESCANSO E SAÚDE** | **ANÁLISE** |
|:---:|:---:|:---:|:---:|
| categorias, frentes e painel em árvore | sessões em paralelo, sem somar a mesma hora duas vezes | modo pausa: café, refeição, leitura e respiro | relatório por semana, mês ou 30 dias, com CSV |
| **Começar agora**: abre pastas, links, apps e roda comandos | linha do tempo com os trechos em que as sessões rodaram juntas | modo saúde: água, alongamento e olhos | mapeamento opcional de apps e jogos |
| status do Git direto no card | **onde parei**: a nota do próximo passo | alertas de saúde, cada um com a sua fonte | perfil com mapa de atividade e hábitos |
| tarefas em kanban e lista, com Issues do GitHub | bolha, bandeja e **Ctrl + K** | sessão esquecida: o app pergunta quanto foi de verdade | ambientes de uso: Geral, TI, Design e Acadêmico |

</div>

<br>

<h3> $ como o fluxo se encaixa </h3>

```
projeto (pastas, links, apps, comando)
       │
       ▼
Começar agora ─── abre o ambiente e inicia a sessão
       │
       ├──► pausa ........... barra que enche, vale para todas as sessões
       ├──► tarefas ......... kanban, lista e Issues do GitHub
       └──► mapeamento ...... programa em foco (opcional, só neste computador)
       │
       ▼
Encerrar ─── pergunta onde você parou
       │
       ▼
relatório · linha do tempo · perfil e hábitos
```

<br>

<h3> $ identidade visual </h3>

A identidade da G.W.E.N. é **Noir**: preto, branco e cinzas, do logo ao wallpaper. Qualquer outra identidade é de quem usa, criada no tema **Personalizado** por HEX ou JSON. Modo, cor e estilo são escolhas independentes.

<div align="center">

| | **Opções** |
|:---:|:---:|
| **Modo** | claro, escuro ou o do sistema |
| **Cor** | Noir ou Personalizado, com 9 tokens |
| **Estilo** | Moderno (cantos arredondados, vidro) ou Terminal (mono, caixa alta, scanlines) |

</div>

<br>

<h3> $ privacidade </h3>

O código-fonte não é público, então esta lista é o compromisso do que o app faz com os seus dados.

- Projetos, sessões, tarefas e mapeamento **nunca saem do computador** no modo local.
- O mapeamento é opcional e guarda só o nome do programa em primeiro plano.
- A versão distribuída envia um **registro da instalação** ao servidor da autora: código aleatório, nome, foto, versão, sistema e idioma, só para contar quem usa e em qual versão. Nunca vão projetos, tempos, pastas ou e-mail. Dá para desligar em Ajustes, Dados, e isso apaga o registro lá.
- No modo conta (opcional), os dados ficam no Supabase que você mesmo conectou, não no servidor da autora.
- Os alertas de saúde são lembretes com base em referências publicadas, não diagnóstico.

<br>

<h3> $ feedback e issues </h3>

Este repositório é o canal público da G.W.E.N.: aqui ficam as **Releases** (instalador e atualizações) e as **Issues**.

<div align="center">

| **QUANDO** | **O QUE ABRIR** | **O QUE INCLUIR** |
|:---:|:---:|:---:|
| algo não funcionou | [relatar um bug](https://github.com/gwen-org/gwen/issues/new?template=bug_report.yml) | versão, sistema, o que aconteceu e como reproduzir |
| tem uma ideia | [sugerir uma melhoria](https://github.com/gwen-org/gwen/issues/new?template=sugestao.yml) | o problema que você tem e como imaginou a solução |

</div>

- Antes de abrir, procure nas [issues existentes](https://github.com/gwen-org/gwen/issues). Se já existir, comente ou reaja na que está lá.
- Issues são públicas. **Não coloque** caminhos de pastas pessoais, nomes de clientes, e-mails ou prints com dados que você não queira expor.
- Sugestões entram no roadmap conforme a necessidade real de uso, sem prazo prometido.
- O código não aceita contribuição direta (pull requests). Enviar uma ideia ou um trecho em uma issue não dá direito sobre o código nem sobre o produto.

<br>

<h3> $ roadmap </h3>

<div align="center">

| **Versão** | **Foco** | **Situação** |
|:---:|:---:|:---:|
| V0.1 a V0.9.2 | launcher, sessões, pausa, saúde, dados locais, navegação em trilho, sessões em paralelo, tarefas, ambientes de uso | publicadas |
| V0.9.3 | botão "Nova coleção" visível e um nome só para coleção e categoria | próxima |
| V0.10 a V0.11 | clientes e pipeline, finanças e check-in de foco | planejadas, em beta fechado |
| V0.12 | pronta para o público: política de privacidade, planos, site e lançamento | planejada |
| V0.13 a V0.17 | calendário, sistemas, caderno, ideias e padrões de trabalho | planejadas |
| V1.0 | assistente local que conversa sobre os seus dados | planejada |

</div>

<br>

<h3> $ como trabalho </h3>

- Decisões de arquitetura registradas em **ADRs**, uma por arquivo, no repositório de desenvolvimento.
- Histórico de versões em `CHANGELOG.md`, e o README atualizado a cada versão.
- Releases assinadas, com atualização automática que preserva os dados.

<br>

<h3> $ stack </h3>

<div align="left">

![Tauri](https://img.shields.io/badge/Tauri%202-171717?style=flat-square&logo=tauri&logoColor=FFC131)
![React](https://img.shields.io/badge/React%2019-171717?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-171717?style=flat-square&logo=vite&logoColor=A78BFA)
![Tailwind](https://img.shields.io/badge/Tailwind%204-171717?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![SQLite](https://img.shields.io/badge/SQLite-171717?style=flat-square&logo=sqlite&logoColor=74C0FC)
![Rust](https://img.shields.io/badge/Rust-171717?style=flat-square&logo=rust&logoColor=E8E4DE)
![Supabase](https://img.shields.io/badge/Supabase-171717?style=flat-square&logo=supabase&logoColor=3ECF8E)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-171717?style=flat-square&logo=githubactions&logoColor=2088FF)

</div>

<br>

<h3> $ licença </h3>

A G.W.E.N. é **software proprietário**. Copyright (c) 2026 Samara Silvia Sabino. Todos os direitos reservados. Os termos estão em [`LICENSE`](LICENSE) e o resumo em [`NOTICE.md`](NOTICE.md).

- **Pode:** instalar o instalador oficial (Releases ou site), para uso pessoal, e abrir issues neste repositório.
- **Não pode sem autorização:** copiar, modificar, criar versões derivadas, redistribuir (inclusive o instalador), vender ou usar o nome, o logo e a identidade visual.

Qualquer outro uso precisa ser combinado antes com a autora.

> O Windows pode avisar que o app é de um "editor desconhecido", porque o instalador não tem assinatura digital. Clique em **Mais informações > Executar assim mesmo**.

<br>

<h3> $ contato </h3>

<div>
<a href="mailto:samarasilvia.dev@gmail.com">
  <img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=microsoft-outlook&logoColor=972FFF" />
</a>

<a href="https://www.linkedin.com/in/samara-silvia-9a2a26231" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=FF22D6" />
</a>

<a href="https://github.com/samarasilvia81" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=FF22D6" />
</a>
</div>

---

<div align="center">

<a href="https://git.io/typing-svg">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1800&color=E0E1E0&center=true&vCenter=true&width=600&lines=Uma+sess%C3%A3o+de+cada+vez.;Uma+pausa+de+cada+vez."
    alt="Typing SVG"
  />
</a>

</div>

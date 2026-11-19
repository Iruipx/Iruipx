# Direção de arte e manutenção

## Identidade

Preto `#09090B`, vermelho `#C1121F`, branco `#F5F5F5`, grafite `#27272A`. Tipografia larga e pesada, alinhamento editorial, numeração de seções, linhas finas, textura halftone e uma forma circular cortada por uma diagonal. A forma remete a uma lente e a um corte de lâmina de maneira abstrata, sem reproduzir o desenho de olhos ou símbolos de personagens.

O vermelho concentra a atenção no emblema. O branco carrega a tipografia. Texto informativo aparece em branco/cinza claro, evitando letras pequenas em vermelho sobre preto. Nada pisca ou depende de animação.

## Implementação

- Markdown nativo para o conteúdo e navegação.
- SVGs locais, com `viewBox`, sem scripts, `foreignObject`, imagens externas ou carregamento de fontes.
- `<picture>` escolhe uma composição vertical para telas menores.
- Texto principal permanece selecionável e legível sem as imagens.
- Ícones possuem texto alternativo e os nomes aparecem no texto.
- Separador estritamente decorativo usa `alt=""`.
- O estilo não exige CSS dentro do README; o GitHub sanitiza HTML e estilos.
- Sem serviços externos de estatísticas ou imagens dinâmicas.

## Curadoria do conteúdo

Inspeção dos repositórios públicos realizada em 19/11/2026: `Senkyn` contém apenas `README.md`, sem implementação. Foi listado com seu estado real e não foi tratado como projeto concluído. Não há linguagem usada em código público a destacar neste momento. Nenhum conteúdo privado foi consultado para redigir o perfil.

Atividade: manter o calendário de contribuições nativo do GitHub. Considerar gráficos de linguagens somente quando houver aplicações públicas representativas; volume de código não mede domínio de uma tecnologia. `github-readme-stats` foi avaliado, mas não incluído para evitar dependência e métricas pouco úteis nesta etapa.

Pins: neste momento não há aplicação pública pronta para recomendar como destaque. Assim que publicar uma, fixar o repositório com descrição clara, instalação reproduzível e exemplo de uso. Não preencher todos os espaços apenas por preencher.

## Bio sugerida

Desenvolvedor júnior em formação, com foco em backend. Estudando JavaScript, TypeScript e Node.js.

## Metadados sugeridos

| Repositório | Descrição | Tópicos |
| --- | --- | --- |
| Iruipx | Perfil de Bruno Martinelli · backend em formação · JavaScript, TypeScript e Node.js | profile-readme, github-profile, backend, javascript, typescript, nodejs |
| Senkyn | Repositório em preparação. Implementação ainda não publicada. | Não atribuir tecnologias sem código que as confirme. |

## Referências consultadas

| Referência | Aplicação |
| --- | --- |
| [GitHub: perfil e currículo](https://docs.github.com/en/account-and-profile/tutorials/using-your-github-profile-to-enhance-your-resume) | Apresentação curta, honestidade de habilidades, documentação e curadoria de projetos. |
| [GitHub: Profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme) | Repositório público com o mesmo nome do usuário e README na raiz. |
| [GitHub: escrita e imagens](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) | Imagens relativas, texto alternativo e suporte a picture. |
| [GitHub: quickstart de escrita](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) | Imagens responsivas e uso de Markdown nativo. |
| [GitHub Markup](https://github.com/github/markup) | Limitações de renderização e sanitização. |
| [Simon Willison](https://github.com/simonw/simonw) | Clareza ao apresentar trabalho real. |
| [innng](https://github.com/innng/innng) | Referência de perfil backend com identidade ligada a anime e apresentação concisa. |
| [HerXayah](https://github.com/HerXayah/HerXayah) | Exploração do limite entre identidade pessoal e excesso de ornamentos. |
| [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme) | Repertório comparativo de perfis minimalistas e temáticos. |
| [Laboratories](https://www.itsnicethat.com/articles/laboratories-graphic-design-310519) | Contraste, assimetria e tipografia japonesa como composição. |
| [PENETRATE / Hiroshi Imaeda](https://www.slanted.de/experimental-typography-by-hiroshi-imaeda-penetrate/) | Tipografia experimental e ritmo editorial. |
| [VIZ: direitos autorais](https://www.viz.com/copyrights-page) | Identificação dos titulares de Tokyo Ghoul e Bleach; nenhuma autorização ampla de republicação encontrada. |
| [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) | Avaliação de dependência e limites das métricas. |

## Manutenção

Atualizar esta apresentação conforme os estudos e os repositórios públicos evoluírem. Antes de incluir um projeto, verificar sua implementação e documentar uma forma reproduzível de executá-lo. Manter os recursos visuais no próprio repositório e preservar seus créditos.

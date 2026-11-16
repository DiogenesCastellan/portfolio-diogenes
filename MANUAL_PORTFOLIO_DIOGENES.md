# Manual do Portfólio — Diógenes Castellan

**Versão:** 0.2 — documentação em desenvolvimento  
**Estado:** checkpoint Neo Editorial implementado no HTML; validação visual e em dispositivos ainda pendente.  
**Base de código:** `index(1).html` enviado para revisão; versões de teste posteriores não são publicação definitiva.

## 1. Objetivo
Portfólio pessoal de posicionamento executivo para recrutadores, empresas e parceiros. Mostrar atuação em marketing, negócios, tecnologia, dados, IA e sistemas, com conteúdo factual e navegação clara.

## 2. Identidade visual
**Direção escolhida:** Neo Editorial — visual contemporâneo, sóbrio e com detalhes tecnológicos.

| Uso | Cor | HEX |
|---|---|---|
| Fundo principal | Azul quase preto | `#0B1220` |
| Texto principal em fundo escuro | Branco | `#FFFFFF` |
| Cor de destaque | Verde eucalipto | `#83B6A0` |
| Texto secundário | Cinza azulado claro | `#CBD5E1` |

**Regras:** destaque verde em botões principais, links ativos, marcadores e pequenas palavras; evitar excesso de cor. Manter contraste acessível, inclusive em botões e textos pequenos. Cores anteriores (dourado, vermelho, lima elétrico) foram testadas, mas não integram a direção atual.

## 3. Tipografia
- **Assinatura / nome:** Baskerville URW Medium, com capitalização `Diógenes Castellan`.
- **Títulos, menus e botões:** Acumin Pro Semibold.
- **Parágrafos e legendas:** Acumin Pro Regular.
- **Projeto Adobe Fonts:** `https://use.typekit.net/tuk3wob.css`.
- Confirmar no navegador se o kit publicado inclui todas as famílias e pesos; manter fontes substitutas seguras (`serif` / `sans-serif`) em caso de falha.
- Não embutir nem distribuir arquivos de fonte licenciados dentro do repositório.

## 4. Responsividade e navegação
- Desktop: menu horizontal, hierarquia tipográfica ampla, fotografia integrada ao hero.
- Celular: botão hambúrguer com `aria-expanded`, `aria-controls`, rótulo acessível, fechamento ao clicar em link, ao pressionar Escape e ao clicar fora.
- Evitar rolagem horizontal da página e links espremidos.
- Testar larguras de 320, 375, 390, 430, 768, 1024 e 1440 px; verificar também iPhone 15.
- Áreas clicáveis confortáveis (idealmente 44 × 44 px) e estados de foco visíveis.

## 5. Estrutura da página
1. Cabeçalho e navegação
2. Hero: proposta de valor, CTA, foto real e animação
3. Sobre
4. Projetos e casos práticos
5. Inteligência Artificial
6. Competências
7. Experiência profissional
8. Contato
9. Rodapé

## 6. Fotografia e movimento
- Utilizar exclusivamente a fotografia original fornecida pelo proprietário, sem recriar o rosto.
- Nome de arquivo esperado no HTML: `foto-diogenes.jpg`.
- Usar formato otimizado para web sem alterar enquadramento e identidade.
- Animações discretas; respeitar `prefers-reduced-motion`.

## 7. Conteúdo e credibilidade
- Diferenciar experiência prática, ferramentas exploradas e competências comprovadas.
- Não inventar resultados numéricos, certificações, cargos ou links sociais.
- Confirmar dados de contato antes da publicação.
- Apresentar projetos com contexto, contribuição pessoal, tecnologias e resultados apenas quando verificáveis.

## 8. Arquitetura técnica
- Site estático HTML/CSS/JavaScript, hospedagem prevista no GitHub Pages.
- Repositório: `DiogenesCastellan/portfolio-diogenes`.
- Página prevista: `https://diogenescastellan.github.io/portfolio-diogenes/`.
- Preferir HTML semântico, CSS organizado por tokens e componentes e JavaScript progressivo para navegação.
- Evitar dependências pesadas sem necessidade; carregar Adobe Fonts pelo CSS oficial.

## 9. Checklist antes de publicar
- [x] Paleta aplicada em todas as seções (revisão visual pendente)
- [ ] Adobe Fonts carregando corretamente
- [ ] Menu hambúrguer testado no celular
- [ ] Fotografia correta e otimizada
- [ ] Links e âncoras funcionando
- [ ] Textos revisados e aprovados
- [ ] Contraste, foco por teclado e movimento reduzido verificados
- [ ] Testes em desktop e celular
- [x] Arquivos de checkpoint exportados (aprovação final pendente)
- [ ] Publicação no GitHub Pages

## 10. Registro de decisões
- **Aprovado:** Baskerville URW Medium para nome; Acumin Pro para interface.
- **Aprovado:** navegação móvel por menu hambúrguer.
- **Direção atual:** Neo Editorial, azul quase preto `#0B1220`, branco e verde eucalipto `#83B6A0`.
- **Descartado para esta etapa:** substituição do dourado por vermelho; verde-lima elétrico muito intenso.
- **Pendente:** revisão visual do HTML com a nova paleta; refinamento da primeira tela; validação real em dispositivos.

---
*Documento vivo: atualizar a cada decisão aprovada e a cada entrega de versão.*

## 11. Encerramento da sessão — 13/11/2026
- Criado checkpoint do site com fundo azul quase preto, branco e verde eucalipto.
- Mantidos menu móvel, fotografia original e integração Adobe Fonts.
- Arquivos a publicar: `index.html`, `foto-diogenes.jpg`, `MANUAL_PORTFOLIO_DIOGENES.md`.
- Próxima sessão: validar visual, Adobe Fonts e menu no iPhone/desktop; continuar refinamento.
- A publicação no GitHub não deve ser considerada concluída até o commit aparecer no repositório.


## 12. Atualização tipográfica — versão 0.3 (14/11/2026)
- Referência de legibilidade: página TOTVS RH Atração de Talentos. A TOTVS utiliza tipografia institucional própria; não copiamos nem distribuímos essa fonte.
- Assinatura: Baskerville URW Medium (500), com capitalização natural.
- Interface: Acumin Pro, pelo projeto Adobe Fonts `tuk3wob.css`; fallback Segoe UI / Arial.
- Título principal: Light (300); destaque Regular (400).
- Títulos de seção: Regular (400); cartões e subtítulos Medium (500).
- Corpo: Regular (400), 16px base, entrelinha 1.72–1.8.
- Botões e menu: Medium (500); etiquetas Medium (500).
- Preservados: paleta Neo Editorial #0B1220, #FFFFFF, #83B6A0; menu hambúrguer; retrato original e animação; conteúdo e contatos.
- Conferir na Adobe Fonts: Web Project deve incluir Baskerville URW Medium e Acumin Pro Light, Regular e Medium.
- Testes pendentes: legibilidade em desktop e iPhone, menu, links, foto, fontes e movimento reduzido.
- GitHub Pages: enviar `index.html`, `foto-diogenes.jpg` e `MANUAL_PORTFOLIO_DIOGENES.md` na raiz da branch `main`.


## 13. Redes sociais — versão 0.4
- Instagram: https://www.instagram.com/di_castellan/
- Facebook: https://www.facebook.com/di.da.praia?locale=pt_BR
- Discord: https://discord.com/users/720865491266043966
- Três botões adicionados à seção Contato; links abrem em nova aba, com rel seguro.
- Mantidos os demais contatos e toda a identidade visual da versão 0.3.


## 14. Hero cinematográfico 3D — versão 0.5 (15/11/2026)
- Retrato original entra da esquerda para a direita com perspectiva 3D, rotação Y, profundidade, escala e blur transitório; duração ~1,45s.
- Assinatura Diógenes Castellan em Baskerville URW entra da esquerda, seguida de subtítulo, texto e botões com animação escalonada.
- Layout desktop: retrato à esquerda, texto à direita; mobile: texto antes do retrato, sem rolagem horizontal.
- Animação apenas CSS, sem bibliotecas externas, com `prefers-reduced-motion` para acessibilidade.
- Sem som automático: não incomodar recrutadores nem depender de desbloqueio de áudio pelo navegador.
- Paleta Neo Editorial, tipografia leve, contatos e menu responsivo preservados.
- Testar no GitHub Pages e em dispositivo real antes de declarar versão definitiva.


## 14. Versão 0.6 — reorganização editorial (15/11/2026)
- Seção Sobre simplificada, sem cartões redundantes.
- Projetos reduzidos de seis para quatro casos práticos: ERP, CRM, analytics e audiovisual.
- Inteligência Artificial incorporada à seção Competências e tecnologias (três áreas).
- Experiência profissional mais concisa; datas e empresas preservadas.
- Menu atualizado com cinco âncoras; preservados contatos, retrato e animações da home.
- Manter validação visual em dispositivos reais antes de considerar finalizado.

## Versão 0.7 — Cases e personagens virtuais (15/11/2026)
Inclusões e alterações:
1. Quatro estudos de caso com contexto, atuação e entrega: performance/GA4/GTM; CRM Flux; ERP GestãoClick; produção audiovisual e IA.
2. Cards visuais feitos com CSS, sem imagens externas, métricas inventadas ou resultados não comprovados.
3. Seção nova "Personagens e modelos virtuais com IA", com frentes masculina e feminina.
4. Aviso explícito de que as letras M e F são placeholders gráficos, não fotos dos modelos já produzidos.
5. Menu inclui "Personagens IA"; preservados demais links e animação de entrada.
6. Layout responsivo de cards em duas colunas no desktop e uma no celular.
Pendências editoriais: selecionar imagens reais dos personagens, confirmar direitos de publicação e identificar projetos, ferramentas e objetivos de cada personagem. Validar métricas antes de publicar resultados quantificados.

## Versão 0.8 — Galeria de personagens e vídeo (15/11/2026)
- Substituídos os cartões ilustrativos M/F por imagens reais fornecidas nesta conversa.
- Galeria masculina: 4 imagens (executivo, retratos e academia).
- Galeria feminina: 5 imagens (retratos, perfis, corpo inteiro frente e costas).
- Arquivos de imagem convertidos para WebP, com carregamento lazy.
- Vídeo de 29 segundos adicionado como experimento audiovisual com controles manuais (sem autoplay).
- Layout responsivo com duas colunas no celular e quatro no desktop.
- As imagens ampliam em nova aba ao clicar.
- Não atribuídos nomes de ferramentas nem resultados não confirmados a cada imagem.
- Para publicar, subir todos os arquivos da pasta, incluindo os 9 WebP e MP4.

## v0.9 — Curadoria editorial (15/11/2026)
- Galeria de personagens reduzida de 9 para 4 imagens: masculino 01 e 04, feminino 03 e 04.
- Excluídos retratos masculinos 02/03 e femininos 01/02/05, por repetição de ângulo ou menor diversidade.
- Projeto Marine Itajuba: 1 mockup selecionado (terceira arte enviada), duas artes excluídas; adicionado vídeo imobiliário de 39 segundos.
- Projeto VitalVille: vídeo de produto de 29 segundos, separado do conteúdo de modelos virtuais.
- Todas as mídias mantidas sem reprodução automática.
- Importante: outdoor é tratado como mockup conceitual; confirmar autoria e etapas executadas antes de acrescentar créditos específicos.
- Arquivos retirados da seleção não foram incluídos no ZIP; preservar os originais em backup pessoal.

## Versão 1.0 — Autoria e produção audiovisual integral (15/11/2026)
- Confirmada pelo autor a responsabilidade integral pelos projetos exibidos.
- Vídeo Marine Itajuba: IA como apoio; concepção, direção de arte, montagem, edição, locução e finalização no Adobe Premiere Pro. Mockup identificado como conceitual.
- Vídeo VitalVille: IA como apoio; concepção, direção criativa, montagem, edição, locução e finalização no Adobe Premiere Pro.
- Personagens virtuais: autoria e criação integral confirmadas.
- Descrições atualizadas sem afirmar que a locução foi gravada pessoalmente nem especificar plataforma de IA para cada peça.

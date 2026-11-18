# PatoLab 0.8 — Apostilas + Simulador de Declaração de Óbito

Plataforma estática para GitHub Pages (organização patolabmed, repositório patolabmed.github.io). Abra `index.html` em um servidor local ou publique os arquivos na raiz do repositório.

## Mudanças
- 13 aulas com estrutura de apostila e 39 seções autorais de mecanismos e revisão, em modo de leitura escuro inspirado no FisioLab.
- Diagramas de mecanismos integrados ao texto, tabelas e caixas de conceito-chave e pegadinhas.
- Seis recortes de lâminas e imunohistoquímica da aula prática, integrados nos módulos de Burkitt, linfoma folicular e morfologia; os demais módulos usam esquemas autorais, não imagens histológicas inventadas.
- Acervo original de 193 slides preservado em seção recolhida.
- 10 casos interativos de Declaração de Óbito (arquivo declaracao-obito.html) com correção aproximada.
- Flashcards ampliados: 119 anteriores + 39 novos, separados por módulo.

## Transparência e limitações
Os textos foram elaborados com apoio nos slides da disciplina e em conceitos gerais de patologia; não foi fornecido exemplar do Robbins & Cotran para cotejo literal. Portanto não alegamos verificação página a página no livro. A apostila é material didático complementar, não reprodução do Robbins. Algumas figuras de aula contêm imagens de terceiros e precisam de autorização antes de publicação pública. A correção de DO é baseada em termos e não substitui avaliação docente. Revise as informações com a professora e as fontes oficiais antes de uso profissional.

## Publicação
Copie todos os arquivos e pastas deste pacote para a pasta clonada do repositório, substituindo os arquivos homônimos. Faça commit e push no GitHub Desktop. Não apague `.git`. GitHub Pages: branch `main`, pasta `/ (root)`, domínio personalizado vazio.


## Atualização 0.9 — identidade e identificação do estudante
- Paleta roxo profundo / amarelo-ouro aplicada ao painel, apostilas, flashcards e simulador de DO.
- Tela de boas-vindas solicita nome no primeiro acesso. O nome é guardado somente em `localStorage`, sem login, banco de dados ou sincronização entre dispositivos.
- Botão “Alterar nome” no menu lateral. O progresso anterior no mesmo navegador permanece.

## Auditoria visual das imagens e esquemas
- Confirmada a existência e leitura das seis imagens recortadas em `assets/atlas/` e das 193 páginas WebP do acervo.
- Os recortes do linfoma folicular (H&E e IHQ), Burkitt (H&E, céu estrelado, detalhe) e linfoma agressivo foram inspecionados visualmente.
- Atenção: `dlbcl-he.png` contém título de slide genérico “LINFOMA AGR...” e não comprova isoladamente o subtipo DLBCL; a legenda foi tornada cautelosa.
- Os esquemas moleculares são fluxogramas didáticos resumidos, não diagramas bioquímicos exaustivos.
- A auditoria de precisão científica de cada um dos 193 slides e a correspondência de cada imagem com cada parágrafo continuam pendentes; não interpretar esta versão como validação histopatológica completa.
- Referência conceitual: Robbins & Cotran, *Patologia: Bases Patológicas das Doenças*; o livro não foi diretamente cotejado nesta revisão.


## Atualização v1.0 — Atlas curado
- Retirada a galeria automática de páginas de slides ao fim das aulas.
- Atlas restrito a seis recortes morfológicos selecionados com legendas e perguntas interpretativas.
- Quatro esquemas de mecanismos moleculares (RAS, BCR::ABL1, MMR e BCL2).
- Slides originais mantidos nos arquivos do pacote para rastreabilidade, mas não são apresentados no Atlas.
- A identificação diagnóstica das imagens é orientativa e não substitui confirmação por patologista.

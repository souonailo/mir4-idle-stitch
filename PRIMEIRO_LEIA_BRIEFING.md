# MIR4 Idle — briefing para redesign visual no Google Stitch

## Objetivo
Criar uma nova linguagem visual para TODAS as interfaces do jogo web MIR4 Idle, para desktop 1920×1080 e mobile 390×844. O resultado deve ser claramente diferente das capturas atuais em composição, hierarquia, materiais, tipografia, controles e apresentação das informações. Não basta recolorir componentes antigos, inserir bordas douradas, adicionar um fundo e colar a logo.

O jogo combina fantasia oriental inspirada em MIR4, logo caligráfica vermelha e preta e personagens/cenários em pixel art. A interface precisa ligar esses elementos de forma coesa, imersiva e funcional. Use as capturas para entender dados e controles existentes, não como um layout a ser preservado. Crie telas implementáveis, com texto real em português, informações legíveis e estados claros.

## Restrições obrigatórias
- Preserve a arte principal, composição, regiões, cores, marcadores e funcionamento dos mapas do continente e regionais. Redesenhe somente moldura, cabeçalho, navegação e painéis ao redor deles. As imagens 10 e 11 são referência visual protegida.
- Não inclua Pokémon, Pokédex, Poké Balls, treinadores ou marcas de outros jogos em navegação, imagens ou textos. As capturas antigas contêm elementos legados: eles não são direção artística.
- Preserve funções e dados existentes; não invente preços, atributos, probabilidades, recompensas ou botões que indiquem recursos inexistentes. Demonstrações de valores devem ser tratadas como exemplos.
- Preserve o personagem chibi/pixel art real. Não use retratos realistas falsos para representá-lo. Mantenha quatro slots de personagem e o fluxo classe → aparência → nome.
- Em masmorras, diferencie arte conceitual de chefes comprovadamente identificados. O material em 03-assets/masmorras-conceitos é gerado, não prova a identidade canônica. Não retrate como oficial sem validação.
- Telas administrativas estão fora do escopo. Inclua conta e segurança acessíveis ao jogador.

## Referências incluídas
- 01-telas-atuais/: capturas nomeadas de login, personagem, HUD e todos os grupos de painéis. São inventário de funções e conteúdo, não aprovação do visual. Algumas mostram carregamento ou estados vazios; não interprete isso como ausência definitiva de conteúdo.
- 02-logo/: PNG original transparente, PNG de exibição, SVG e ICO existentes. Letras pretas exigem uma superfície com contraste; a logo não deve ficar minúscula ou invisível em fundo escuro.
- 03-assets/personagem-e-icones/: sprites e artes existentes para escala e linguagem. São referências; spritesheets não são retratos prontos.
- 03-assets/masmorras-conceitos/: fundos e chefes gerados anteriormente. São opções de conceito, NÃO são artes oficiais nem comprovam a identidade dos chefes. A imagem mir4-boss-uma-extracted é uma referência extraída, mas sua associação à masmorra não está comprovada.
- 04-tentativa-rejeitada/: três referências propostas anteriormente. Mostram o que não foi aceito: mesmo formulário com fundo novo, HUD quase inalterado e janela genérica com imagem e cartões. Mobile apresenta sobreposição e conteúdo cortado.

## Direção de arte
Fantasia oriental de MIR4 com personalidade própria: pedra escura, metal envelhecido, materiais de arquitetura oriental e detalhes em tinta vermelha da logo. Dourado envelhecido para detalhes e hierarquia, não como contorno em tudo. Manter cores funcionais para vida, recursos, raridade e avisos. Títulos expressivos e corpo de texto muito legível. Evitar interface corporativa, grades genéricas, aparência de site de cassino e ornamentos que prejudiquem dados.

As telas de acesso e apresentação podem ser cinematográficas. HUD, inventário, menus e comércio são usados frequentemente e devem ser rápidos, claros e organizados. A arte gerada deve combinar com a pixel art sem fingir que o personagem do jogo é realista.

## Entregáveis solicitados ao Stitch
1. Uma direção visual coesa com exemplos de cores, tipografia, molduras, botões, ícones, estados e seletores.
2. Mockups desktop e mobile para todas as telas listadas abaixo, inclusive estados selecionado, vazio, erro, carregamento e indisponível quando relevantes.
3. Exemplos de motion como descrições de interação: abertura de painéis, seleção, transição de masmorra, forja e feedback. Preferir movimento breve e funcional, com alternativa para movimento reduzido.
4. Apresentar três telas prioritárias — login, HUD e masmorras — como sistema visual completo antes de expandir para as demais.

## Telas a recriar

### Acesso e personagem
01 Login: fundo ilustrado oriental, logo legível, formulário bem composto, sem duplicar ação de cadastro; campos, recuperação e provedores claros.
02 Cadastro: formulário organizado, validação, termos e estados de envio.
03 Recuperação: entrada de e-mail, retorno e estados de envio/erro.
04 Seleção de personagem: palco em escala com sprites reais, quatro slots claros, detalhes do personagem e ação entrar.
05 Classe: seletor ilustrado com nome, arma e estado real; impedir que classes indisponíveis pareçam jogáveis; palco com modelo real.
06 Aparência: prévias reais de cabelo, seleção de cabelo, olhos e pele e comparação visual clara.
07 Nome: campo, validação, resumo de classe/aparência e ação de criação.

### Mundo e HUD
08 HUD: retrato, nome, vida, mana, experiência, moedas, navegação, chat e habilidades sem sobreposições. Mobile deve reservar espaço ao cenário, com menus recolhíveis e áreas de toque acessíveis.
09 Analisador de caça: métricas legíveis, filtros/ações claras, sem esconder o cenário.
10 Mapa continente: manter integralmente a imagem e marcadores; redesenhar apenas interface ao redor.
11 Atlas Bicheon: preservar imagem e marcadores; redesenhar lista de regiões, filtros, detalhes e molduras externas.
12 Masmorras: catálogo com seleção ilustrada, área de destaque com ambiente e chefe em camadas, categoria, requisitos, tempo, recompensas e ações reais. Prever quatro entradas: Santuário Oculto de Bicheon / Senhor da Guerra do Santuário; Labirinto Demoníaco / Rei Minotauro Demoníaco; Expedição Asura / Asura Primordial; Expedição Abismo / Guardião do Abismo. Mostrar arte pendente caso não haja identificação confiável. Incluir salas, criação, convites, lobby de prontidão e HUD/resultado de masmorra.
13 Descanso: estado atual, duração, benefícios e ação, com atmosfera tranquila.

### Personagem e progressão
14 Inventário/equipamentos: personagem real com slots, mochila, categorias, pesquisa, detalhes e comparação de item. Mobile alterna seções sem perder seleção.
15 Forja: catálogo com imagens e nomes, seleção, materiais, custos, chances, estado e palco de resultado. Não usar uma grade de espaços vazios como solução.
16 Encantamento: item selecionado, nível atual, materiais, custo, probabilidade e confirmação.
17 Atributos: personagem, poder, grupos de atributos, valores e explicações legíveis.
18 Habilidades: ícones, seleção, nível, requisitos, detalhes e rotação/atalhos.
19 Títulos: lista, disponibilidade, título ativo, detalhes e bônus.
20 Maestria: caminhos de progressão, nível, próximo efeito, custo e requisitos.
21 Espíritos e montarias: coleções separadas com artes reais, slots, detalhes, raridade e ação equipar.

### Comércio e comunidade
22 Passe de batalha: trilha de progressão clara, gratuita e premium, imagem de temporada e estados de recompensa.
23 Loja/suprimentos: produtos com imagem, nome, quantidade, preço e moeda; filtros e confirmação.
24 Mercado global: busca, filtros, ofertas, preço, quantidade, detalhes e criação de anúncio.
25 Compra de ouro/aço: opções, moeda, estado e indicação de ambiente de teste quando existir.
26 Guilda: brasão, resumo, membros, solicitações, permissões, brasão e diplomacia. Mostrar exemplo preenchido, não só carregamento.
27 Amigos: lista, presença, pesquisa e pedidos enviados/recebidos.
28 Correio: lista e detalhe, não lidas, anexos e ações.
29 Rankings: categorias, posições, nomes e pontuação com tabela adaptável.
30 Configurações: gráficos, HUD, conta e sessão, valores claros e controles acessíveis.
31 Sistemas auxiliares: redesenhar ajuda, calculadora e analisador; excluir Pokédex e qualquer conteúdo Pokémon. Não substituir a Pokédex por bestiário falso; um bestiário MIR4 só com dados reais.

## Padrões transversais
- Criar melhores seletores, abas e filtros: destaque por forma e texto além de cor; seleção evidente e consistente.
- Usar estados normais, foco, selecionado, desabilitado, erro e carregamento; sem sobreposição ou truncamento de controles no mobile.
- Preservar rolagem, fechamento, retorno, conteúdo essencial e informações importantes acima de imagens decorativas.
- Garantir contraste e área de toque; prever navegação por teclado e movimento reduzido.
- Criar mockups com dados de exemplo explicitamente identificados, sem vender dados ou artes conceituais como reais.

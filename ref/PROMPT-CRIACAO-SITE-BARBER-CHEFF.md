# Prompt de criação — Site Barber Cheff

Copie o conteúdo abaixo para a IA geradora e disponibilize o design system e a pasta `fotos/pesquisa-barber-cheff`. Elaborado em 07/10/2026, com pesquisa coletada em 06/10/2026.

---

Atue como um designer de produto digital, diretor de arte e desenvolvedor front-end experiente. Crie e implemente um site institucional completo, responsivo e visualmente marcante para a **Barber Cheff**, uma barbearia de Jardim Primavera, Duque de Caxias/RJ.

O site deve transformar a identidade real da empresa em uma experiência clara, envolvente e orientada a agendamentos. Entregue a página funcionando, com conteúdo real, imagens do acervo, navegação e interações completas. Não se limite a um wireframe ou descrição de proposta.

## 1. Primeiro, compreenda o projeto

**Já existe um design system. Ele é a autoridade visual da implementação.** Localize e leia seus arquivos antes de criar componentes. Reutilize tipografia, tokens, espaçamento, grid, botões, bordas, raios, ícones, estados e padrões de movimento. Use a stack e as convenções existentes no projeto.

Não substitua o design system por um tema novo nem instale outra biblioteca visual sem necessidade. As sugestões tipográficas da pesquisa são alternativas anteriores, não uma ordem para trocar as fontes do sistema existente. Se o design system não estiver disponível, solicite somente seu arquivo ou referência; não afirme que seguiu algo que não conseguiu consultar.

Leia a pasta `fotos/pesquisa-barber-cheff`, especialmente:

- `README.md` e os cinco documentos de `relatorios/`;
- `dados/cadastro.json`, `servicos.json`, `assinaturas.json`, `horarios.json` e `inventario-imagens.json`;
- as pastas `logos/`, `fachada/` e `campanhas/`;
- `identidade/paleta.json` e `dados/publicacoes.json`.

Use os dados estruturados como referência factual e os relatórios como contexto editorial. O arquivo `PAINEL.html` é um painel de pesquisa, não o layout que deve ser copiado para o site.

Se não tiver acesso à pasta, informe isso e solicite os materiais necessários. O resumo abaixo permite planejar a página, mas não autoriza inventar imagens, regras ou informações ausentes.

## 2. Conceito e personalidade

Conceito editorial: **“Seu corte em dia. Seu estilo na régua.”**

A marca tem presença local, linguagem próxima, humor nos bastidores e foco em manter o visual com praticidade. O clube de assinatura é sua principal chamada comercial. Crie uma experiência com personalidade, acabamento cuidadoso e fotos reais, mantendo a sensação de uma barbearia acessível e presente na rotina dos clientes.

O amarelo da fachada e das campanhas, o preto, o branco e os pequenos detalhes vermelhos do logo são referências observadas. Mapeie essas referências para os tokens semânticos do design system. O amarelo aproximado da campanha é `#FFC603`; esse código não é um padrão oficial que deva sobrepor o sistema existente. Use o vermelho com discrição, principalmente no próprio logo.

Busque variedade na composição: uma abertura expressiva, uma seção de assinatura com hierarquia comercial forte, uma lista de serviços fácil de ler, fotografias editoriais e um encerramento local e acolhedor. Evite uma sequência monótona de cartões iguais em todas as seções.

Escreva em português brasileiro, com frases diretas e naturais. Preserve a proximidade da marca, sem exagerar nas gírias. Não invente tempo de mercado, número de clientes, premiações ou alegações como “a melhor da cidade”.

## 3. Informações que devem orientar o conteúdo

**Marca:** Barber Cheff. Sempre com dois “f” no nome de apresentação.

**Endereço:** Avenida Visconde de Itaúna, 508 — Jardim Primavera, Duque de Caxias/RJ — CEP 25214-415.

**Telefone e WhatsApp:** (21) 97698-5317.

**Equipe cadastrada:** Daniel, Gabriel, Luiz e Thiago. Não atribua cargos, biografias, experiência ou fotografias a nomes sem correspondência comprovada.

**Serviços avulsos com preço divulgado:**

- Corte: R$ 40,00.
- Corte + barba: R$ 70,00.
- Corte na tesoura: R$ 50,00.
- Raspagem da cabeça inteira com máquina ou navalha: R$ 30,00.

**Serviços com preço sob consulta:** barba, cera no nariz, cera na orelha, Nevou, pé do cabelo, reflexo, sobrancelha, tintura de barba e tintura de cabelo. Preserve os nomes técnicos quando não houver descrição confirmada.

**Clubes:**

- Clube Barba Ilimitada: R$ 59,90/mês.
- Clube Corte Ilimitado: R$ 75,90/mês.
- Clube Corte + Barba Ilimitado: R$ 129,90/mês.

Os detalhes públicos informam uso ilimitado do item coberto nos dias de funcionamento. Isso não inclui automaticamente serviços extras. Os valores foram consultados em 06/10/2026; centralize-os em uma fonte de dados fácil de atualizar.

**Comodidades declaradas:** Wi-Fi, estacionamento, acessibilidade e atendimento a crianças. Não amplie essas declarações para estacionamento gratuito, estrutura específica ou serviços infantis especializados.

**Pagamentos informados:** dinheiro, cartão de crédito, cartão de débito e PIX.

**Links funcionais:**

- Agendamento: `https://sites.appbarber.com.br/barbercheff-jmf9`
- WhatsApp: `https://wa.me/5521976985317`
- Instagram: `https://www.instagram.com/barberchef01/`
- Google: `https://share.google/n92P3dzJ9hc59dIuB`
- Rota: `https://www.google.com/maps/search/?api=1&query=-22.68759727%2C-43.2604332`

O identificador do Instagram é `barberchef01`, com um “f”. Preserve a URL exatamente.

## 4. Jornada e dobras

Trate “dobras” como momentos da narrativa, com altura determinada pelo conteúdo. Não force todas as seções a ocupar uma tela inteira.

### Cabeçalho — A próxima ação sempre clara

Logo original, navegação por âncoras e botão **Agendar horário**. Sugestão de navegação: Clube, Serviços, Espaço e Localização. No celular, use cabeçalho compacto e menu acessível. Se houver cabeçalho fixo, compense sua altura ao navegar entre seções.

### Dobra 1 — Reconhecimento e vontade de entrar

Crie uma abertura de impacto com composição assimétrica no desktop: mensagem forte de um lado e uma fotografia real relevante do outro. A imagem deve transmitir a experiência da Barber Cheff, sem parecer banco de imagens.

Texto de apoio: **Barbearia em Jardim Primavera • Duque de Caxias**.

Título: **Seu corte em dia. Seu estilo na régua.**

Descrição: **Cortes clássicos e modernos, barba e cuidado com o seu visual. Escolha seu horário na Barber Cheff.**

CTA principal: **Agendar horário**. CTA secundário: **Conhecer o clube**, levando à seção de planos.

Inclua uma indicação discreta do clube de cabelo: **Corte ilimitado por R$ 75,90/mês**. Evite vários selos e informações concorrentes. Use a identidade gráfica da fachada como inspiração para divisórias ou detalhes, sempre dentro do design system.

No celular, apresente localização, título e CTA rapidamente, com imagem abaixo ou ao lado somente se houver espaço real. Não imponha uma imagem de tela inteira antes da ação principal.

### Dobra 2 — O clube como hábito

Título: **Seu visual não precisa esperar o próximo mês.**

Introduza a assinatura com uma explicação curta: o cliente escolhe o plano e agenda o serviço coberto nos dias de funcionamento.

Apresente os três planos lado a lado no desktop e empilhados no celular. Destaque visualmente o **Clube Corte Ilimitado**, por ser a oferta mais presente na comunicação, sem rotulá-lo como “mais vendido” ou “mais escolhido”.

Cada plano deve ter nome, benefício objetivo, mensalidade e botão **Ver plano no AppBarber**. Na ausência de URLs específicas verificadas, use a página oficial de agendamento e deixe claro o destino externo. Não simule contratação dentro do site.

Use uma sequência simples de três passos: **Escolha seu plano → Confira as condições → Agende seu horário**. Inclua a orientação **Consulte as condições de uso e contratação no AppBarber**.

### Dobra 3 — Escolha o cuidado de hoje

Título: **Do corte ao acabamento.**

Crie um menu editorial de serviços, com nomes alinhados e preços fáceis de comparar. Use quatro linhas ou blocos principais para os serviços com preço divulgado, evitando uma grade excessiva de cartões.

Agrupe os demais em **Outros cuidados**, com expansão acessível ou lista compacta e indicação **Valor sob consulta**. Não use preço zero ou calcule valores ausentes. CTA de dúvidas: **Consultar pelo WhatsApp**.

O site deve atender tanto quem deseja uma visita avulsa quanto quem considera assinar o clube.

### Dobra 4 — A identidade ganha espaço

Título: **Reconheça a fachada. Conheça a Barber Cheff.**

Use a fachada amarela como âncora de reconhecimento local e uma imagem real do interior, se houver material adequado. No desktop, explore duas imagens de proporções diferentes com texto curto ao lado. No celular, transforme a composição em uma sequência simples, sem recortes que escondam o logo ou o acesso.

Mostre as comodidades declaradas em uma faixa discreta. Integre um bloco de equipe com os quatro nomes. Se não houver retratos identificados, use uma apresentação tipográfica limpa; não gere rostos ou associe pessoas dos reels a nomes por suposição.

### Dobra 5 — O trabalho acontecendo

Título: **A rotina da casa, de perto.**

Monte uma seleção curta de três a seis imagens úteis do atendimento ou de resultados, somente quando a qualidade e o conteúdo permitirem. Prefira uma imagem principal e imagens complementares a um carrossel automático.

As capas de reels são referências, não fotos profissionais em alta resolução. Se o acervo não sustentar uma boa galeria, reduza esta seção para uma composição com material válido e CTA **Acompanhar no Instagram**. Não invente antes e depois, clientes, cortes ou resultados.

Não carregue um feed pesado do Instagram como dependência para exibir a página. Não use vídeo com áudio automático.

### Dobra 6 — Dúvidas antes de sentar na cadeira

Crie um FAQ curto, com quatro a cinco questões realmente úteis:

- Como agendar? Pelo link oficial do AppBarber; WhatsApp para dúvidas.
- Posso fazer um serviço avulso? Sim, há serviços avulsos no catálogo.
- O que o clube inclui? O item correspondente ao plano; condições no AppBarber.
- A barbearia atende crianças? Sim, conforme informado pela empresa.
- Quais pagamentos são aceitos? Dinheiro, crédito, débito e PIX.

Use acordeão do design system com operação por teclado e estado expandido identificável. Não inclua respostas sobre cancelamento, fidelidade contratual ou corte na tesoura dentro do clube sem confirmação.

### Dobra 7 — Uma visita começa com um caminho fácil

Título: **A próxima parada é na Barber Cheff.**

Combine foto da fachada, endereço completo, telefone e botões **Como chegar** e **Agendar horário**. Deixe o endereço em texto selecionável. Um mapa é opcional; carregue-o sob demanda ou use o link de rota. Não gere imagem fictícia de mapa.

Como os horários divergem entre as fontes, use **Consulte os horários disponíveis no agendamento**. Não exiba “aberto agora” nem escolha silenciosamente uma das grades.

### Encerramento e rodapé

Finalize com uma chamada curta: **Seu próximo corte começa aqui.** e o botão **Agendar horário**. O rodapé deve ter logo, nome, endereço, contato e Instagram. Não repita toda a página.

Não adicione redes sociais do AppBarber como se fossem da barbearia. Não invente e-mail, CNPJ, política de privacidade, páginas legais ou links sem destino. Caso a implementação passe a coletar dados, registre a necessidade de conteúdo de privacidade real na entrega técnica.

## 5. Responsividade como parte do projeto

Projete primeiro para telas pequenas e amplie a composição com intenção. Use os breakpoints do design system; valide a experiência em 360, 390, 768, 1024 e 1440 px, além de verificar ausência de overflow a partir de 320 px.

- Use larguras fluidas, contêiner máximo e espaçamentos consistentes.
- Ajuste a escala dos títulos sem cortar palavras ou impor quebras ruins.
- Transforme colunas em uma sequência lógica; preserve a ordem de leitura no HTML.
- Preços e “/mês” devem continuar legíveis juntos.
- Botões e áreas de toque devem ter pelo menos 44 × 44 px.
- Não dependa de hover para revelar conteúdo ou ações.
- Não esconda condições importantes apenas para encurtar a tela.
- Trate recortes de imagens por contexto; use `object-fit: contain` no logo e `object-position` apropriado nas fotos.
- Uma barra inferior de agendamento no celular pode aparecer após a abertura. Reserve espaço para ela, respeite a safe area e não cubra conteúdo, teclado, FAQ ou rodapé. Evite sobrepor um segundo botão flutuante de WhatsApp.

## 6. Qualidade visual, acessibilidade e desempenho

Use HTML semântico, um único H1, hierarquia de títulos, foco visível, links descritivos e contraste adequado. O menu móvel deve controlar foco, fechar com Escape e devolver o foco ao acionador. Não comunique estados somente por cor. Preserve usabilidade com zoom de 200% e conteúdo legível sem JavaScript quando possível.

Use transições discretas do design system e respeite `prefers-reduced-motion`. Evite parallax intenso, cursores personalizados, rolagem forçada e conteúdo inicialmente invisível que dependa de animação para aparecer.

Otimize fotos sem degradar logo e textos, mantenha dimensões explícitas e formatos responsivos. Priorize a imagem principal e carregue imagens posteriores sob demanda. Não use URLs temporárias do Instagram: use os arquivos locais do inventário. Não amplie miniaturas pequenas para fundos gigantes. Preserve os originais e crie derivados separados quando necessário.

Defina título e descrição para busca local:

**Título:** Barber Cheff | Barbearia em Jardim Primavera, Duque de Caxias

**Descrição:** Conheça a Barber Cheff em Jardim Primavera, Duque de Caxias. Veja cortes, barba e clubes de assinatura e agende seu horário pelo AppBarber.

Se implementar dados estruturados, use somente informações confirmadas. Não invente domínio, URL canônica, horários ou avaliação agregada. Não transforme a nota 5,0 do AppBarber em avaliação do Google. Para esta primeira versão, depoimentos são opcionais e devem ser omitidos se não houver atribuição e conteúdo adequados.

## 7. Entrega e revisão

Implemente o site no projeto, mantendo componentes organizados e conteúdo fácil de atualizar. O escopo inicial não inclui loja virtual, pagamentos próprios, cadastro de clientes ou reconstrução do sistema de agendamento.

Confira todas as âncoras, links de contato, menu móvel, FAQ e estados interativos. Revise a página nos tamanhos indicados, confirme que imagens carregam, preços estão corretos e nenhum elemento se sobrepõe. Não declare verificações que não conseguiu executar.

Entregue uma prévia funcional para revisão, sem publicar automaticamente. Ao concluir, informe de forma breve os componentes do design system reutilizados, as verificações realizadas e as pendências concretas, especialmente horários, condições dos planos e seleção das imagens. Essas observações pertencem à entrega do projeto, não a avisos técnicos espalhados na interface do cliente.

**Critério de sucesso:** o visitante deve reconhecer a Barber Cheff, entender os serviços e o clube, localizar a loja e conseguir agendar com facilidade tanto no celular quanto no computador. A criatividade deve aparecer na composição e na narrativa, sustentada pela identidade real e pelo design system fornecido.

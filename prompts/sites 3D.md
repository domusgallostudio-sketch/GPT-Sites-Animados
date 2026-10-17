# sites 3D

Transcrição do prompt visível no vídeo enviado em 17/10/2026. O início e a última frase ficaram cortados; esses pontos estão indicados abaixo.

[Início cortado no vídeo: “…visuais e entrega navegável.”]

## EXPERIÊNCIA CENTRAL

O site começa com uma hero de tela inteira mostrando a fachada da casa em 3D, em um enquadramento levemente oblíquo, com paisagismo, profundidade e iluminação cinematográfica de fim de tarde.

Conforme o visitante desce a página, a câmera se aproxima da entrada, entra na casa e percorre os ambientes. Cada ambiente apresentado recebe uma frase curta e marcante que ajuda o interessado a imaginar sua vida naquele espaço.

A casa inteira deve existir como uma única cena tridimensional coerente, renderizada em tempo real no navegador. Fachada e interiores pertencem à mesma construção.

Não substitua essa experiência por vídeo, sequência de imagens, panoramas 360°, imagens com parallax ou cômodos desconectados. Imagens podem servir como texturas ou como alternativa de compatibilidade, mas a experiência principal deve usar geometria 3D real.

## ARQUITETURA E REFERÊNCIA

Analise a planta anexada antes de modelar. Preserve seu programa e sua organização geral:

- Casa térrea.
- 3 quartos, sendo 1 suíte.
- Exatamente 2 banheiros completos: suíte e social.
- Sala de estar e sala de jantar.
- Cozinha com ilha.
- Lavanderia.
- Área gourmet com churrasqueira, bancada, mesa e estar externo.
- Jardim integrado à área de lazer.

A entrada principal está na parte inferior da imagem, a área gourmet nos fundos, os quartos à esquerda e a área social à direita.

A imagem é um estudo conceitual sem medidas. Defina dimensões plausíveis para a visualização e registre as medidas assumidas, sem apresentá-las como informações verificadas.

Corrija ambiguidades antes de construir o modelo, especialmente o fechamento do vestíbulo da suíte voltado ao jantar. Garanta privacidade, acesso independente aos quartos, portas utilizáveis e circulação contínua.

Crie fachada, cobertura e alturas coerentes com a planta. Não acrescente piscina, garagem, pavimentos ou ambientes que alterem o programa.

## IMPORTANTE SOBRE OS BANHEIROS

Modele os dois banheiros completos em 3D, mas apresente apenas o banheiro social durante o tour. O banheiro da suíte permanece na construção, sem uma etapa própria de câmera, sem entrada durante a visita e sem frase exclusiva.

Na apresentação do banheiro social, use:
“Dois banheiros. Mais conforto para todos.”

## QUALIDADE DA MODELAGEM

Busque acabamento de visualização arquitetônica comercial.

Modele paredes com espessura, aberturas reais, esquadrias, portas, rodapés, cobertura, forros e detalhes visíveis no percurso.

Os ambientes precisam estar mobiliados e reconhecíveis. Sofás devem ter estrutura e almofadas; camas, colchões e roupa de cama; cozinhas, marcenaria e equipamentos; os dois banheiros, vaso, cuba, torneiras e box; churrasqueira, corpo, grelha e bancada.

Use detalhes onde a câmera chega perto. Evite aparência de maquete composta apenas por caixas e materiais planos.

Combine madeira natural, pedra clara, tecidos, vidro e metal, com texturas na escala correta, bordas bem resolvidas e pequenas variações de superfície.

A iluminação deve tornar os interiores legíveis, com sombras de contato e uma relação convincente entre luz natural e luminárias. Preserve as vistas pelas janelas e o equilíbrio entre exterior e interior.

Busque a melhor qualidade visual viável para renderização interativa. Não dependa de renderização offline para demonstrar que o site funciona.

## PERCURSO DA CÂMERA

Planeje o percurso sobre a geometria real da casa.

A hero deve mostrar a fachada, com entrada identificável e espaço para o título. O visitante precisa perceber imediatamente que pode explorar a casa pelo scroll.

Durante a visita:

- A câmera passa por portas e espaços livres.
- Não atravessa paredes, vidros fechados, móveis ou bancadas.
- Mantém altura próxima à de uma pessoa e perspectiva natural.
- Usa movimentos suaves e desacelera nos pontos de apresentação.
- Evita giros bruscos, tremores e distorção excessiva.
- Dedica tempo suficiente a cada enquadramento para leitura e contemplação.

Defina pontos intermediários suficientes para que as curvas não cortem obstáculos.

Apresente estar, jantar, cozinha, os três quartos, lavanderia, banheiro social, área gourmet e jardim. A lavanderia pode ter uma apresentação mais breve. O banheiro da suíte não faz parte do percurso de apresentação.

Escolha a ordem mais coerente com a circulação. Reserve a área gourmet e o jardim para o momento final de maior impacto.

Encerre saindo para o jardim e revelando uma vista geral da casa em 3D, seguida da apresentação do projeto.

O scroll controla o avanço e o retorno pelo mesmo percurso. Ao parar de rolar, a câmera deve estabilizar após uma suavização curta. A experiência não deve continuar sozinha como um vídeo.

Mantenha o scroll natural e permita chegar ao conteúdo final sem ficar preso à animação.

## TEXTOS E DIREÇÃO VISUAL

Toda a interface será em português brasileiro.

Use composição editorial, tipografia expressiva, bastante espaço e poucos elementos sobre a cena. A arquitetura deve ocupar a maior parte da tela.

Mostre uma frase principal por ambiente, acompanhada do nome do espaço e, apenas quando necessário, de uma descrição curta.

Use estas frases como direção inicial, refinando-as se conseguir algo melhor. Preserve a informação de que existem dois banheiros na frase correspondente.

Fachada:
“Sua próxima história começa aqui.”

Estar:
“O melhor do dia é chegar.”

Jantar:
“Há conversas que merecem ficar à mesa.”

Cozinha:
“O prazer de criar. A alegria de compartilhar.”

Quarto 02:
“Espaço para crescer no seu próprio ritmo.”

Quarto 03:
“Um lugar para receber quem faz parte da sua vida.”

Suíte:
“Feche a porta. Deixe o dia lá fora.”

Banheiro social — única apresentação de banheiro:
“Dois banheiros. Mais conforto para todos.”

Lavanderia:
“Mais praticidade. Mais tempo para viver.”

Área gourmet:
“Os melhores encontros podem ser em casa.”

Jardim e encerramento:
“Imagine tudo o que você pode viver aqui.”

Sincronize a entrada e a saída dos textos com os enquadramentos. Preserve contraste e evite cobrir os elementos mais importantes.

Inclua indicação discreta para iniciar o scroll e indicador de ambiente/progresso.

Não coloque termos como WebGL, shaders, GPT ou detalhes de implementação na experiência comercial.

## CONVERSÃO

O produto apresentado é o projeto arquitetônico da casa.

Inclua um CTA “Ver planta e detalhes”, que abra um painel funcional com a imagem de referência e o resumo dos ambientes. Permita acessá-lo sem percorrer obrigatoriamente toda a visita.

Não invente preço, metragem confirmada, endereço, autoria profissional, certificações, depoimentos ou contato. Não simule compra, envio de formulário ou integração comercial inexistente.

## DESTINO FINAL: HOSTGATOR

A hospedagem final será a HostGator pelo cPanel. Prepare este site como uma aplicação estática: HTML, CSS, JavaScript e recursos 3D executados no navegador, com o build feito localmente. Não dependa de um servidor Node.js, SSR ou serviços exclusivos de outro provedor para o funcionamento deste projeto.

Confira a URL-base, os caminhos de modelos e texturas, os tipos de conteúdo e o comportamento das rotas na hospedagem. Gere um ZIP contendo somente o conteúdo público do build, com index.html na raiz, pronto para publicar na pasta correta do domínio.

Depois de concluir e validar o site, peça o domínio de destino e a conexão do cPanel. O aluno deve digitar usuário, senha e eventual código de autenticação diretamente no painel, sem colar segredos no chat. Se a skill $astra-hostgator estiver disponível, use-a para conduzir essa etapa.

Inspecione o destino, preserve outros sites e faça backup dos arquivos que serão substituídos. Publique automaticamente apenas com as ferramentas e acessos realmente disponíveis. Se a conexão ainda estiver pendente, entregue a versão local e o ZIP prontos, com o estado da publicação claramente informado.

## IMPLEMENTAÇÃO

Use uma arquitetura adequada a uma experiência 3D web, preferencialmente React, TypeScript e Three.js, com React Three Fiber e Drei quando fizerem sentido no ambiente disponível.

Escolha uma única estratégia principal de sincronização de scroll e câmera, evitando controladores concorrentes.

Organize separadamente:

- Geometria e configuração da casa.
- Materiais e iluminação.
- Percurso e enquadramentos da câmera.
- Capítulos, textos e intervalos de scroll.
- Interface e comportamento responsivo.

Mantenha layout, modelo e percurso baseados na mesma definição espacial. Deixe simples ajustar posições da câmera e textos sem reconstruir a aplicação.

Você pode modelar com código ou usar Blender, caso esteja disponível e melhore o resultado. Se usar Blender, entregue o arquivo editável e exporte os recursos necessários para o navegador.

Priorize recursos locais e modelos/texturas com licença compatível. Registre a origem dos recursos externos utilizados.

## DESEMPENHO E ACESSIBILIDADE

Otimize geometria, texturas, instâncias, sombras e pós-processamento conforme o custo medido.

Busque fluidez próxima de 60 fps no desktop e pelo menos 30 fps em dispositivos móveis compatíveis, tratando esses números como metas a verificar. Informe o ambiente realmente testado e não trate uma viewport móvel emulada como teste em um celular físico.

No celular, adapte enquadramentos e textos ao formato vertical e reduza o custo gráfico preservando a visita 3D.

Implemente carregamento com progresso real e entrada suave na cena. Não deixe a página presa em uma tela vazia.

Respeite prefers-reduced-motion e ofereça navegação acessível por ambientes com transições reduzidas. Para dispositivos sem suporte à experiência 3D, ofereça conteúdo estático útil e identificado.

## EXECUÇÃO E VERIFICAÇÃO

Faça um plano breve e comece a implementar. Tome decisões rotineiras de forma autônoma e registre as suposições relevantes.

Construa em etapas internas:

1. Organização espacial e percurso.
2. Casa completa e mobiliário.
3. Materiais, iluminação e composição.
4. Scroll, textos e interface.
5. Otimização e testes.

Não encerre na etapa de estrutura inicial ou protótipo de volumes básicos. Continue até cumprir os critérios deste pedido.

Faça testes visuais no navegador, com capturas da hero e de cada ambiente apresentado, em desktop e em viewport móvel. Confira separadamente a existência dos dois banheiros no modelo; isso não exige incluir os dois no tour público.

Percorra o site inteiro para baixo e para cima. Verifique scroll rápido, retorno à hero, redimensionamento, carregamento inicial e abertura do painel da planta.

Inspecione também os intervalos entre os enquadramentos. Corrija colisões da câmera, paredes atravessadas, objetos flutuando, materiais ausentes, interiores escuros e textos ilegíveis.

Não considere o projeto concluído apenas porque compilou. Compare o resultado visível com este…

[Continuação cortada no vídeo.]

# Dev-Full-stack-CITAV
Reportório criado para uma formação 
 Semântica e Estrutura de Conteúdo
​A transição de divisões genéricas para tags semânticas é o ponto mais forte desta atualização:
​Uso do <main>: Fundamental para indicar o conteúdo principal da página, ajudando motores de busca e leitores de ecrã a identificar o "coração" do documento.
​Substituição de <div> por <article>: Utilizaste corretamente <article> nos cards de serviços (sobre), equipas e pilotos. Como cada um destes itens tem um significado independente e completo, esta é a tag ideal.
​Tags de Imagem (<figure> e <figcaption>): A inclusão destas tags para as imagens de destaque e do pódio é uma excelente prática. Isso agrupa logicamente a imagem à sua legenda, algo que uma <div> simples não faz.
​2. Correções de Sintaxe e Validação
​Identificaste e corrigiste erros que impediriam a renderização correta ou a validação do W3C:
​Fechamento de Tags: Corrigiste o parágrafo no card "Tecnologia de Ponta" e o link no rodapé (<a>). Tags mal fechadas podem "quebrar" o layout em navegadores diferentes.
​Hierarquia de Títulos (<h1> - <h3>): Corrigir o <h4> para <h3> no terceiro card da secção "Sobre" garante que a estrutura lógica do documento seja consistente.
​Atributo lang: Adicionar lang="pt" na tag <html> é crucial para que os sintetizadores de voz usem a pronúncia correta e para o SEO local.
​3. Formulários e Acessibilidade
​Estas alterações impactam diretamente a experiência do utilizador (UX):
​Tipo de Input: Alterar de type="text" para type="email" ativa validações automáticas no navegador e altera o teclado em dispositivos móveis para incluir o símbolo @.
​Ligação label e input: A adição do id="email-input" no campo e o for="email-input" na label permite que, ao clicar no texto da label, o cursor foque automaticamente no campo.
​Atributos alt: Garantiste que as imagens têm descrições textuais, tornando o site acessível para pessoas com deficiência visual.
​4. Pequenos Ajustes de Texto e Erros Tipográficos
​Correção de <strong>: Corrigiste a gralha <stron> para <strong> na secção de circuitos, garantindo que o negrito seja aplicado corretamente.
​Links de Imagem: A atualização para URLs válidas e funcionais permite que o site seja visualizado conforme planeado, sem ícones de "imagem quebrada".

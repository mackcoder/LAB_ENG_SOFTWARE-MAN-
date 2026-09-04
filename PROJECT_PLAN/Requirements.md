# 📋Levantamento de Requisitos
## Instruções:
<div align="justify">
O objetivo é identificar o problema, propor elementos da solução, negociar diferentes abordagens e
especificar um conjunto preliminar de requisitos da solução em uma atmosfera que seja propícia para o
cumprimento da meta
</div>

## Requisitos funcionais

 ID  | Tópico | Requisito
-----|----------|---------
RF01 | Autenticação de Usuário | O sistema deve permitir que o usuário crie uma conta e realize login via e-mail e senha ou autenticação em um clique (ex: Google).
RF02 | Categorização Automática | O sistema deve classificar o documento em categorias predefinidas (ex: Veículos, Imóveis, Serviços) e exibi-lo na tela inicial.
RF03 | Pré-visualização e Validação | O sistema deve exibir uma tela de confirmação após a captura da foto para que o usuário valide visualmente se o texto está nítido antes do processamento.
RF04 | Captura e Envio de Documentos | O sistema deve permitir o upload de contratos em formato PDF ou a captura direta de páginas físicas através da câmera do dispositivo.
RF05 | Extração de Texto (OCR) | O sistema deve extrair automaticamente os textos contidos nas imagens ou arquivos enviados.
RF06 | Chat Interativo sobre o Contrato | O sistema deve permitir que o usuário faça perguntas específicas sobre o documento analisado, aceitando entradas via texto ou áudio.
RF07 | Síntese por Texto | O sistema deve disponibilizar um botão para narrar em áudio os principais pontos e alertas identificados no contrato.
RF08 | Exibição de resumo estruturado | O sistema deve apresentar de forma organizada a análise do contrato em blocos como (Valores, Cláusulas Críticas, Parcelas)
RF09 | Preferências Consideradas | O perfil do usuário e suas preferências devem ser levadas em consideração pela IA

## Requisitos não funcionais

  ID  | Tópico | Requisito
------|--------| ---------
RNF01 | Segurança | O sistema deve solicitar dados sensíveis de forma contextual e permitir que o usuário opte por não salvar essas informações em conversas futuras.
RNF02 | Disponibilidade | A aplicação web deve ser hospedada em plataforma com deploy contínuo acessível publicamente via protocolo HTTPS.
RNF03 | Privacidade | O sistema deve garantir a segurança e anonimato dos dados de seus usuários
RNF04 | Usabilidade | O sistema deve traduzir termos jurídicos complexos para linguagem acessível, priorizando frases curtas e diretas.
RNF05 | Acessibilidade | A interface deve manter contraste adequado de cores nos textos, fontes legíveis e botões com área de toque suficiente.

## Usabilidade

  ID  | Tópico | Requisito
------|--------| ---------
RU01 | Facilidade de Uso | Um usuário novato com baixa instrução deve conseguir concluir o envio de um documento sem necessidade de tutoriais ou manuais.
RU02 | Linguagem Centrada no Usuário | A interface e o assistente devem substituir o vocabulário jurídico por linguagem simples e direta do cotidiano.
RU03 | Prevenção de Erros | A interface deve permitir refazer a captura da imagem com um único clique caso a foto fique escura ou cortada.
RU04 | Eficiência de Interação | O caminho da tela inicial até a abertura da câmera para uma nova análise deve ser de poucos toques
RU05 | Acessibilidade Visual | Elementos clicáveis devem ter área considerável para toque e contraste adequado de cores.

## Confiabilidade

  ID  | Tópico | Requisito
------|--------| ---------
RC01 | Integridade de Sessão e Dados | O sistema deve impedir a perda do texto digitado no chat ou da imagem enviada caso a conexão oscile durante a requisição.
RC02 | 

## Desempenho

  ID  | Tópico | Requisito
------|--------| ---------
RD01

## Facilidade de Suporte

  ID  | Tópico | Requisito
------|--------| ---------
RS01


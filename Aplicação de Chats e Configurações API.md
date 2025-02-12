Para interagir com o Azure OpenAI, os desenvolvedores utilizam chamadas de API REST. O processo  envolve:

>Criar um recurso no Azure OpenAI e obter as chaves de acesso e endpoint.
>Autenticar-se via chave de API ou Azure Active Directory (AAD).
>Enviar requisições HTTP para os endpoints disponíveis, como /v1/completions (para geração de texto) ou /v1/images/generations (para geração de imagens).
>Processar a resposta JSON contendo o resultado da IA.
A API suporta customização com deployment de modelos, ajuste fino (fine-tuning) e parametrização, como temperatura, número máximo de tokens, etc.

O Semantic Kernel é um SDK da Microsoft que permite integrar IA generativa a aplicações, combinando planejamento, memória e habilidades (skills). Permite:

>Orquestrar chamadas ao Azure OpenAI de maneira modular.
>Criar pipelines de IA, combinando diferentes modelos e funções.
>Incorporar memória (armazenamento de contexto para chatbots, por exemplo).
>Interagir com serviços externos (bancos de dados, APIs, sistemas legados).
O Semantic Kernel é usado para construir aplicações de IA mais eficientes e adaptáveis, reduzindo a necessidade de chamadas diretas e repetitivas à API.

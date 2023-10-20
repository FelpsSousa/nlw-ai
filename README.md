# upload.ai

![Exemplo de Aplicação](/screenshots/tela-principal.png)

## Visão Geral

Este projeto é uma aplicação de inteligência artificial que gera transcrições de vídeos, títulos e palavras-chave para postagens no YouTube. A aplicação funciona da seguinte maneira: o usuário faz upload de um vídeo .mp4 que é processado localmente no navegador, otimizando o processamento.

O vídeo é convertido em .mp3 e, por meio de APIs implementadas, é transformado em texto transcrito. O usuário pode inserir palavras-chave como entrada para orientar a geração de títulos e descrições.

O modelo usado é a versão gratuita da OpenAI, GPT 3.5-turbo 16k. O usuário pode escolher a "temperatura" para ajustar a criatividade da saída.

## Tecnologias Utilizadas

- API OpenAI
- JavaScript
- TypeScript
- Axios
- Prisma
- Tailwind CSS
- Shadcn/ui
- FFMPEG

## Executar a Aplicação:

1. Navegue até o diretório `upload-ai-api` e execute:
```npm run dev``` 

2. Navegue até o diretório `upload-ai-web` e execute:
```npm run dev```

Pronto! Agora a aplicação estará pronta pára rodar no navegador. `http://localhost:5173/`

## Como Usar

1. Faça o upload de um vídeo .mp4.
2. Insira palavras-chave para orientar a geração.
3. Escolha opções para o título e a descrição do YouTube.
4. Defina a "temperatura" desejada.
5. Execute a aplicação.

## Capturas de Tela

### Tela de Upload
![Tela de Upload](/screenshots/video-carregado.png)
---
### Opções de Processamento: Título.
![Tela de Opções](/screenshots/gerando-titulo.png)
---
### Opções de Processamento: Descrição.
![Tela de Opções](/screenshots/gerando-descricao.png)
---
### Resultado do Processamento: Descrição.
![Tela de Resultado](/screenshots/saida-descricao.png)

<!--
## Licença

Este projeto é licenciado sob [Sua Licença](URL_DA_LICENÇA). Consulte o arquivo [LICENSE](/LICENSE) para obter detalhes.
-->
---
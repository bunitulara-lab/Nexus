# NEXUS 2.0

Projeto da interface e da aplicação NEXUS 2.0.

## REGRA OBRIGATÓRIA — PRÉ-VISUALIZAÇÃO DO PROJETO

**A pré-visualização da NEXUS deve executar a aplicação; nunca deve usar o PDF de documentação como pré-visualização.**

- O ponto de entrada da aplicação web é o arquivo `index.html` na raiz deste repositório.
- Ao abrir a pré-visualização ou executar o projeto, iniciar/servir a aplicação web a partir da raiz do repositório e renderizar o `index.html` no navegador.
- A pré-visualização deve mostrar a interface real e navegável da NEXUS, em funcionamento no navegador. Não abrir, incorporar, converter ou apresentar o PDF como se fosse a aplicação.
- O documento PDF e os arquivos Markdown em `docs/` são **somente documentação e especificações**. Eles não são páginas da aplicação, não são o ponto de entrada e não podem substituir a execução do projeto.
- Se a plataforma de hospedagem/pré-visualização exigir configuração, configurar o projeto como site estático com a raiz do repositório como diretório de saída/publicação, usando `index.html` como página inicial. Não definir o PDF como artefato de entrada.
- Se a pré-visualização atual estiver apontando para o PDF, corrigir a configuração para apontar para a aplicação web e testar o resultado em navegador, tanto em celular quanto em desktop.

## Estado atual

O `index.html` contém uma primeira versão visual da interface. O envio de mensagens ainda usa uma resposta local de demonstração: o cérebro real, autenticação, memória, voz, ferramentas e NEXUS GUARDIAN ainda precisam ser implementados e testados. Não apresentar esses recursos como funcionais antes da integração real.

## Documentação

- [Segundo documento completo — especificação e roteiro passo a passo](docs/NEXUS_2_0_SEGUNDO_DOCUMENTO_COMPLETO.md)

A documentação orienta a implementação, mas **não é a pré-visualização executável** da aplicação.

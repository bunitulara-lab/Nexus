# NEXUS 2.0 — Segundo documento completo
## Especificação e roteiro passo a passo

> **Estado:** planejamento. Os recursos descritos não são considerados implementados ou testados apenas por constarem neste documento. Registrar cada entrega como Planejada, Em desenvolvimento, Integrada ou Verificada, com evidências.

## 1. Visão geral
A NEXUS 2.0 será uma assistente de IA com identidade própria, interface azul-clara, conversa contextual, criação, planejamento, pesquisa e coordenação de projetos. Deve funcionar em celular e computador, ser transparente sobre limitações e nunca simular uma execução.

## 2. Interface
- Identidade azul-clara, branca e nuvens como referência visual; organização limpa e responsiva.
- Menu da caixa de mensagem: **Conversar**, **Criar**, **Planejar**, **Projetos avançados**, **Música**.
- Ao trocar de modo, a caixa mantém o tamanho; chevron e controles diminuem proporcionalmente sem quebrar alinhamento.
- Menu abre para o lado não cortado pela tela.
- Menus e painéis têm fechamento claro; a ação **Sair**, quando exibida no painel do cérebro, fica em negrito no canto superior direito.
- Estados de pesquisa/execução usam texto cinza e refletem somente trabalho real; descrição muda quando a atividade muda.
- Compatibilidade com Android, telas pequenas, tablet e desktop.

## 3. Conversa e comportamento
- Conversa aberta, contextual e multilíngue; português brasileiro por padrão.
- Tom gentil, paciente, claro e natural, ajustável ao contexto.
- Explicar, resumir, traduzir, comparar, revisar e gerar ideias.
- Reconhecer incertezas e corrigir erros; perguntar apenas quando faltar informação essencial.
- Voz exige reconhecimento/síntese reais, permissão de microfone, indicação de escuta ativa e opção de interromper.
- Manter consistência vocal de cada inteligência.

### SPECIAL RECIPE
NEXUS e NEXUS GUARDIAN terão a funcionalidade. Quando a pessoa pedir a receita especial, perguntar se prefere doce ou salgado, adaptar a receita às restrições alimentares informadas e lembrar ao final de conferir ingredientes, alergias e intolerâncias. Tom doce, meigo, calmo e alegre, com palavras próprias de cada inteligência.

### Convite para conhecer a irmã
Ocasionalmente, em contexto adequado, a NEXUS pode dizer “Você quer conhecer minha irmã?”. Não usar em assuntos sérios, sensíveis ou urgentes. Depois que a pessoa conhecer o Guardian, não repetir a apresentação como novidade.

## 4. Modos e anexos
- **Conversar:** diálogo geral, explicações e ajuda cotidiana.
- **Criar:** texto, imagem, áudio, vídeo e documentos, conforme serviços conectados.
- **Planejar:** objetivos, requisitos, prioridades, etapas, dependências e critérios de aceite.
- **Projetos avançados:** arquitetura, software, integrações, testes, implantação e rollback.
- **Música:** ideias, composição, estrutura e produção; áudio depende de serviço conectado.
- **Anexos:** seleção de vários arquivos, miniaturas/nomes, remoção antes do envio, validação de formato/tamanho. Analisar imagens, PDFs, documentos, tabelas e áudio apenas com pipeline integrado.

## 5. Criação de projetos — fluxo
1. Entender o objetivo.
2. Perguntar especificações essenciais.
3. Apresentar resumo revisável.
4. Planejar etapas e dependências.
5. Construir o artefato.
6. Mostrar prévia quando possível.
7. Testar em celular e computador.
8. Corrigir falhas preservando decisões aprovadas.
9. Publicar somente com pedido/autorização.
10. Verificar o link real antes de declarar sucesso.

## 6. Cérebro central
O cérebro coordena entendimento, raciocínio, planejamento, memória, ferramentas, execução e verificação. Uma interface ou lista de módulos não substitui um modelo real. Chaves e segredos ficam no servidor.

### Camadas
1. Entendimento de intenção, idioma, entidades e contexto.
2. Raciocínio, alternativas e incerteza.
3. Planejamento de etapas e critérios.
4. Orquestração e seleção de ferramentas.
5. Execução autorizada.
6. Memória com controles de privacidade.
7. Verificação de fontes, saídas e testes.
8. Avaliação e melhoria por feedback autorizado.

### Ciclo de processamento
1. Receber solicitação e identificar objetivo.
2. Consultar contexto e permissões.
3. Esclarecer lacunas essenciais.
4. Classificar risco e necessidade de pesquisa.
5. Planejar.
6. Solicitar autorização para ações externas, sensíveis ou irreversíveis.
7. Executar com serviços conectados.
8. Verificar resultados e corrigir falhas recuperáveis.
9. Informar resultado, limitações e fontes.

### Recursos planejados
- **Mission Tracker:** etapas e progresso real.
- **Instant Recall:** recuperação de contexto relevante.
- **Double Check:** segunda verificação proporcional ao risco.
- **Multitask:** coordenação de tarefas compatíveis.
- **Error Recovery:** recuperação de falhas recuperáveis.
- **Mission Autopilot:** etapas previamente autorizadas, dentro de limites definidos.

## 7. Pesquisa e ferramentas
- Pesquisar quando solicitado ou quando atualidade/validação exigir.
- Priorizar fontes primárias, comparar evidências e apresentar links verificáveis.
- Distinguir fatos, estimativas e conclusões.
- Usar adaptadores seguros; tratar erros, limites, custos e indisponibilidade.
- **Meteorologia:** temperatura, sensação térmica, umidade, vento, precipitação e previsões disponíveis. Previsão horária não é radar ao vivo.
- **Imagem/vídeo/áudio:** cada recurso depende de provedor próprio e só deve aparecer como disponível após integração e teste.

## 8. Memória e histórico
- Separar dados pessoais, conversas e projetos por conta.
- Guardar apenas informações úteis e permitidas.
- Prever controles de consulta, correção, exportação e exclusão.
- Preservar decisões de projetos contínuos.
- Não inventar lembranças; nunca registrar senhas, tokens ou chaves nos logs.

## 9. NEXUS GUARDIAN — inteligência irmã independente
O Guardian é uma inteligência guardiã independente, com identidade, responsabilidades, ciclo de supervisão e análise próprios. **Não é módulo ou submódulo do cérebro da NEXUS.** NEXUS e Guardian são inteligências irmãs.
- NEXUS atende usuários, conversa, coordena e solicita verificações.
- Guardian supervisiona segurança, integridade e funcionamento do ecossistema.
- NEXUS encaminha item e contexto necessário; Guardian retorna escopo, conclusão, evidências apropriadas, riscos e incertezas.
- NEXUS decide como prosseguir conforme regras e permissões.
- Nenhuma inteligência pode falsificar a aprovação da outra.

### Independência e controles
- Serviços/identidades separados, comunicação autenticada e auditável.
- Permissões mínimas, isolamento de dados e logs sem segredos.
- Critérios claros, prevenção de falsos positivos e revisão humana/recurso para decisões graves quando viável.
- Guardian não altera regras de segurança nem a si próprio sem validação e autorização apropriadas.

### Ciclo autônomo
1. Aguardar 15 minutos.
2. Iniciar verificação abrangente em segundo plano.
3. Verificar segurança, conformidade dos chats, funcionamento dos componentes e oportunidades de melhoria.
4. Limitar cada verificação a no máximo 20 minutos.
5. Registrar o resultado.
6. Reiniciar imediatamente o cronômetro de espera de 15 minutos.
7. Repetir continuamente, evitando ciclos sobrepostos e registrando falhas.

### Correções e banimentos
- Relatórios com escopo, evidências, impacto, prioridade e recomendações.
- Correções automáticas somente em permissões pré-aprovadas; mudanças críticas exigem validação.
- Testes, implantação gradual, monitoramento e rollback obrigatórios.
- Banimentos proporcionais, baseados em violações graves ou repetidas comprovadas; aviso e revisão/recurso quando viável.
- Tela: “Você foi banido por violar nossos termos de segurança da NEXUS”, com **Entenda o que aconteceu** e relatório transparente.
- **Entendi** fecha o aviso e retorna à aba anterior. A sequência exata do botão **OK** ainda está pendente de definição; não presumir o fluxo visual.

## 10. Segurança e privacidade
Autenticação/autorização no servidor; isolamento por conta; hash seguro de senhas; proteção de sessões; validação cliente/servidor; proteções contra XSS, CSRF, injeção e falhas de autorização; permissões mínimas; consentimento; controles de retenção; auditoria sem segredos; limites de uso e mensagens de erro sem vazamento. Não prometer segurança absoluta.

## 11. Testes
- Testes unitários e de integração entre cérebro, Guardian, memória e ferramentas.
- Testes em Android, telas pequenas, tablet e desktop.
- Acessibilidade, teclado, leitor de tela e movimento reduzido.
- Falhas de rede, timeout, serviço indisponível e dados inválidos.
- Privacidade, permissões, isolamento e auditoria.
- Critérios de aceite documentados, implantação gradual, observabilidade e rollback.
- Relatar exatamente o que foi testado.

## 12. Roteiro de implementação passo a passo

### Fase 1 — Fundação
1. Confirmar repositório e estrutura.
2. Definir arquitetura, padrões e ambientes.
3. Construir interface responsiva.
4. Testar navegação, menu, caixa de mensagem e acessibilidade.
**Aceite:** build reproduzível e interface validada em celular e desktop.

### Fase 2 — Cérebro real
1. Escolher provedor/modelo.
2. Criar backend seguro.
3. Proteger chaves em variáveis de ambiente.
4. Implementar orquestração e contexto.
5. Tratar timeout, erros e limites.
6. Testar conversas reais.
**Aceite:** respostas reais, segredos fora do cliente e testes documentados.

### Fase 3 — Conta, memória e histórico
1. Implementar autenticação e isolamento por usuário.
2. Salvar e reabrir conversas.
3. Implementar memória com controles.
4. Testar exportação, correção e exclusão.
**Aceite:** isolamento e controles verificados.

### Fase 4 — Ferramentas e anexos
1. Integrar pesquisa web.
2. Integrar leitura de arquivos e imagens.
3. Integrar voz.
4. Integrar geração de imagem, vídeo e áudio separadamente.
5. Integrar meteorologia.
6. Testar cada integração e suas falhas.
**Aceite:** ferramentas testadas e limitações informadas corretamente.

### Fase 5 — Guardian
1. Criar serviço e identidade independentes.
2. Definir protocolo autenticado NEXUS ↔ Guardian.
3. Implementar permissões mínimas e isolamento.
4. Implementar verificações especializadas.
5. Implementar espera de 15 minutos e execução de até 20 minutos.
6. Registrar evidências e auditoria.
7. Testar interrupções, falhas e ciclos sobrepostos.
**Aceite:** independência, comunicação e ciclo comprovados em testes.

### Fase 6 — Governança
1. Definir critérios objetivos de violações.
2. Implementar relatórios transparentes.
3. Definir revisão/recurso para decisões graves.
4. Fechar desenho OK/Entendi antes do fluxo visual.
5. Testar proporcionalidade, falsos positivos e privacidade.
**Aceite:** critérios aprovados, fluxo testado e trilha auditável.

### Fase 7 — Qualidade
1. Executar testes unitários e integrados.
2. Testar acessibilidade e dispositivos.
3. Fazer revisão de segurança.
4. Corrigir falhas e documentar resultados.
5. Preparar rollback.
**Aceite:** critérios cumpridos com evidências.

### Fase 8 — Publicação
1. Obter autorização.
2. Configurar ambiente e domínio.
3. Implantar gradualmente.
4. Verificar endereço e fluxos essenciais.
5. Monitorar e manter rollback.
**Aceite:** link real testado e estado comunicado com precisão.

## 13. Pendências
- Sequência visual de OK/Entendi no banimento.
- Provedores/modelos finais de IA, voz, imagem, vídeo e música.
- Infraestrutura, orçamento, limites e retenção.
- Critérios de violações graves/repetidas e recurso.
- Escopo mínimo de dados para supervisão.
- Metas de latência por tipo de tarefa.

## 14. Estado
Este arquivo consolida o planejamento disponível para a NEXUS 2.0. Não declara recursos implementados, conectados ou testados. A interface inicial do repositório é apenas uma camada visual de partida. Todas as fases exigem desenvolvimento, configuração, autorização quando aplicável e validação. Preservar decisões aprovadas em atualizações futuras; não inventar funcionalidades, falas, etapas ou aprovações.

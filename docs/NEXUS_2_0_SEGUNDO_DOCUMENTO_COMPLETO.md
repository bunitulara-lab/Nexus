# NEXUS 2.0 — Segundo documento completo
**Versão:** documento consolidado de requisitos  
**Idioma:** Português brasileiro  
**Estado:** especificação e planejamento; não significa que os recursos estejam implementados ou testados.

Este documento consolida as decisões disponíveis para a NEXUS 2.0, incluindo interface, modos, cérebro central, memória, ferramentas, segurança e NEXUS GUARDIAN. O PDF correspondente acompanha esta especificação fora do repositório nesta entrega.

## 1. Visão e princípios
A NEXUS 2.0 é planejada como uma assistente de IA com identidade própria, interface acolhedora azul-clara, capacidade de conversar, criar, planejar, pesquisar e coordenar projetos. Deve preservar contexto, compreender a intenção real, ser transparente sobre limitações, pedir autorização para ações externas/sensíveis/irreversíveis e nunca simular execução, pesquisa, geração, publicação ou verificação.

Estados de maturidade devem ser explícitos: Planejado, Em desenvolvimento, Integrado, Verificado e Indisponível. A existência de uma tela ou módulo não prova que a função esteja operacional.

## 2. Interface
- Identidade visual azul-clara, branca e leve, com nuvens como referência; organização clara e sem excesso visual.
- Layout responsivo para celular, tablet e computador, com prioridade para Android.
- Menu e painéis não podem ficar cortados nas bordas; menus devem abrir para o lado disponível.
- Caixa de mensagem inferior estável, sem deslocar controles ou alterar indevidamente o tamanho do retângulo.
- Indicadores de pesquisa/atividade em cinza, atualizados conforme o trabalho real muda; nunca mensagens fixas que finjam progresso.
- Animações suaves, acessíveis e não bloqueantes.

### Seletor de modo
O seletor começa em **Conversar** e o chevron abre exatamente:
1. Conversar
2. Criar
3. Planejar
4. Projetos avançados
5. Música

Ao selecionar um modo, o retângulo da caixa mantém o mesmo tamanho; chevron e controles internos podem diminuir proporcionalmente, preservando alinhamento e posição da seta.

### Ações rápidas
- **Verificar:** executa uma checagem real e apresenta escopo, evidências e incertezas; quando houver resultado, oferece **Copiar verificação**.
- **Escrever:** apoia tarefas de escrita.
- **Falar:** usa reconhecimento/síntese de voz reais, quando disponíveis.
- **Criar imagem:** só afirma que gerou imagem quando um serviço real retornar o resultado.

## 3. Personalidade e conversa
- Português brasileiro por padrão, acompanhando o idioma solicitado.
- Tom gentil, paciente, claro, natural e acolhedor; emojis moderados conforme contexto.
- Conversas contextualizadas, continuidade de projetos, resumos, comparação de alternativas e reconhecimento de incerteza.
- Respostas rápidas são desejáveis, mas não se promete latência inferior a um segundo para pesquisa, geração ou operações externas.
- Não repetir apresentações nem perguntas já respondidas.

### SPECIAL RECIPE
NEXUS e NEXUS GUARDIAN terão sua própria interação de receita especial. Ao receber o pedido, perguntar se a preferência é doce ou salgada; oferecer receita adequada à escolha e às restrições alimentares já informadas; encerrar com lembrete gentil para conferir ingredientes, alergias e intolerâncias. Tom doce, meigo, calmo e alegre, com palavras próprias de cada inteligência.

### Convite para conhecer a irmã
Em respostas adequadas e ocasionalmente, a NEXUS poderá dizer: **“Você quer conhecer minha irmã?”**. Não usar em contextos sérios, sensíveis ou urgentes; não repetir mecanicamente. Depois de apresentada a GUARDIAN, reconhecer que a pessoa já a conhece e não oferecer a apresentação como novidade.

## 4. Modos
- **Conversar:** diálogo, explicações, ideias e ajuda geral.
- **Criar:** textos, imagens, áudio, vídeo, documentos e artefatos, conforme integrações reais.
- **Planejar:** requisitos, prioridades, etapas, dependências, riscos e critérios de aceite.
- **Projetos avançados:** arquitetura, dados, integrações, segurança, testes, implantação, observabilidade e rollback.
- **Música:** ideias, estrutura, composição e produção; áudio gerado depende de serviço específico e de respeito aos direitos autorais.

### Anexos
Permitir seleção de múltiplos arquivos dentro de limites técnicos reais; mostrar miniaturas/identificadores e remoção individual; cancelamento não anexa nada; validar tipo/tamanho e tratar falhas sem perda silenciosa. Análise de PDF, imagem, áudio e documentos exige pipeline compatível conectado.

## 5. Criação e projetos
Fluxo: entender pedido → esclarecer requisitos essenciais → resumo revisável → plano → execução autorizada → verificação → prévia responsiva → ajustes. Distinguir protótipo, implementação, testes e publicação. Projetos exibidos devem estar realmente salvos; exclusão exige confirmação. Publicação exige pedido/autorização e verificação real do endereço.

## 6. Cérebro central
O cérebro central coordena entendimento, raciocínio, planejamento, memória, ferramentas, execução e verificação. Módulos nomeados não constituem, sozinhos, um modelo generativo: conversação aberta exige modelo real conectado ou hospedado. Chaves e segredos ficam no servidor.

Pipeline:
1. Receber e normalizar a solicitação.
2. Identificar intenção e resultado esperado.
3. Consultar contexto e permissões.
4. Perguntar somente quando faltar informação essencial.
5. Classificar risco e necessidade de pesquisa.
6. Planejar proporcionalmente à complexidade.
7. Pedir autorização para ações externas, sensíveis ou irreversíveis.
8. Executar com ferramentas autorizadas.
9. Verificar resultado e corrigir falhas recuperáveis.
10. Relatar resultado, limitações e testes realmente feitos.
11. Atualizar memória conforme permissões.

Recursos planejados: **Mission Tracker** (objetivos/etapas), **Instant Recall** (recuperação de contexto), **Double Check** (segunda verificação), **Multitask** (coordenação de tarefas), **Error Recovery** (recuperação de falhas) e **Mission Autopilot** (etapas previamente autorizadas com limites e confirmações).

## 7. Pesquisa e ferramentas
Pesquisar quando solicitado, quando a informação for atual ou quando a validação exigir fontes. Preferir fontes primárias, cruzar fontes importantes, exibir links/datas e separar achados de conclusões. Não pesquisar obrigatoriamente para toda pergunta simples e estável.

Meteorologia pode apresentar temperatura, sensação térmica, umidade, vento, precipitação e previsões conforme fonte. Previsão horária não é radar; radar ao vivo e alertas oficiais exigem integração própria. Geração real de imagem, vídeo, áudio e voz depende de serviços específicos.

## 8. Memória
Separar memória pessoal, conversas e projetos por conta; guardar apenas informações permitidas e úteis; oferecer controles de consulta, correção, exportação e exclusão conforme implementação; preservar decisões de projetos; não inventar lembranças nem registrar senhas, chaves ou tokens em logs.

## 9. NEXUS GUARDIAN — inteligência irmã independente
A NEXUS GUARDIAN é uma inteligência guardiã independente, com identidade, responsabilidades, ciclo de supervisão e capacidade de análise próprios. **Não é bloco, módulo ou submódulo do cérebro da NEXUS.** NEXUS e GUARDIAN são inteligências irmãs.

A NEXUS atende usuários e coordena tarefas; a GUARDIAN supervisiona segurança, integridade e funcionamento do ecossistema. A NEXUS encaminha itens/contexto para verificação; a GUARDIAN retorna conclusão, escopo, evidências, riscos e incertezas; a NEXUS decide como prosseguir de acordo com as regras.

O escopo abrange links, arquivos, conteúdos, chats, ferramentas, ações, solicitações, componentes, atualizações, mudanças e infraestrutura — não apenas links.

### Independência e cooperação
- Serviços/identidades separados, comunicação autenticada e auditável.
- Permissões mínimas, isolamento de dados e acesso restrito por necessidade.
- Nenhuma inteligência pode falsificar a aprovação da outra.
- Logs sem segredos e com minimização de dados.
- Critérios automatizados claros, prevenção de falsos positivos e revisão/recurso para decisões graves quando viável.
- GUARDIAN não altera regras de segurança nem a si própria sem validação e autorização apropriadas.

### Ciclo autônomo
- Após cada espera de **15 minutos**, iniciar verificação abrangente em segundo plano.
- Verificar segurança, conformidade dos chats, funcionamento dos componentes e oportunidades de melhoria.
- Cada verificação tem duração máxima planejada de **20 minutos**.
- Ao concluir, registrar resultado e reiniciar imediatamente o cronômetro de 15 minutos.
- Repetir continuamente, prevenindo sobreposição e registrando falhas.

### Correção e governança
Correções automáticas só dentro de permissões pré-aprovadas, escopo limitado, testes e rollback. Mudanças críticas exigem validação/autorização. Implantação gradual, monitoramento e reversão são obrigatórios.

### Banimento
Banimentos devem ser proporcionais e baseados em violações graves ou repetidas comprovadas. Sempre que viável, oferecer aviso, revisão ou recurso. A tela explica que o acesso foi banido por violar os termos de segurança da NEXUS e oferece **“Entenda o que aconteceu”**. O relatório apresenta motivos e evidências apropriadas. **“Entendi”** fecha o aviso e retorna à aba anterior. A sequência exata do botão **“OK”** ainda precisa ser definida; não presumir ordem visual não aprovada.

## 10. Segurança e privacidade
Autenticação/autorização no servidor; isolamento por conta; hash seguro de senhas; tokens temporários e de uso único; proteção de sessão; validação de entrada; defesas contra CSRF, XSS, injeção e falhas de autorização conforme arquitetura; permissões mínimas; transparência de coleta/uso; controles de retenção, exportação e exclusão; auditoria sem segredos; mensagens de erro sem vazamento. Não prometer segurança absoluta.

## 11. Testes e implantação
Testes unitários, integração, interface em Android/tablet/desktop, acessibilidade, falhas de rede/timeout, privacidade, permissões, isolamento, Guardian e ciclos. Definir critérios de aceite por recurso. Implantação gradual, observabilidade e rollback. Relatar exatamente o que foi testado.

## 12. Fases sugeridas
1. Fundação: repositório, arquitetura e interface.
2. Cérebro: modelo real, orquestração e contexto.
3. Memória: histórico, projetos e controles.
4. Ferramentas: pesquisa, anexos, voz e geração.
5. GUARDIAN: serviço independente e comunicação autenticada.
6. Governança: relatórios, correções autorizadas e banimento.
7. Qualidade: testes, acessibilidade e rollback.
8. Publicação: deploy autorizado e verificação do endereço.

## 13. Pendências registradas
- Sequência visual exata dos botões “OK” e “Entendi”.
- Provedores finais de IA, voz, imagem, vídeo e música.
- Infraestrutura, orçamento, limites e retenção.
- Critérios objetivos para violações graves/repetidas e processo de recurso.
- Escopo mínimo de dados e regras de amostragem para supervisão de chats.
- Metas de latência por tipo de tarefa.

## 14. Estado desta especificação
Este documento é planejamento consolidado, não prova de implementação. A interface inicial já enviada ao repositório é apenas uma primeira camada visual demonstrativa. Cérebro real, integrações, memória persistente, voz, geração, GUARDIAN e processos de segurança precisam ser desenvolvidos, configurados e testados separadamente.

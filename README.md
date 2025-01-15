
<h1 align="center">GitHub Advanced Security: Protegendo seu Workflow</h1>
<h5 align="center">Revisão para Português Brasil @paulanunes85 - 2025</h5>

Se você for ministrar esta sessão, consulte a página de [recursos de entrega de sessão](https://github.com/microsoft/aitour-github-advanced-security-workflow/tree/main/session-delivery-resources#readme) para slides, scripts de demonstração e outros recursos.

## Descrição da Sessão

Os recursos do GitHub Advanced Security são integrados diretamente ao fluxo de trabalho de desenvolvimento, tornando-os fáceis de usar e dando aos desenvolvedores a capacidade de identificar possíveis problemas de segurança o mais cedo possível no ciclo de vida do desenvolvimento de software.

Aprenda como evitar que problemas de segurança comuns sejam mesclados ao seu código, como encontrar e corrigir vulnerabilidades mais rapidamente com IA e como manter suas dependências atualizadas via GitHub Advanced Security.

- Material [GitHub Advanced Security - Protegendo seu fluxo de trabalho](https://github.com/paulanunes85/Github-Advanced-Security-Workflow-pt-br/blob/main/PT-BR_BRK422_Tech%20-%20GitHub%20Advanced%20Security%20-%20Paula%20Silva.pdf)

## Resultados de Aprendizagem

- Aprenda como habilitar alertas do Dependabot e receber notificações sobre dependências vulneráveis, incluindo um link para o arquivo afetado no projeto e informações sobre uma versão corrigida.
- Veja como atualizar automaticamente ou gerar uma solicitação de pull para atualizar dependências vulneráveis.
- Descubra como atualizar automaticamente pacotes suportados usados pelo seu repositório em uma programação que você configura.
- Aprenda como habilitar a varredura de segredos e a proteção de push que previne proativamente vazamentos de segredos ao escanear o código no commit e bloquear um push se um segredo estiver presente.
- Encontre vulnerabilidades antes que elas sejam mescladas ao código com varreduras automatizadas do CodeQL.
- Aprenda como obter correções de código sugeridas por IA em solicitações de pull.

## Tecnologia Utilizada

        - GitHub Advanced Security
        - Dependabot
        - Varredura de Segredos
        - CodeQL
        - Copilot Autofix
        - GitHub Actions

## Pré-requisitos

Antes de participar do workshop, há somente um pré-requisito: ter uma conta pública do GitHub. Todos os recursos, dependências e dados já fazem parte do repositório.
- **Pré-requisitos:** Para usar o GitHub Copilot, você deve ter uma assinatura ativa do GitHub Copilot Business ou Enterprise. Inscreva-se para Copilot Free para VS Code apenas para fim de treinamento [Copilot for free para VS Code](https://learn.microsoft.com/en-us/visualstudio/ide/copilot-free-plan?view=vs-2022).
- **Já possuir acesso ou Habilitar GitHub Advanced Security:** [Habilitando a segurança avançada do GitHub](https://resources.github.com/pt-br/learn/pathways/security/essentials/enabling-github-advanced-security/)
- **Ter acesso a uma organização GitHub com licença do GitHub Advanced Security**

## Recursos Adicionais e Aprendizado Contínuo

| Recursos          | Links                             | Descrição        |
|:-------------------|:----------------------------------|:-------------------|
| Documentação  | [Documentação](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security) | Sobre GitHub Advanced Security |
| Documentação  | [Documentação de atualizações de segurança do Dependabot](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/about-dependabot-security-updates) | Sobre atualizações de segurança do Dependabot |
| Documentação  | [Documentação do Copilot Autofix](https://docs.github.com/en/code-security/code-scanning/managing-code-scanning-alerts/about-autofix-for-codeql-code-scanning#autofix-generation-process) | Sobre o Copilot Autofix para varredura de código do CodeQL |
| Certificação  | [Programa de Certificação do GitHub Advanced Security](https://examregistration.github.com/) | Saiba mais sobre as Certificações do GitHub |

## Proprietários do Conteúdo

<!-- ALL-CONTRIBUTORS-LIST:START - Não remova ou modifique esta seção -->

<table>
<tr>
         <td align="center"><a href="http://learnanalytics.microsoft.com">
                  <img src="https://developer.microsoft.com/en-us/advocates/media/profiles/joylynn-kirui.jpg" width="100px;" alt="Chris Testa-O'Neill
"/><br />
                  <sub><b>Joylynn Kirui
</b></sub></a><br />
                                <a href="[https://developer.microsoft.com/advocates/joylynn-kirui]" title="talk">📢</a> 
         </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## IA Responsável

A Microsoft está comprometida em ajudar nossos clientes a usar nossos produtos de IA de forma responsável, compartilhando nossos aprendizados e construindo parcerias baseadas em confiança por meio de ferramentas como Notas de Transparência e Avaliações de Impacto. Muitos desses recursos podem ser encontrados em https://aka.ms/RAI. A abordagem da Microsoft para IA responsável é baseada em nossos princípios de IA de justiça, confiabilidade e segurança, privacidade e segurança, inclusão, transparência e responsabilidade.

Modelos de linguagem natural, imagem e fala em larga escala - como os usados neste exemplo - podem potencialmente se comportar de maneiras injustas, não confiáveis ou ofensivas, causando danos. Consulte a [nota de transparência do serviço Azure OpenAI](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) para se informar sobre riscos e limitações.

A abordagem recomendada para mitigar esses riscos é incluir um sistema de segurança em sua arquitetura que possa detectar e prevenir comportamentos prejudiciais. O [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) fornece uma camada independente de proteção, capaz de detectar conteúdo prejudicial gerado por usuários e IA em aplicativos e serviços. O Azure AI Content Safety inclui APIs de texto e imagem que permitem detectar material prejudicial. Também temos um Content Safety Studio interativo que permite visualizar, explorar e testar códigos de exemplo para detectar conteúdo prejudicial em diferentes modalidades. A seguinte [documentação de início rápido](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) orienta você a fazer solicitações ao serviço.

Outro aspecto a ser considerado é o desempenho geral do aplicativo. Com aplicativos multimodais e multimodelos, consideramos desempenho como o sistema funcionando conforme você e seus usuários esperam, incluindo não gerar saídas prejudiciais. É importante avaliar o desempenho do seu aplicativo geral usando [avaliadores de Desempenho e Qualidade e de Risco e Segurança.](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-metrics-built-in?tabs=warning) Você também tem a capacidade de criar e avaliar com [avaliadores personalizados.](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators)

Você pode avaliar seu aplicativo de IA em seu ambiente de desenvolvimento usando o [SDK de Avaliação do Azure AI.](https://microsoft.github.io/promptflow/index.html) Dado um conjunto de dados de teste ou um alvo, as gerações do seu aplicativo de IA generativa são medidas quantitativamente com avaliadores integrados ou avaliadores personalizados de sua escolha. Para começar a usar o SDK de fluxo de prompt para avaliar seu sistema, você pode seguir o [guia de início rápido.](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk) Depois de executar uma execução de avaliação, você pode [visualizar os resultados no Azure AI Studio.](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results)

## Avisos Legais
 
A Microsoft e quaisquer colaboradores concedem a você uma licença para a documentação da Microsoft e outros conteúdos neste repositório sob a [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
veja [LICENSE](LICENSE) e concedem a você uma licença para qualquer código no repositório sob a  [MIT License](https://opensource.org/licenses/MIT), consulte
[LICENSE-CODE](LICENSE-CODE)
 
Microsoft, Windows, Microsoft Azure e/ou outros produtos e serviços da Microsoft referenciados na documentação podem ser marcas registradas ou marcas registradas da Microsoft nos Estados Unidos e/ou em outros países. As licenças para este projeto não concedem a você direitos de uso de quaisquer nomes, logotipos ou marcas registradas da Microsoft. As diretrizes gerais de marcas registradas da Microsoft podem ser encontradas em http://go.microsoft.com/fwlink/?LinkID=254653.
 
As informações de privacidade podem ser encontradas em https://privacy.microsoft.com/en-us/
 
A Microsoft e quaisquer colaboradores reservam todos os outros direitos, sejam sob seus respectivos direitos autorais, patentes, ou marcas registradas, seja por implicação, estoppel ou de outra forma.


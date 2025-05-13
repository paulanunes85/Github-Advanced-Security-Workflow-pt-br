<h1 align="center">GitHub Advanced Security: Protegiendo su Workflow</h1>
<h5 align="center">Revisión para Español @paulanunes85 - 2025</h5>

Si va a impartir esta sesión, consulte la página de [recursos de entrega de sesión](session-delivery-resources/README.es.md) para diapositivas, scripts de demostración y otros recursos.

## Descripción de la Sesión

Los recursos de GitHub Advanced Security están integrados directamente en el flujo de trabajo de desarrollo, haciéndolos fáciles de usar y dando a los desarrolladores la capacidad de identificar posibles problemas de seguridad lo más temprano posible en el ciclo de vida del desarrollo de software.

Aprenda cómo evitar que problemas de seguridad comunes se fusionen en su código, cómo encontrar y corregir vulnerabilidades más rápidamente con IA y cómo mantener sus dependencias actualizadas a través de GitHub Advanced Security.

- Material [GitHub Advanced Security - Protegiendo su flujo de trabajo](https://github.com/paulanunes85/Github-Advanced-Security-Workflow-pt-br/blob/main/PT-BR_BRK422_Tech%20-%20GitHub%20Advanced%20Security%20-%20Paula%20Silva.pdf)

## Resultados de Aprendizaje

- Aprenda cómo habilitar alertas de Dependabot y recibir notificaciones sobre dependencias vulnerables, incluyendo un enlace al archivo afectado en el proyecto e información sobre una versión corregida.
- Vea cómo actualizar automáticamente o generar una solicitud de extracción para actualizar dependencias vulnerables.
- Descubra cómo actualizar automáticamente paquetes soportados utilizados por su repositorio en una programación que usted configura.
- Aprenda cómo habilitar el escaneo de secretos y la protección de push que previene proactivamente filtraciones de secretos al escanear el código en el commit y bloquear un push si un secreto está presente.
- Encuentre vulnerabilidades antes de que se fusionen al código con escaneos automatizados de CodeQL.
- Aprenda cómo obtener correcciones de código sugeridas por IA en solicitudes de extracción.

## Tecnología Utilizada

        - GitHub Advanced Security
        - Dependabot
        - Escaneo de Secretos
        - CodeQL
        - Copilot Autofix
        - GitHub Actions

## Requisitos Previos

Antes de participar en el taller, hay solo un requisito previo: tener una cuenta pública de GitHub. Todos los recursos, dependencias y datos ya forman parte del repositorio.
- **Requisitos previos:** Para usar GitHub Copilot, debe tener una suscripción activa de GitHub Copilot Business o Enterprise. Inscríbase para Copilot Free para VS Code solo para fines de entrenamiento [Copilot for free para VS Code](https://learn.microsoft.com/es-es/visualstudio/ide/copilot-free-plan?view=vs-2022).
- **Ya tener acceso o Habilitar GitHub Advanced Security:** [Habilitando GitHub Advanced Security](https://resources.github.com/es/learn/pathways/security/essentials/enabling-github-advanced-security/)
- **Tener acceso a una organización GitHub con licencia de GitHub Advanced Security**

## Recursos Adicionales y Aprendizaje Continuo

| Recursos         | Enlaces                           | Descripción        |
|:-----------------|:----------------------------------|:-------------------|
| Documentación    | [Documentación](https://docs.github.com/es/get-started/learning-about-github/about-github-advanced-security) | Sobre GitHub Advanced Security |
| Documentación    | [Documentación de actualizaciones de seguridad de Dependabot](https://docs.github.com/es/code-security/dependabot/dependabot-security-updates/about-dependabot-security-updates) | Sobre actualizaciones de seguridad de Dependabot |
| Documentación    | [Documentación de Copilot Autofix](https://docs.github.com/es/code-security/code-scanning/managing-code-scanning-alerts/about-autofix-for-codeql-code-scanning#autofix-generation-process) | Sobre Copilot Autofix para escaneo de código de CodeQL |
| Certificación    | [Programa de Certificación de GitHub Advanced Security](https://examregistration.github.com/) | Aprenda más sobre las Certificaciones de GitHub |

## Propietarios del Contenido

<!-- ALL-CONTRIBUTORS-LIST:START - No elimine o modifique esta sección -->

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

## IA Responsable

Microsoft está comprometida a ayudar a nuestros clientes a usar nuestros productos de IA de forma responsable, compartiendo nuestros aprendizajes y construyendo asociaciones basadas en la confianza a través de herramientas como Notas de Transparencia y Evaluaciones de Impacto. Muchos de estos recursos se pueden encontrar en https://aka.ms/RAI. El enfoque de Microsoft para IA responsable se basa en nuestros principios de IA de justicia, confiabilidad y seguridad, privacidad y seguridad, inclusión, transparencia y responsabilidad.

Los modelos de lenguaje natural, imagen y habla a gran escala - como los utilizados en este ejemplo - pueden potencialmente comportarse de manera injusta, poco confiable u ofensiva, causando daños. Consulte la [nota de transparencia del servicio Azure OpenAI](https://learn.microsoft.com/es-es/legal/cognitive-services/openai/transparency-note?tabs=text) para informarse sobre riesgos y limitaciones.

El enfoque recomendado para mitigar estos riesgos es incluir un sistema de seguridad en su arquitectura que pueda detectar y prevenir comportamientos perjudiciales. [Azure AI Content Safety](https://learn.microsoft.com/es-es/azure/ai-services/content-safety/overview) proporciona una capa independiente de protección, capaz de detectar contenido dañino generado por usuarios e IA en aplicaciones y servicios. Azure AI Content Safety incluye APIs de texto e imagen que permiten detectar material dañino. También tenemos un Content Safety Studio interactivo que permite visualizar, explorar y probar códigos de ejemplo para detectar contenido dañino en diferentes modalidades. La siguiente [documentación de inicio rápido](https://learn.microsoft.com/es-es/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) lo guía para hacer solicitudes al servicio.

Otro aspecto a considerar es el rendimiento general de la aplicación. Con aplicaciones multimodales y multimodelo, consideramos el rendimiento como el sistema funcionando conforme usted y sus usuarios esperan, incluyendo no generar salidas dañinas. Es importante evaluar el rendimiento de su aplicación general utilizando [evaluadores de Rendimiento y Calidad y de Riesgo y Seguridad.](https://learn.microsoft.com/es-es/azure/ai-studio/concepts/evaluation-metrics-built-in?tabs=warning) También tiene la capacidad de crear y evaluar con [evaluadores personalizados.](https://learn.microsoft.com/es-es/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators)

Puede evaluar su aplicación de IA en su entorno de desarrollo utilizando el [SDK de Evaluación de Azure AI.](https://microsoft.github.io/promptflow/index.html) Dado un conjunto de datos de prueba o un objetivo, las generaciones de su aplicación de IA generativa se miden cuantitativamente con evaluadores integrados o evaluadores personalizados de su elección. Para empezar a usar el SDK de flujo de prompt para evaluar su sistema, puede seguir la [guía de inicio rápido.](https://learn.microsoft.com/es-es/azure/ai-studio/how-to/develop/flow-evaluate-sdk) Después de ejecutar una evaluación, puede [visualizar los resultados en Azure AI Studio.](https://learn.microsoft.com/es-es/azure/ai-studio/how-to/evaluate-flow-results)

## Avisos Legales
 
Microsoft y cualquier colaborador le otorgan una licencia para la documentación de Microsoft y otros contenidos en este repositorio bajo la [Licencia Pública Internacional Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/legalcode),
vea [LICENSE](LICENSE) y le otorgan una licencia para cualquier código en el repositorio bajo la [Licencia MIT](https://opensource.org/licenses/MIT), consulte
[LICENSE-CODE](LICENSE-CODE)
 
Microsoft, Windows, Microsoft Azure y/u otros productos y servicios de Microsoft referenciados en la documentación pueden ser marcas comerciales o marcas registradas de Microsoft en los Estados Unidos y/u otros países. Las licencias para este proyecto no le otorgan derechos para usar ningún nombre, logotipo o marca comercial de Microsoft. Las directrices generales de marcas comerciales de Microsoft se pueden encontrar en http://go.microsoft.com/fwlink/?LinkID=254653.
 
La información de privacidad se puede encontrar en https://privacy.microsoft.com/es-es/
 
Microsoft y cualquier colaborador se reservan todos los demás derechos, ya sea bajo sus respectivos derechos de autor, patentes o marcas comerciales, ya sea por implicación, impedimento legal o de otro modo. 
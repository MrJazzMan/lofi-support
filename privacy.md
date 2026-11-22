---
permalink: /privacy/
---

# Lofi Harbour — Privacidade / Privacy

## Português

### Responsável e contacto

Responsável pela app: **Miguel Garcia**. Contacto de privacidade e suporte: **miguelopesgarcia+lofi@gmail.com**.

Esta informação descreve a app a partir da versão 1.0.2 e indica as diferenças entre versões. Não certifica os direitos de distribuição das emissoras.

### Reprodução e serviços externos

No arranque frio, a app tenta iniciar Lofi automaticamente. Os pedidos de áudio podem começar sem um toque adicional; o regresso do segundo plano não volta a disparar esse arranque.

Os destinos de áudio identificados são `radio.cliamp.stream` para Lofi, `play.streamafrica.net` e `boxradio-edge-00.streamafrica.net` para Box Radio, `public.isekoi-radio.com` para ISEKOI Radio e `play.radioregional.pt:8220` para Cascais FM. Na versão 1.0.2, a app também pede a lista de faixas de Lofi a `radio.cliamp.stream`; a partir da 1.0.3, toca apenas a emissão em direto. Os operadores recebem o endereço IP e informação técnica dos pedidos, podendo relacionar pedidos e horários com o conteúdo solicitado. Não dispomos de confirmação dos respetivos prazos de conservação, finalidades adicionais ou transferências internacionais. Não se deve presumir que o IP nunca é guardado.

A função de verificação de atualizações utiliza o serviço iTunes Lookup da Apple. Abrir a ficha da App Store também comunica com a Apple. Os serviços externos aplicam as suas próprias práticas de privacidade, distintas da informação que o responsável pela app recebe.

### Informação no dispositivo e diagnósticos

Preferências de equalizador, idioma, tema, visualizador e efeitos são guardadas localmente. Podem incluir nomes de presets introduzidos pelo utilizador e curvas por estação. Há processamento e armazenamento temporário de áudio em memória para reprodução; a app não oferece gravação ou escuta offline.

Estas preferências não são enviadas para o responsável. A única informação que a app envia ao servidor do responsável são as métricas de utilização descritas abaixo, a partir da versão 1.0.4. Existem registos locais do sistema sobre reprodução, erros, HTTP e componentes de caminhos de URL; não foi identificado envio automático destes registos no código auditado. O sistema operativo pode gerir e partilhar diagnósticos segundo as suas definições e termos. Estas observações não equivalem a uma garantia global de ausência de recolha ou rastreamento por todos os serviços externos.

### Métricas anónimas de utilização

A partir da versão 1.0.4, a app guarda no dispositivo contadores por dia (minutos e reproduções por rádio, definições em uso e alguns eventos). Cada envio para `metrics.miguelg.dev` inclui também o dia, a versão da app e o tipo de plataforma (iOS, iPadOS ou macOS). Os contadores não incluem identificadores, nada mais fino do que o dia nem texto livre, e não são ligados à sua identidade. O servidor, alojado na Cloudflare, recebe o endereço IP necessário à ligação; não guardamos o endereço IP com estes contadores. Servem apenas para perceber o que os ouvintes mais usam (análise) e não são usados para rastreamento. As versões de desenvolvimento não enviam nada.

**Versão 1.0.4:** cada dia terminado é enviado automaticamente, e esta versão não tem opção para desligar o envio.

**Versão 1.0.5 e seguintes:** nada é enviado até responder à pergunta apresentada na quinta abertura da app ou usar a opção **Partilhar estatísticas de uso** nas Definições. Até lá, os dias terminados ficam apenas no dispositivo, no máximo durante uma semana. Se escolher partilhar, esses dias são enviados. Se escolher não partilhar, ou desligar a opção mais tarde, a app deixa de contar e de enviar e apaga o que ainda não foi enviado. Pode mudar a escolha nas Definições em qualquer momento.

### Contacto, conservação e direitos

Se contactar o suporte, a mensagem e a informação que enviar serão disponibilizadas ao responsável através do serviço de email usado no contacto. Esse contacto utiliza Gmail; o serviço de email tem os seus próprios termos e práticas. Não envie dados sensíveis ou gravações de áudio.

Pode usar o contacto acima para pedir informação sobre o tratamento de dados, conservação e os direitos aplicáveis, incluindo acesso, retificação ou apagamento quando o responsável detenha dados pessoais seus. Não se promete que o responsável possa apagar registos mantidos pelos operadores de rádio ou pela Apple. Os prazos de conservação dos servidores externos não foram confirmados.

### Alojamento destas páginas

A opção de alojamento prevista é GitHub Pages. Segundo a documentação do GitHub, este serviço regista e conserva endereços IP de visitantes por motivos de segurança. Trata-se do alojamento do site, separado das ligações de áudio da app. Esta informação não constitui uma declaração de que nenhum dado é recolhido.

## English

### Responsible party and contact

App responsible party: **Miguel Garcia**. Privacy and support contact: **miguelopesgarcia+lofi@gmail.com**.

This information describes the app from version 1.0.2 onwards and notes the differences between versions. It does not certify the broadcasters’ distribution rights.

### Playback and external services

On a cold launch, the app attempts to start Lofi automatically. Audio requests may begin without an additional tap; returning from the background does not trigger this startup again.

The identified audio destinations are `radio.cliamp.stream` for Lofi, `play.streamafrica.net` and `boxradio-edge-00.streamafrica.net` for Box Radio, `public.isekoi-radio.com` for ISEKOI Radio and `play.radioregional.pt:8220` for Cascais FM. Version 1.0.2 also requests the Lofi track list from `radio.cliamp.stream`; from 1.0.3 onwards the app plays the live stream only. Operators receive the IP address and technical request information and may associate requests and times with requested content. Their retention periods, additional purposes and international transfers have not been confirmed. IP addresses must not be assumed never to be stored.

The update-check function uses Apple’s iTunes Lookup service. Opening the App Store listing also communicates with Apple. External services apply their own privacy practices, distinct from information received by the app’s responsible party.

### On-device information and diagnostics

Equaliser, language, theme, visualiser and effects preferences are stored locally. These may include user-entered preset names and per-station curves. Audio is processed and temporarily buffered in memory for playback; the app does not offer recording or offline listening.

These preferences are not sent to the responsible party. The only information the app sends to the responsible party's server is the usage metrics described below, from version 1.0.4 onwards. Local system logs include playback state, errors, HTTP and URL path components; automatic upload of these logs was not identified in the audited code. The operating system may manage and share diagnostics according to its settings and terms. These observations are not an app-wide guarantee of no collection or tracking by all external services.

### Anonymous usage metrics

From version 1.0.4, the app keeps per-day counts on the device (minutes and plays per station, settings in use and a few events). Each submission to `metrics.miguelg.dev` also includes the day, the app version and the platform type (iOS, iPadOS or macOS). The counts contain no identifiers, nothing finer than the day and no free text, and are not linked to your identity. The server, hosted on Cloudflare, receives the IP address needed for the connection; we do not store the IP address with these counts. They are used only to understand what listeners use most (analytics) and not for tracking. Development builds send nothing.

**Version 1.0.4:** each finished day is sent automatically, and this version has no option to turn sending off.

**Version 1.0.5 and later:** nothing is sent until you answer the question shown on the fifth time you open the app or use the **Share usage statistics** option in Settings. Until then, finished days stay only on the device, for at most one week. If you choose to share, those days are sent. If you choose not to share, or turn the option off later, the app stops counting and sending and deletes anything not yet sent. You can change your choice in Settings at any time.

### Contact, retention and rights

If you contact support, your message and the information you send will be made available to the responsible party through the email service used by the contact. This contact uses Gmail, which has its own terms and practices. Do not send sensitive information or audio recordings.

Use the contact above to ask about processing, retention and applicable rights, including access, correction or deletion where the responsible party holds your personal information. No promise is made that the responsible party can delete records held by radio operators or Apple. External servers’ retention periods have not been confirmed.

### Hosting these pages

The proposed host is GitHub Pages. According to GitHub’s documentation, that service logs and retains visitors’ IP addresses for security purposes. This website-hosting processing is separate from the app’s audio connections. This information is not a declaration that no data is collected.

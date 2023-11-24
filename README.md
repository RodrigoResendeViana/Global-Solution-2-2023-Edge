<h1>GS2 2023 - Toten para hospitais</h1>

<h2>Problema</h2>

Nosso problema em questão foram as filas e o tempo de espera para atendimento em hospitais. Nosso objetivo é implementar nossa solução para atender mais pessoas do que conseguiríamos sem a nossa aplicação.


<h2>Solução</h2>

Tendo isso em vista, criamos uma aplicação que tem como diferencial um pré-diagnóstico realizado por IA. Nossa ideia era pegar as informações desse pré-diagnóstico e mandar para uma nuvem, com essas informações linkadas as CPF do paciente. Ao chegar no hospital, você coloca seu CPF no toten específico, e assim, ele busca pelo CPF as informações na nuvem, puxa da nuvem e envia para o sistema do médico no hospital. Nesse protótipo, tentamos fazer essa implementação usando o keypad para inserir o CPF, e quando finalizassemos, enviaríamos o CPF inserido para um arquivo JSON, como representação da nuvem, apenas para testes


<h2>Como reproduzir</h2>
    <li>Baixar as devidas bibliotecas
    <li>Fazer as configurações do MQTT, preparando as constantes para conectar com seu servidor
    <li>Preparar as variáveis (Keypad, principalmente)
    <li>Iniciar a conexão com o Broker
    <li>Implementar o código para pegar o CPF digitado no keypad e enviar para o servidor MQTT
<h3>Caso fizessemos a implementação completa</h3>
    <li>Conectar a aplicação com a nuvem(assim, as informações do pré-diagnóstico ficariam na nuvem, ligada a um CPF específico)
    <li>No toten realizar os passos acima
    <li>Linkar o toten à nuvem
    <li>Linkar o toten com a aplicação do médico para envio das informações captadas na nuvem


<h2>Link</h2>

Segue link para projeto:<br>

https://wokwi.com/projects/382226004640500737<br>

Projeto incompleto, mas com as devidas partes

<h2> Integrantes </h2>

Caique Chargas - RM551943<br>
Rodrigo Resende - RM551057<br>


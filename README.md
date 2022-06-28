# salesforce-zap-challenge-apex
Componente Consulta CEP.
Ao entrar no salesforce e ir ao objeto Conta temos um botão "Consultar CEP" onde ao clicar abre um modal com informações de endereço,
como por exemplo CEP, Rua, Bairro, Estado. Assim que o usuário digitar seu CEP e clicar no ícone de pesquisa (Lupa) será 
feita a consulta e adicionado nos respectivos campos e ao clicar no botão salvar é adicionado na guia Detalhes
em Endereço de Cobrança.
Foi criado um ambiente novo em Salesforce para o desenvolvimento.
Em seguida entrando no developer console foi criado um componente cujo nome ConsultaCep.
Para este componente foi criado uma controller.JS para a integração com o componente.
Feito isso foi criado um botão dentro do Salesforce para o Objeto conta com o nome "Consultar CEP".
Feito ajustes no layout do componente.
Feita a consulta no formato de Json pelo ViaCep, criado a classe ViaCepJson.
Criado a classe controller, ConsultaCepController para ter a integração com o front-end.
Criado a classe de teste da controller, ConsultaCepControllerTeste.
Recurso Estático ViaCepJson e a Estrutura do Json.

Documentações Salesforce utilizadas:
https://developer.salesforce.com/docs/component-library/bundle/force:hasRecordId/documentation
https://developer.salesforce.com/docs/component-library/bundle/aura:valueInit/documentation
https://developer.salesforce.com/docs/component-library/bundle/force:showToast/documentation
https://www.lightningdesignsystem.com/components/modals/
https://developer.salesforce.com/docs/component-library/bundle/lightning:layout/example
https://developer.salesforce.com/docs/component-library/bundle/lightning:input/example#lightningcomponentdemo:exampleInputText
https://www.lightningdesignsystem.com/icons/#utility
https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_class_System_Json.htm
https://developer.salesforce.com/docs/atlas.en-us.object_reference.meta/object_reference/compound_fields_address.htm
https://trailhead.salesforce.com/en/content/learn/modules/apex_integration_services/apex_integration_rest_callouts
https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/controllers_server_apex_auraenabled_annotation.htm







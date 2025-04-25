# Guia para Abertura de Chamados no GLPI para FGRZap

Guia para o processo de abrir chamados no GLPI relacionados ao FGRZap.

## Passo a Passo

1. **Acesse o GLPI**
   
3. **Categoria de abertura de chamado**:
   - **TI** > **Desenvolvimento de Sistemas** > **FGRZap**.

4. **Selecione a Opção Desejada**:
   - Escolha a opção **Outros**.

5. **Preencha a Descrição do Chamado**:
   - No campo **Descrição**, inclua:
     - O **template da mensagem padrão** que será usado no WhatsApp.
     - Utilize **{1}**, **{2}**, etc., para indicar as partes da mensagem que mudam.
     - Exemplo: "Olá, cliente {1}! sua solicitação {2} foi processada com sucesso."
     - Exemplo:
      ```md
      Olá, Cliente Jardins {1}!
      Tudo bem?

      Confira o último {2} do seu Empreendimento, clicando no botão abaixo.

      Att.: Equipe de Relacionamento - FGR Incorporações
      ```

- Para dúvidas adicionais, contate a equipe de desenvolvimento.

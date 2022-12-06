# Teste para candidatos à vaga de frontend na Supersonic

De antemão já agradecemos pelo seu tempo e intenção de trabalhar conosco, temos certeza que grandes frutos vão surgir dessa parceria!

## Descrição
- O teste consiste na conversão de um layout feito no [Figma](https://www.figma.com/file/LDTaoFR7mk2bZ2FxCIKalm/Supersonic-teste-para-frontend?node-id=40%3A262) para web
- Damos o prazo inicial de 7 dias para a entrega do teste, mas se precisar de mais tempo, basta comunicar
- As tecnologias utilizadas na conversão não terão tanto peso quanto o bom uso delas, ou seja, sinta-se livre pra utilizar as bibliotecas e/ou frameworks que se sentir mais confortável desde que possamos replicá-las localmente sem dificuldade
- Projeto versionado em git e publicado no Github
- Instruções para instalação no readme.md
## Ganhe pontos extras por:

- Atingir boas notas nas métricas do Lighthouse
- Aplicar o Design System do layout de maneira eficiente e escalável
- Aplicar boas práticas de UX e acessibilidade na validação do form e na navegação da página no geral
- Integrar o formulário com a API da hubspot
- Buscar os posts de blog mais recentes pela API do WordPress da Supersonic

## Materiais de apoio

- Link do projeto no figma:  https://www.figma.com/file/LDTaoFR7mk2bZ2FxCIKalm/Supersonic-teste-para-frontend?node-id=0%3A1
- URL da API do WordPress da Supersonic: [https://www.supersonic.ag/wp-json/wp/v2/](https://www.supersonic.ag/wp-json/wp/v2/)
- Informações do formulário da Hubspot:
    
    ```json
    {
      "portalId": "23289049",
      "formId": "74eb6839-1f8e-45ea-9c20-2b0c038a4829"
    }
    ```
    
    campos do formulário:
    
    ```json
    {
      "fields": [
        {
          "objectTypeId": "0-1",
          "name": "email",
          "value": ""
        },
        {
        "objectTypeId": "0-1",
          "name": "firstname",
          "value": ""
        },
        {
          "objectTypeId": "0-1",
          "name": "phone",
          "value": ""
        }
      ],
      "legalConsentOptions": {
        "consent": {
          "consentToProcess": true,
          "text": "",
          "communications": [
            {
              "value": true,
              "subscriptionTypeId": 999,
              "text": "Li e concordo com os termos de uso."
            }
          ]
        }
      }
    }
    ```

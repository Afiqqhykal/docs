---
title: Solicitar una verificación de publicador para tu organización
intro: 'Para ofrecer planes de pago para tu app o para incluir una insgnia de marketplace en el listado de tu app, debes completar el proceso de verificación de publicador para tu organización.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Marketplace
redirect_from:
  - /developers/github-marketplace/applying-for-publisher-verification-for-your-organization
shortTitle: Verificación del publicador
---

La verificación del publicador garantiza que {% data variables.product.prodname_dotcom %} tiene una forma de contactarte, que habilitas la autenticación bifactorial para tu organización y que el dominio de tu organización se verificó.

Una vez que se haya verificado tu organización, podrás publicar planes de pago para tu app. Para obtener más información, consulta la sección "[Configurar los planes de pago para tu listado](/developers/github-marketplace/setting-pricing-plans-for-your-listing)".

Para ofrecer planes de pago para tu app, esta debe pertenecer a una organización y debes tener permisos de propietario en ella. If your app is currently owned by a personal account, you'll need to transfer the ownership of the app to an organization. Para obtener más información, consulta la sección "[Transferir la propiedad de una GitHub App](/developers/apps/transferring-ownership-of-a-github-app)" o "[Transferir la propiedad de una App de OAuth](/developers/apps/transferring-ownership-of-an-oauth-app)".

## Solicitar la verificación de publicador


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
1. En la barra lateral izquierda, haz clic en **Developer settings** (Parámetros del desarrollador). ![La opción de configuración de desarrollador en la barra lateral de ajustes de la organización](/assets/images/marketplace/developer-settings-in-org-settings.png)
1. Debajo de "Ajustes de desarrollador", da clic en **Verificación del publicador**. ![Opción de verificación del publicador en la barra lateral de ajustes de la organización](/assets/images/marketplace/publisher-verification-settings-option.png)
1. Debajo de "Verificación del publicador", completa la información de la lista de verificación:
   - Asegúrate de que tu información de perfil básica está presente y es correcta. También, asegúrate de que hayas incluido la mejor dirección de correo electrónico para recibir soporte y actualizaciones de {% data variables.product.company_short %}.
   - Asegúrate de que se encuentre habilitada la autenticación bifactorial para tu organización. Para obtener más información, consulta "[Solicitar la autenticación de dos factores en tu organización](/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization)".
   - Emite un dominio verificado y asegúrate que se muestre la insignia de "Verificado" en el perfil de página de tu organización. Para obtener información relacionada, consulta la sección "[Verificar o aprobar un dominio para tu organización](/organizations/managing-organization-settings/verifying-or-approving-a-domain-for-your-organization)".

  ![Lista de verificación para la verificación del publicador](/assets/images/marketplace/publisher-verification-checklist.png)

2. Da clic en **Solicitar verificación**. {% data variables.product.company_short %} revisará tus detalles y te avisará cuando se haya completado tu verificación de publicador.

## Leer más

Para obtener más información sobre el proceso de publicación de apps, consulta la sección "[Acerca de GitHub Marketplace](/developers/github-marketplace/about-github-marketplace)".

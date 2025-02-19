---
title: Candidatar-se à verificação de publicador para a sua organização
intro: 'Para oferecer planos pagos para seu aplicativo ou para incluir um selo no Marketplace no anúncio do seu aplicativo, você deverá concluir o processo de verificação de publicação para a sua organização.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Marketplace
redirect_from:
  - /developers/github-marketplace/applying-for-publisher-verification-for-your-organization
shortTitle: Verificação do editor
---

A verificação do editor garante que {% data variables.product.prodname_dotcom %} tem uma forma de entrar em contato com você, que você habilitou a autenticação de dois fatores para a sua organização e que o domínio da sua organização foi verificado.

Assim que sua organização for verificada, você poderá publicar planos pagos para o seu aplicativo. Para obter informações, consulte "[Configurar planos de preços para o seu anúncio](/developers/github-marketplace/setting-pricing-plans-for-your-listing)".

Para oferecer planos pagos para o seu aplicativo, este deverá pertencer a uma organização e você deverá ter permissões de proprietário na organização. If your app is currently owned by a personal account, you'll need to transfer the ownership of the app to an organization. Para obter mais informações, consulte "[Transferir a propriedade de um aplicativo GitHub](/developers/apps/transferring-ownership-of-a-github-app)" ou "[Transferir a propriedade de um aplicativo OAuth](/developers/apps/transferring-ownership-of-an-oauth-app)".

## Solicitar verificação de publicador


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
1. Na barra lateral esquerda, clique em **Developer settings** (Configurações do desenvolvedor). ![Opção de configurações do desenvolvedor na barra lateral de configurações da organização](/assets/images/marketplace/developer-settings-in-org-settings.png)
1. Em "Configurações de desenvolvedor", clique em **Verificação do publicador**. ![Opção de verificação do editor na barra lateral de configurações da organização](/assets/images/marketplace/publisher-verification-settings-option.png)
1. Em "Verificação do Publicador, preencha as informações na lista de verificação:
   - Certifique-se de que as suas informações básicas do perfil estejam presentes e precisas. Além disso, certifique-se de incluir o melhor endereço de e-mail para suporte e atualizações de {% data variables.product.company_short %}.
   - Certifique-se de que a autenticação de dois fatores esteja habilitada para a sua organização. Para obter mais informações, consulte "[Exigir autenticação de dois fatores em sua organização](/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization)".
   - Envie um domínio verificado e certifique-se de que um selo "Verificado" seja exibido na página de perfil da sua organização. Para informações relacionadas, consulte "[verificar ou aprovar um domínio para sua organização](/organizations/managing-organization-settings/verifying-or-approving-a-domain-for-your-organization)".

  ![Lista de verificação do publicador](/assets/images/marketplace/publisher-verification-checklist.png)

2. Clique **Solicitar verificação**. {% data variables.product.company_short %} analisará as suas informações e informará assim que a verificação de publicação for concluída.

## Leia mais

Para obter informações sobre o processo de publicação de aplicativos, consulte "[Sobre o GitHub Marketplace](/developers/github-marketplace/about-github-marketplace)".

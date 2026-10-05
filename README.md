# LVM Weightlifting Support

Site estático de suporte e privacidade para o app LVM Weightlifting, pronto para publicação no GitHub Pages.

## Antes de publicar

1. Substitua `SEU_EMAIL_DE_SUPORTE` em `index.html` e `privacidade.html` pelo e-mail real de atendimento.
2. Preencha todos os campos entre colchetes em `privacidade.html`. A política precisa descrever as práticas reais do app, inclusive dados coletados por SDKs e serviços integrados.
3. Atualize a data da política e revise o conteúdo e os links de contato.
4. Envie as alterações para a branch `main` do repositório no GitHub.

## Ativar o GitHub Pages

O workflow em `.github/workflows/pages.yml` publica o conteúdo da branch `main` automaticamente. No GitHub, abra **Settings > Pages** e selecione **GitHub Actions** como fonte de publicação. Após a conclusão do workflow, as URLs serão:

- Suporte: `https://SEU_USUARIO.github.io/SEU_REPOSITORIO/`
- Privacidade: `https://SEU_USUARIO.github.io/SEU_REPOSITORIO/privacidade.html`

Use a primeira URL como Support URL e a segunda como Privacy Policy URL nos metadados do app. Se o repositório for `SEU_USUARIO.github.io`, o endereço não inclui o nome do repositório.
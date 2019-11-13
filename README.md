To deploy to your Netlify account, hit the button below.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/TryGhost/gatsby-starter-ghost)

Content API Keys are generally not considered to be sensitive information, they exist so that they can be changed in the event of abuse; so most people commit it directly to their `.ghost.json` config file. If you prefer to keep this information out of your repository you can remove this config and set [Netlify ENV variables](https://www.netlify.com/docs/continuous-deployment/#build-environment-variables) for production builds instead.

Once deployed, you can set up a [Ghost + Netlify Integration](https://docs.ghost.org/integrations/netlify/) to use deploy hooks from Ghost to trigger Netlify rebuilds. That way, any time data changes in Ghost, your site will rebuild on Netlify.

# Copyright & License

Copyright (c) 2013-2019 Ghost Foundation - Released under the [MIT license](LICENSE).
---
title: "EasySelfHost"
layout: "elements"
description: "EasySelfHost"
draft: false
---

Check out EasySelfHost, a hosting platform with one-click apps, deployments from Github via automated CI/CD pipelines and more!
EasySelfHost is based on the popular open-source project CapRover, but includes advanced monitoring, persistent volumes which are shared in the cluster, backups, snapshots and way more!

- **CI/CD pipeline**: Just paste in your Github repo link, and it will automatically deploy the newest version of your app on every push!
    - **CLI Deployment**: Deploy using the CLI without writing any Dockerfiles or specifications
    - **Git Deployment**: Specify the Github repo, create a Github secret, and automatically build and deploy your application on every push!
- **Let's encrypt SSL built in**: No need to worry about SSL certificates, EasySelfHost will automatically create and renew them for you!
- **prod/staging/dev stages**: Create a Github branch "main" for your productive app, and a branch "staging" for the "test"-app and test changes live before deploying them to prod!
- **persistent volumes**: Your data is stored in a persistent volume. EasySelfHost allows you to take snapshots of your data and restore them later (only included in the advanced plan)
- **one-click apps**: deploy ready-made apps in seconds without worrying about the setup. select one from the app-catalog and deploy!
- **managed databases**: you do not want to worry about selfhosted databases? just book one in addition to your EasySelfHost subscription
- **CLI deployments**: you are not using Github? No problem, just deploy your app from the console!
- **Monitoring**: Built in monitoring and request tracking to prevent and analyse errors and downtimes.

{{< button label="Contact us for a free 7 day trial!" link="/contact">}}

{{< button label="Pricing" link="/easyselfhost-pricing">}}


## live demo (reduced features)

*password:* captain42

<iframe style="width:100%; height:800px" src="https://captain.server.demo.caprover.com/"></iframe>
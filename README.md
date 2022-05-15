## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn
```

## Deploy to AWS

Set your AWS Access Key and Secret Access Key on the ```.env``` file:

```
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
```

Run:

```bash
yarn run deploy
# or to remove:
yarn run remove
```

If the deployment was completed successfully you will get the CloudFront url on your terminal.

## Learn More

To learn more about Serverless Next.js, take a look at the following resources:

- [Serverless Next.js plugin](https://www.serverless.com/plugins/serverless-nextjs-plugin)
- [Deploying Next.js to AWS using Serverless Next.js](https://blog.logrocket.com/deploying-nextjs-aws-serverless-next-js/)
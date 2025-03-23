# Crapriconio Business Group S.A web project

## How to run this site

In order to run this site first you need [Node.js](https://nodejs.org/en/download) installed in your device.

After that, you can run the following commands:

```bash
npm install # To install all the node dependencies

npm run start # Using this command executes all the other commands to build the project and runs the site locally
```

Then you can check your site up and running in [localhost:3000](https://http://localhost:3000) or [localhost:4000](https://http://localhost:4000).


### As an additional note

Everytime after you've run the `npm run start` command, it's applying and building the original template and publishing it into the `dist` directory. In order to avoid any information loss, please we strongly advice to keep all your changes in `dev/index.html` and copy-paste its contents over the `dist/index.html` after every `npm run start` execution.

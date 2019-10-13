<p align="center"><img src="images/squared-serverless-logo-small.png" height="150" alt="Seagull with a French Fry"><a href="#disclaimer">*</a></p>
<h1 align="center">Serverless Toolkit</h1>
<p align="center"><a href="https://github.com/twilio-labs/about"><img src="https://img.shields.io/static/v1?label=&message=Twilio-Labs&color=F22F46&labelColor=0D122B&logo=twilio&style=for-the-badge" alt="Part of Twilio Labs Banner"></a></p>

## What is the Serverless Toolkit?

The [Serverless Toolkit](https://www.twilio.com/docs/labs/serverless-toolkit) is CLI tooling to help you develop locally and deploy to the [Twilio Runtime](https://www.twilio.com/runtime).

There are two ways you can use the toolkit. If you are already using the [Twilio CLI](https://www.twilio.com/docs/twilio-cli), you can install it via a plugin. Alternatively, you can use the toolkit as a standalone using [twilio-run](https://npm.im/twilio-run) via npm or another Node.js package manager.

Throughout the [docs](https://www.twilio.com/docs/labs/serverless-toolkit), you can switch in the code snippets between Twilio-CLI and Bash Session to get the commands for both versions.

## Let's work together

Everything in this toolkit is released under [Twilio Labs](https://www.twilio.com/docs/labs) and fully open-source. If you find any problems with this, [please file an issue](https://github.com/twilio-labs/serverless-toolkit/issues) or even create a pull request to work together with us on the toolkit. We would love to hear your ideas and feedback!

## Project Structure & Contributing

The project is broken down into a variety of repositories. If you just want to [file an issue](https://github.com/twilio-labs/serverless-toolkit/issues) feel free to file it under this project if you don't know where it belongs. For pull requests, please check out the right project and check out their respective contributing guides.

To understand more about the structure and the design of the Toolkit check out the [design documentation](DESIGN.md).

- [`twilio-run`](https://github.com/twilio-labs/twilio-run) - The underlying CLI tool
- [`plugin-serverless`](https://github.com/twilio-labs/plugin-serverless) - Exposes the `twilio-run` CLI into the [Twilio CLI](https://www.twilio.com/docs/twilio-cli)
- [`create-twilio-function`](https://github.com/twilio-labs/create-twilio-function) - Handles templating and bootstrapping of new projects and Functions
- [`serverless-api`](https://github.com/twilio-labs/serverless-api) - The module used to interact with the actual [Serverless API](https://github.com/twilio-labs/serverless-api)
- [`function-templates`](https://github.com/twilio-labs/function-templates) - The templates used by the toolkit to create new Functions

## License [![GitHub license](https://img.shields.io/github/license/twilio-labs/serverless-toolkit)](https://github.com/twilio-labs/serverless-toolkit/blob/master/LICENSE)

MIT

## Disclaimer

Unofficial logo. Not a Twilio logo.

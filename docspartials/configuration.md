# Configuration
The authoring tool has been built to allow for multiple configurations for different system environments (e.g. testing, production, development).

## Quick reference
See below for an overview of all available configuration options.

{{{REPLACE_ME}}}

## Set up your environment

To configure your tool for a specific environment, you must create a config file in `/conf` named according to the env value your system will be using (e.g. `dev.config.js`, `production.config.js`, `helloworld.config.js`). We recommend sticking to something short like `dev`, `prod`, and `test`, but it's up to you what you name these; just make sure to set the environment variable to the same.

*The `NODE_ENV` environment variable is used to determine the current environment, so make sure that this is set appropriately when running the application:*

**Bash**:
```bash
$ NODE_ENV=dev adaptat start
```
**Powershell**:
```bash
> set NODE_ENV=dev && adaptat start
```
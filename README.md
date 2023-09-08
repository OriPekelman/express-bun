# Express on Bun 1.0 for Platform.sh

<p align="center">
<a href="https://console.platform.sh/projects/create-project?template=https://gist.githubusercontent.com/OriPekelman/1b19f464756919e0b26937092fb1eda1/raw/a58af40e77cad4d268f4bf56b99008e2e02ad7b9/template.yaml&utm_content=express_bun&utm_source=github&utm_medium=button&utm_campaign=deploy_on_platform">
    <img src="https://platform.sh/images/deploy/lg-blue.svg" alt="Deploy on Platform.sh" width="180px" />
</a>
</p>

This template demonstrates building the Express framework for Platform.sh.  It includes a minimalist application skeleton that demonstrates how to connect to a MariaDB server.  It is intended for you to use as a starting point and modify for your own needs.

Express is a minimalist web framework written in Node.js.

## Features

* Bun 1.0
* MariaDB 10.4
* Automatic TLS certificates
* npm-based build

## Customizations

The following files and additions make the framework work.  If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added.  These provide Platform.sh-specific configuration and are present in all projects on Platform.sh.  You may customize them as you see fit.
* An additional module, [`config-reader-nodejs`](https://github.com/platformsh/config-reader-nodejs), has been added.  It provides convenience wrappers for accessing the Platform.sh environment variables.

## References

* [Express](https://expressjs.com/)
* [Node.js on Platform.sh](https://docs.platform.sh/languages/nodejs.html)

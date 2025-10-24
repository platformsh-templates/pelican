> [!WARNING]
> **This repository is no longer maintained by our internal teams.**  
> The template is provided *as is* and will not receive updates, bug fixes, or new features.  
> You are welcome to contribute on it or fork the repository and modify it for your own use.
> To deploy this template on [Upsun](https://www.upsun.com), you can use the command [upsun project:convert](https://docs.upsun.com/administration/cli/reference.html#projectconvert)
> on this codebase to convert the existing `.platform.app.yaml` configuration file to the [Upsun Flex format](https://docs.upsun.com/create-apps/app-reference/single-runtime-image.html).

# Pelican for Platform.sh

This template provides a basic Pelican skeleton.  Only content files need to be committed, as Pelican itself is downloaded at build time via the Pipfile.  All files are generated at build time, so at runtime only static files need to be served.

Pelican is a static site generator written in Python and using Jinja for templating.

## Features

* Python 3.8
* Automatic TLS certificates
* Pipfile-based build

## Customizations

The following changes have been made relative to a plain Pelican project.  If using this project as a reference for your own existing project, replicate the changes below to your project.

* The `.platform.app.yaml`, `.platform/services.yaml`, and `.platform/routes.yaml` files have been added.  These provide Platform.sh-specific configuration and are present in all projects on Platform.sh.  You may customize them as you see fit.

## References

* [Pelican](https://getpelican.com/)
* [Python on Platform.sh](https://docs.platform.sh/languages/python.html)

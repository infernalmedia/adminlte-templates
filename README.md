<h1 align="center"><img src="https://assets.infyom.com/open-source/infyom-logo.png" alt="InfyOm"></h1>

# AdminLTE Templates for InfyOm Laravel Generator

Templates for [AdminLTE Theme](https://adminlte.io/) for InfyOm Laravel Generator.  

## Documentation

Read [Documentation](https://infyom.com/open-source/laravelgenerator/docs/8.0/adminlte-templates) for detailed installation steps and usage.

## Inclusion in IM projects

Add this entry in `composer.json` :

```
"repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:infernalmedia/adminlte-templates.git"
        }
    ],
```

Run `composer require infyomlabs/adminlte-templates:dev-develop`

Make sure to have `<x-page-header>` component from [this repo](https://gitlab.com/infernalmedia/infernal-components)

Enjoy !

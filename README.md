# Renovate configuration for oapi-codegen

This repository contains [Shareable Config Presets](https://docs.renovatebot.com/config-presets/) for [Renovate](https://docs.renovatebot.com/) usage across [`oapi-codegen`](https://github.com/oapi-codegen/oapi-codegen) and its related projects.

## `user.json`

For use by `oapi-codegen` users, and can be used like so:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>oapi-codegen/renovate-config:user"
  ]
}
```

Provides utilities to:

- Keep JSON schema references (in `yaml-language-server` comments) updated alongside the version of `oapi-codegen`

## `default.json`

> [!NOTE]
> It is not intended for usage outside of `oapi-codegen`.

This configuration is used across all repositories in the `oapi-codegen` org.

# Lura Installer Template

A Installer Template for [Lura](https://github.com/Muetze42/lura).

## Development

### Set up the `composer.json` file.

```json
{
    "name": "vendor/my-lura-installer"
}
```

### Don't forget to register the installer after install

```shell
lura register vendor/my-lura-installer
```

### Installer command

Use the `lura/Installer.php`. No Namespace, no autoload!.

| Method                  |                           |
|-------------------------|---------------------------|
| runLura(mixed $command) | The running command.      |

runLura: You have the functionality of a [Laravel command](https://laravel.com/docs/artisan) except Input Expectations

### Optional: Configuration

Add configuration to the `config/lura-config.json`

[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine/)

[![Woman. Life. Freedom.](https://raw.githubusercontent.com/Muetze42/Muetze42/2033b219c6cce0cb656c34da5246434c27919bcd/files/iran-banner-big.svg)](https://linktr.ee/CurrentPetitionsFreeIran)

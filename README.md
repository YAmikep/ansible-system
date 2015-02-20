# ansible-system

Manages system wide settings (locale, packages)


## Usage

```yaml
{
    role: system,
    system_packages: ["git"],
    system_locale: "en_US.UTF-8",
}
```

See default variables in ```defaults``` directory.

Run ansible with ```--extra-vars="playbook_debug=yes"``` to debug.
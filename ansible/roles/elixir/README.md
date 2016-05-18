# Ansible role: Elixir (+ Erlang)

## Updating Erlang or Elixir

By default, this role will only ensure that the Erlang package is `present`. To update Erlang:

```yaml
vars:
    elixir_erlang_package_state: latest
```

## Selecting Elixir version

Set a specific Elixir version with:

```yaml
vars:
    elixir_version: 1.2.4
```
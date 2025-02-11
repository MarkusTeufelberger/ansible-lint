(lint-documentation)=

# Ansible Lint Documentation

## About Ansible Lint

Ansible Lint is a command-line tool for linting **playbooks, roles and
collections** aimed towards any Ansible users. Its main goal is to promote
proven practices, patterns and behaviors while avoiding common pitfalls that
can easily lead to bugs or make code harder to maintain.

Ansible lint is also supposed to help users upgrade their code to work with
newer versions of Ansible. Due to this reason we recommend using it with
the newest version of Ansible, even if the version used in production may be
older.

As any other linter, it is opinionated. Still, its rules are the result of
community contributions and they can always be disabled based individually or
by category by each user.

[Ansible Galaxy project](https://github.com/ansible/galaxy/) makes use of
this linter in order to compute quality scores for [Galaxy Hub](https://galaxy.ansible.com)
contributed content. This does not mean this tool is aimed only to those
that want to share their code. Files like `galaxy.yml`, or sections like
`galaxy_info` inside `meta.yml` help with documentation and maintenance,
even for unpublished roles or collections.

The project was originally started by [@willthames](https://github.com/willthames/),
and has since been adopted by the Ansible Community team. Its development is
purely community driven, while keeping permanent communications with other
Ansible teams.

```{toctree}
:caption: Philosophy
:maxdepth: 3

philosophy
```

```{toctree}
:caption: Installing
:maxdepth: 3

installing
```

```{toctree}
:caption: Usage
:maxdepth: 3

usage
```

```{toctree}
:caption: Configuring
:maxdepth: 3

configuring
```

```{toctree}
:caption: Profiles
:maxdepth: 2

profiles
```

```{toctree}
:caption: Rules
:maxdepth: 4

rules
custom-rules
default_rules
```

```{toctree}
:caption: Contributing

contributing
Private unsupported (dev) API autodoc <pkg/modules>
```

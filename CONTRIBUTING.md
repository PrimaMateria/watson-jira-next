# Contributing

## poetry

Install dependencies

```
poetry install
```

Run the installed version

```
poetry run watson-jira
```

Or stay in the python environment

```
poetry shell
```

Tests

```
poetry run pytest ./watson_jira_next
```

Release

```
poetry version patch
poetry build
poetry publish
```

## nix 

Start development shell

```
nix develop
```

Build 

```
nix build
```

Run

```
nix run
```

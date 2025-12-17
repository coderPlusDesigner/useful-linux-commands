# Ubuntu

## General

#### Hiding or trimming command line path folders from its beginning

```
PROMPT_DIRTRIM=1
```

### Users and Groups

#### Listing all the users

```
compgen -u
```

#### List the current sessions

```
loginctl list-sessions
```
then
```
loginctl show-session <id>
```

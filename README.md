# ASMEK template overrides

> [!WARNING]
>
> These template overrides are specially tailored for the corp Astrum Mechanica [ASMEK].
> They override templates of apps we use, to adjust the look or add/augment functionality.
>
> Templates may depend on the existence of certain apps, both public and private, in order to function properly.
> You should use these as examples only, no assistance will be given if you attempt to use them directly.

## Install

You should be in your venv, in `~/myauth/myauth` or in the folder containing the static and templates folders.

```bash
git clone https://github.com/astrum-mechanica/asmek-templates.git
```

create a symlink between the repo and the auth folders

```bash
cd templates
ln -s ~/myauth/myauth/asmek-templates/templates/* .
cd ..
cd static
ln -s ~/myauth/myauth/asmek-templates/static/* .
```

Run collectstatic

## updating

```bash
git pull
```

run collectstatic

## Compatibility

- Alliance Auth V4
- Boostrap 5

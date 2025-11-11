# Build notes

- [Remove Husky](https://github.com/Tyrn/dotfiles/blob/main/messy-notes/Husky.md),
  if necessary

- Clone and install

```
git clone ...
cd casia
pnpm install
...
```

## Troubleshooting

- With `pnpm` >= 10.x, to git rid of the warnings, change `.npmrc`

```
#node-linker=hoisted
#auto-install-peers=true
```

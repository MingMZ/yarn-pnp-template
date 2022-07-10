# Yarn Plug'n'Play Template

Enable `yarn` for `nodejs` version 16.10 or later:

    corepack enable

Update `yarn` to latest version:

    yarn set version latest
    yarn set version berry
    yarn set version stable

Enable Plug'n'Play

    yarn config get nodeLinker
    yarn config set nodeLinker pnp

Install package

    yarn install --immutable
    yarn install --immutable-cache

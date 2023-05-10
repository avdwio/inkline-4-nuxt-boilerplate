# Inkline :heart: Nuxt

Followed [this guide](https://next.inkline.io/docs/installation/nuxt)

## Getting here
1. Setup nuxt:

    ```sh
    npx nuxi init .
    ```

1.  install inkline
    ```sh
    npx inkline init
    ```

1. Copy in inkline config

    Reference (found [here](https://next.inkline.io/docs/configuration/nuxt))

1. Update `inkline.config.ts`

    added new `fontFamily`: `tertiary`


## How do I get `.inkline/*` to update???

### Tried:

#### Method 1:

delete`.inkline/*`, rerun `npm install`

This regenerates `.inkline/*`, but not with the new `tertiary` fontFamily

#### Method 2:

run `npx inkline generate scss`

this regenerates `.inkline/*` with config from `inkline.config.ts`, however I don't think config in `nuxt.config.ts` is respected
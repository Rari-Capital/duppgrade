# duppgrade

Update or revert to a specific [DappTools](https://github.com/dapphub/dapptools) commit with ease.

## Installing

```sh
curl https://rari-capital.github.io/duppgrade/install | bash
```

## Using

To install the **latest** commit:

```sh
duppgrade
```

To install a **specific** commit (in this case commit `213a3...05583`):

```sh
duppgrade 213a3c5cc07b9210124afc06ca63926aee305583
```

To install a specific **branch** (in this case the `control-nonce` branch's latest commit):

```sh
duppgrade control-nonce
```

To install a **fork's master branch** (in this case `transmissionsdev/dapptools`'s master branch):

```sh
duppgrade transmissionsdev/dapptools
```

To install a **specific commit from a fork** (in this case commit `e7594...399ab` made in `transmissionsdev/dapptools`):

```sh
duppgrade transmissionsdev/dapptools e7594a6a8228bfb2494385e02d4e79d8fa2399ab
```

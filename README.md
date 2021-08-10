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

To install a **specific** commit (in this case `213a3c5cc07b9210124afc06ca63926aee305583`):

```sh
duppgrade 213a3c5cc07b9210124afc06ca63926aee305583
```

To install a specific **branch** (in this case `hevm/0.48.0`):

```sh
duppgrade hevm/0.48.0
```

To install a specific **fork's master branch** (in this case `transmissionsdev/dapptools`):

```sh
duppgrade transmissionsdev/dapptools
```

To install a **fork's specific commit** (in this case `transmissionsdev/dapptools`'s `e7594a6a8228bfb2494385e02d4e79d8fa2399ab` commit):

```sh
duppgrade transmissionsdev/dapptools e7594a6a8228bfb2494385e02d4e79d8fa2399ab
```

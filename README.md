# Cordyceps Finance

# Foundry / Forge

## Resources

- [Foundry Book](https://book.getfoundry.sh/index.html)

## Quickstart

### Requirements Install Foundry

- [Forge/Foundryup](https://github.com/gakonst/foundry#installation)

  - You'll know you've done it right if you can run `forge --version`

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

  - You'll know you've done it right if you can run `git --version`

- Install libs
  `forge update`

## Deploy

## Test in Mainnet Fork

- make sure to create `.env` with variables in `.env.example`
- currenlty foundry is configured to only run tests in `test/v2`
- run `forge coverage` to see test coverage for V2. Tests for legacy_v1 will not be accounted for

```
forge test -vv

```

## Makefile

```
make install
```

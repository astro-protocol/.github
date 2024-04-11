Closes #{issue number}

## Summary

- Added new page `/dashboard`
- Added docs on navigating through the Dashboard pages
- Removed dead components (haven't been used in days)

## Checklist

Items checked below are included in this pull request:

- [ ] Write unit tests
- [x] Write integration tests
- [x] Write documentation

## How to Test

- Pull down this branch
- Run the server: `pnpm dev`
- Navigate to `/dashboard`
- Make sure user information is accurate

## Related PRs

- [Astro UI](https://github.com/astro-protocol/astro-ui/pulls)
  - None

- [Protocol Hosted Wallet (PHW)](https://github.com/astro-protocol/contract-testnet-protocol-hosted-wallet/pulls)
  - None

- [USDA Contract](https://github.com/astro-protocol/contract-token-usda-ao/pulls)
  - None

- [Vault Contract](https://github.com/astro-protocol/contract-vault-ao/pulls)
  - None

- [wAR Contract](https://github.com/astro-protocol/contract-token-wrapped-arweave-ao/pulls)
  - None

## Other Notes

This pull request introduces new dependencies that might not work properly in ARM-based environments.

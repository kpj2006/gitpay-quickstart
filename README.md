# gitpay-quickstart

The smallest possible [GitPay](https://github.com/StabilityNexus/GitPay) adopter: one workflow
file, three inputs, no secrets.

Comment `/send 0xRecipientAddress 1 USDC` on a pull request here, and
[`.github/workflows/gitpay.yml`](.github/workflows/gitpay.yml) runs a **dry run**. It parses the
payout, checks policy, and prints the idempotency key, and it moves nothing.

This repo is the evidence for GitPay's release-gate check "a fresh repo integrates in under 5
minutes with zero secrets, in dry-run". To pay for real, see "Going live" in GitPay's README.

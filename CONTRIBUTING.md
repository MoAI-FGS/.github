# Contributing

These rules apply to everyone who works on a Ministry of Agriculture and Irrigation repository: Ministry staff and approved vendors.

## Access

- Access is given by the Ministry's ICT section, through teams only. Ask the ICT section, not a repository admin.
- Your GitHub account must have two-factor authentication turned on.
- Personal access tokens must be fine-grained, limited to the repositories you need, and approved by an Owner.

## Working on code

1. Create a branch from `main`. Name it `feature/<short-name>`, `fix/<short-name>` or `chore/<short-name>`.
2. Make small commits with clear messages. Sign off each commit (`git commit -s`).
3. Open a pull request into `main` using the template, and ask a member of the reviewers team to review it.
4. Do not merge your own pull request. A reviewer merges it once checks pass.

## Never commit

- passwords, API keys, tokens, certificates or private keys
- `.env` files or production configuration
- personal data about farmers, staff or citizens, including in test data or screenshots

If you commit a secret by mistake, tell the ICT section at once. Deleting it in a later commit is not enough: the secret must be revoked.

## GitHub Actions

Only actions made by GitHub or verified creators are allowed, and they must be pinned to a full commit SHA. Workflows get read-only permissions by default; ask for more only in the job that needs it.

## Questions

Contact the ICT section at [ict@moa.gov.so](mailto:ict@moa.gov.so).

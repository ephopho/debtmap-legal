# DebtMap legal pages

The paywall and Settings link to a Privacy Policy and Terms of Use. Apple
Guideline 3.1.2 requires these links to be **live and functional** before review
— dead links are a rejection cause.

These two pages are wired in [`constants/legal.ts`](../constants/legal.ts):

- `https://ephopho.github.io/debtmap-legal/privacy/`
- `https://ephopho.github.io/debtmap-legal/terms/`

## Publishing (GitHub Pages)

1. Create a public repo named **`debtmap-legal`** under the `ephopho` account.
2. Copy the contents of this folder to the repo root so the structure is:
   ```
   debtmap-legal/
     privacy/index.html
     terms/index.html
   ```
3. Repo → **Settings → Pages** → Source: `main` branch, `/ (root)`. Save.
4. After a minute the URLs above go live. Open both on a phone to confirm.

## Before submitting

- Review the policy text — it reflects DebtMap's real data flows (all debt data
  stored on-device, RevenueCat for subscriptions, optional local notifications,
  no analytics). Adjust if anything changes.
- Confirm the contact email (`phophooe@gmail.com`) is the one you want public.
- Add the **Privacy Policy URL** to App Store Connect → App Privacy, and publish
  the App Privacy "nutrition label" so the labels match this policy.

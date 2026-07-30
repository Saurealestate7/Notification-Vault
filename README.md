# Notification Vault — Privacy Policy (hosted)

This repo hosts the public Privacy Policy for the **Notification Vault** Android app, linked from the Play Store listing and from the app's Settings screen.

## Live URL — ✅ live since 2026-07-30

```
https://saurealestate7.github.io/Notification-Vault/
```

⚠️ **Note the capitalisation.** GitHub Pages project-site paths are case-sensitive and must match the repository name exactly — `Notification-Vault`, not `notification-vault`. The all-lowercase form returns **404** even when Pages has deployed successfully, which is easy to mistake for a broken deployment. This cost us a round of false debugging; don't repeat it.

Pages is already enabled (**Settings → Pages → Source: Deploy from a branch → `main` → `/ (root)`**). Pushing to `main` redeploys automatically.

## Editing

`index.html` is the actual policy page. Edit that file and push to update the live policy — no build step, plain static HTML.

The app's own repo (`notificationvault_8june`) keeps a matching Markdown copy at `docs/privacy-policy.md` for version control alongside the app. **Keep both in sync whenever either changes** — the Markdown copy is the version-controlled source of record; this `index.html` is what the public and the Play Console actually see.

## Play Console

The URL above is what goes in **Play Console → Policy and programs → App content → Privacy policy**. After any edit to `index.html`, re-open the live link (incognito, so you're not seeing a cache) and confirm it renders before relying on it — Play refetches the URL during review.

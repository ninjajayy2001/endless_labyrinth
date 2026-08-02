# Endless Labyrinth Public Files

This repository hosts the public web files required by the mobile game **Endless Labyrinth**.

It does **not** contain the Unity project source code, game assets, keystore files, or any private developer data.

## Hosted Files

| File | Purpose |
| --- | --- |
| `/endless-labyrinth/health.txt` | Lightweight internet connectivity check used by the game. |
| `/endless-labyrinth/privacy.html` | Public privacy policy URL for Google Play. |
| `/app-ads.txt` | Authorized sellers file for Google AdMob. |

## Expected URLs

Replace `<github-username>` with the GitHub account name that owns the Pages repository:

```text
https://<github-username>.github.io/endless-labyrinth/health.txt
https://<github-username>.github.io/endless-labyrinth/privacy.html
https://<github-username>.github.io/app-ads.txt
```

## Notes

- The `health.txt` file must return exactly `ok`.
- The repository should be public so GitHub Pages, Google Play, AdMob, and the game client can access these files.
- If the AdMob publisher ID changes, update `app-ads.txt`.


# Tunisia 1943 · Tunisie 1943

The Second World War in Tunisia in short animations, quizzes and hands-on experiments, in English and French: the campaign of 1942–43, life under the occupation, the novels and films it inspired, how it is remembered, and places to visit.

**The app: https://deneszalan.github.io/Tun-WW/**

This repository only publishes the app. Its posts and code live in [deneszalan/instasmart](https://github.com/deneszalan/instasmart), in `editions/tunisia/`; see its README there. The workflow in `.github/workflows/deploy.yml` builds instasmart and publishes it here. To publish a version, write its instasmart commit into `instasmart.sha` and push: the push publishes exactly that commit. Every hour, and when run by hand (Actions → Deploy → Run workflow), it publishes instasmart's main branch instead, the hourly run only when that branch has changed. Pages is set to publish from GitHub Actions (Settings → Pages).

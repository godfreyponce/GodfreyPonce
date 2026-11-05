<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark_mode.svg">
  <source media="(prefers-color-scheme: light)" srcset="light_mode.svg">
  <img alt="Godfrey Ponce braille portrait with profile info" src="dark_mode.svg">
</picture>

Junior CS student in Dallas. Most of these started as a problem I had that week, and I wrote down what broke. Most of my commits are in private repos, so this is the part I can show. [Here's my site](https://godfreyponce.dev), and I'm on [LinkedIn](https://www.linkedin.com/in/godfreyponce/)

## Things I actually use every day

- **[kal](https://github.com/godfreyponce/kal)**: Started tracking my calories, so I built a tracker. Claude kept guessing serving sizes and gave me 372 g protein days, so now it gets real units before it sees a meal
- **[Debrief](https://github.com/godfreyponce/Debrief)**: My morning paper. Makes it easier for me to keep up with AI and tech. Every free X bridge died, so it reads X's embed backend now and caches it to stay under the rate limit

## Work stuff

- **[jiraPlane](https://github.com/godfreyponce/jiraPlane)**: A paper airplane flies across my screen when Jira needs me, and a coworker runs it too. launchd's PATH couldn't find `aerospace`, so multi-display flight broke with no error
- **[Jira-Alerts](https://github.com/godfreyponce/Jira-Alerts)**: Jira emails are horrible, so my tickets DMed me on Teams instead. GitHub Actions cron ran about once an hour instead of twelve times, comments aged out, so I moved the timer to launchd. jiraPlane does this job now

## Other people's code

- **[WP-Admin-Wordpress](https://github.com/phamleduy04/WP-Admin-Wordpress/pulls?q=is%3Apr+author%3Agodfreyponce+is%3Amerged)**: 3 merged PRs on a browser extension for UT Dallas WordPress sites. Fixed the switch buttons on subfolder sites and added editor buttons. It ships to the Chrome and Firefox stores
- **[next.js#48012](https://github.com/vercel/next.js/issues/48012#issuecomment-5938917640)**: Reran an old Jest mocking bug. It passes on 13.2.3 and still fails on 13.2.4 and the 16.4 canary. Looks like Next rewrites the `@/` import path before Jest sees it, so Jest loads the real hook instead of the mock
- **[t3code#19536](https://github.com/pingdotgg/t3code/issues/19536#issuecomment-6666818150)**: A toolbar bug came back, so I traced it to a reverted fix and said so on the closed issue

## Everything else

- **[clawd](https://github.com/godfreyponce/clawd)**: I 3D printed [clawd-mochi](https://github.com/yousifamanuel/clawd-mochi), a crab for my desk, and wired it to Claude Code so I know how my agents are doing. The flash said success and serial was dead, because USB CDC on boot was off
- **[EchoMap](https://github.com/godfreyponce/hacksmu-26)**: HackSMU project with a teammate. Cleans noise out of elephant recordings, and the denoiser is classical DSP, no ML. We measured it, and it helps noisy audio a little but makes clean audio worse
- **[terrariaCompanion](https://github.com/godfreyponce/terrariaCompanion)**: Played Terraria for the first time this year, idk where to start, so I built this. It still mixes up weapons and armor on one of my test questions
- **[LocalPro-Realty](https://github.com/godfreyponce/LocalPro-Realty)**: Internship take home project that I got ghosted on
- **[glass](https://github.com/godfreyponce/glass)**: A simplified way to check on everything I was building. Retired in October when a tickets button in T3 Code replaced it

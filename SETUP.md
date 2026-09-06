# Aayan Chowhan — Profile README Setup

Your profile repository already exists at:

`https://github.com/ayaanchowhan09/ayaanchowhan09`

## Folder structure

```text
ayaanchowhan09/
├── README.md
├── SETUP.md
├── assets/
│   ├── banner.svg
│   ├── divider.svg
│   ├── footer.svg
│   ├── github-stats.svg
│   ├── social-email.svg
│   ├── social-github.svg
│   ├── social-linkedin.svg
│   ├── top-languages.svg
│   └── typing.svg
└── .github/
    └── workflows/
        ├── snake.yml
        └── stats.yml
```

## Easiest installation — GitHub website

1. Extract the downloaded ZIP.
2. Open `https://github.com/ayaanchowhan09/ayaanchowhan09`.
3. Choose **Add file → Upload files**.
4. Drag everything *inside* the `github-profile` folder into the upload area. Upload `README.md`, `SETUP.md`, `assets`, and `.github`—not the outer `github-profile` folder.
5. Use the commit message `build: redesign GitHub profile` and commit to `main`.
6. Open **Settings → Actions → General → Workflow permissions**.
7. Select **Read and write permissions**, then save.
8. Open the **Actions** tab.
9. Select **Update Profile Stats → Run workflow → Run workflow**.
10. Select **Generate Contribution Snake → Run workflow → Run workflow**.
11. Wait about one minute, then refresh `https://github.com/ayaanchowhan09`.

The placeholders in `assets/github-stats.svg` and `assets/top-languages.svg` are automatically replaced after the first stats workflow run. The snake is generated into an automatically created branch named `output`.

## Alternative installation — Git command line

Run these commands from the extracted package directory:

```bash
git clone https://github.com/ayaanchowhan09/ayaanchowhan09.git
cd ayaanchowhan09
```

Copy the contents of the `github-profile` folder into the cloned repository, then run:

```bash
git add README.md SETUP.md assets .github
git commit -m "build: redesign GitHub profile"
git push origin main
```

Then complete steps 6–11 from the website instructions.

## Automatic updates

- `stats.yml` refreshes both stats cards daily at **03:15 UTC** and can also be run manually.
- `snake.yml` refreshes both light and dark purple snakes daily at **03:00 UTC** and can also be run manually.
- Both workflows run once when the profile files are first pushed to `main`.

## Important links already verified in README.md

- GitHub username: `ayaanchowhan09`
- GitHub profile: `https://github.com/ayaanchowhan09`
- LinkedIn: `https://www.linkedin.com/in/aayan-chowhan-860439414/`
- Email: `ayaanchowhan09@gmail.com`

## Design choices

- BackBench is featured first because it is the strongest public engineering repository.
- Paradise Nursery demonstrates React, routing, and Redux state management.
- ML-project is labeled **in progress** because its public repository currently contains only the project description, not an implementation.
- The interest-calculator course repository and empty repositories are intentionally not featured.
- Stats are generated as repository-hosted SVGs instead of depending on a rate-limited public stats endpoint.
- A streak card, separate activity graph, profile-view counter, and extra badges were removed to keep the profile credible and uncluttered.

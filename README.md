# Tandem: a Reshoot demo

Tandem is a small invoicing app (`app/index.html`). Its walkthrough video and help article are code: [`reshoot.yml`](reshoot.yml) lists the steps, and [`.github/workflows/reshoot.yml`](.github/workflows/reshoot.yml) runs the [Reshoot action](https://github.com/kiromoussa/reshoot-action) on every pull request.

Open a pull request that changes the UI and Reshoot re-records the video, rewrites the help article, and comments with a before and after frame of each step that changed. If a change breaks a step (a button is renamed, say), the check fails and the comment shows the page at the moment it broke.

Pushes to `main` save the baseline that pull requests are compared against.

<sub>Made with [Reshoot](https://reshoot-pi.vercel.app)</sub>

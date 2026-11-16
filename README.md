# Nod Builder

The phone version of Nod's node flow. Nod's desktop app can't run on the phone (x64-only Flatpak build, needs a desktop secret store and /dev/kvm), so the builder lives here as a page.

- Describe the agent in plain words, it stacks a node canvas: Trigger → Source → Build APK → Privacy Scan → F-Droid Index → Link Check → Publish Gate
- Live JSON config plus a downloadable build plan aimed at the live n8n instance (hiai808.app.n8n.cloud)
- Open `index.html` in a browser. Nothing here sends, publishes, or spends — the Publish Gate is the Founder's tap.

Repo map on the page: F-Droid Atlas, HI-AI Builder, x-it, and GitHub — 33 repos total (29 under xavierhoolulu13-dotcom, 4 under x1500556-ops), all linked out.

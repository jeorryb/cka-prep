# CKA Prep

A mobile-friendly study app for the Certified Kubernetes Administrator (CKA) exam.
Built to replace doomscrolling with something actually useful.

## Features

- **Flash cards** — 30 cards across all 6 CKA exam domains, shuffled each session
- **Quiz mode** — 15 scenario-style questions that mirror the real exam format, with explanations
- **kubectl reference** — 30+ commands organized by category, fully searchable
- **AI explain** — tap any flash card to get a deeper Claude-powered exam-focused breakdown
- **Stats tracking** — accuracy by domain, day streak, and weakest area detection

## CKA Domains Covered

- Cluster Architecture, Installation & Configuration
- Workloads & Scheduling
- Services & Networking
- Storage
- Security
- Troubleshooting

## Setup: Deploy with GitHub Pages

1. Fork or clone this repo
2. Go to your repo's **Settings** tab
3. In the left sidebar, click **Pages**
4. Under "Branch" select **main**, leave folder as `/ (root)`, click **Save**
5. Wait 1–2 minutes — your app will be live at `https://yourusername.github.io/cka-prep`

## How to Install on Your Phone

**iPhone:**
1. Open your GitHub Pages URL in **Safari**
2. Tap the Share button (box with arrow at the bottom)
3. Tap **Add to Home Screen**
4. Tap **Add**

**Android:**
1. Open your GitHub Pages URL in **Chrome**
2. Tap the three-dot menu
3. Tap **Add to Home Screen**

The app will appear on your home screen and open full-screen with no browser chrome.

## AI Explain Feature

The "Explain deeper with AI" button on each flash card calls the Claude API.
It works automatically when opened from the hosted GitHub Pages URL. If running
locally, add your Anthropic API key in the Stats tab — it saves to your device
and only needs to be entered once.

## Course

Built as a companion to the [KodeKloud CKA course on Udemy](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/).
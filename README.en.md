<p align="center">
  <a href="https://sealednet.com/en/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/lockup-dark.svg">
      <img alt="SealedNet" src=".github/assets/lockup.svg" height="64">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://sealednet.com/en/">Website</a> ·
  <a href="https://sealednet.com/en/docs/quickstart">Quick start</a> ·
  <a href="https://sealednet.com/en/docs/capabilities">What it does</a> ·
  <a href="https://sealednet.com/en/pricing">Pricing</a> ·
  <a href="README.md">中文</a>
</p>

# SealedNet

A separate environment (browser, desktop, terminal or application) for every team and client. Each environment is bound to a line of your own, and its timezone and language follow where that line exits. If the line drops, the environment loses network access instead of falling back to the machine's own network.

## How it works

- **SealedNet hosts the console**: sign up at [sealednet.com](https://sealednet.com/en/) and manage machines, lines, environments and teams.
- **Environments run on your own machine**: one command on a Windows PC, or any Linux server (x86_64 / arm64). No public IP and no open ports.
- **Traffic never passes through SealedNet**: it goes from your machine straight into your line.

## Features

- **Environments**: templates such as cloud browser, Linux desktop, terminal and an Android development environment; Docker applications from the app catalog; or your own image. Every environment has its own data volume, and updates only swap the image.
- **Access**: desktop in the browser (direct WebRTC first, relay as fallback, works on mobile), web terminal, the application's own web port, and TCP port mapping. No remote-access software to install.
- **Stays offline when the line drops**: environments live on a dedicated network where all traffic, UDP included, can only use the bound line.
- **Exit checks**: scheduled checks of exit IP, country, DNS, UDP and WebRTC, IPv6 and more; line quality grades, history and alerts.
- **Teams**: owner, admin, member and read-only roles.

## What it is not

- **Not a proxy seller**: lines are your own SOCKS5 or HTTP proxies.
- **Not a VPN or accelerator**: it manages environments on your machine and leaves your computer's own network alone.
- **Not a hosting provider**: environments run on your Windows PC or your own Linux machine.

## Getting started

1. Sign up at [sealednet.com](https://sealednet.com/en/) and verify your email.
2. Add a machine in the console and run the install command it gives you on your Windows PC or Linux server.
3. Add a line and run a check.
4. Install an environment and open it in the browser.

The full walkthrough is in the [quick start](https://sealednet.com/en/docs/quickstart); all docs are at [sealednet.com/en/docs](https://sealednet.com/en/docs/).

## About this repository

This is SealedNet's official home on GitHub; it does not contain the product's source code. Questions and suggestions are welcome as [issues](https://github.com/sealednet/sealednet/issues), or reach us via [support](https://sealednet.com/en/docs/support).

# Aibex

**Aibex** is a macOS app for working with AI coding agents across several projects at once: each
project gets its own tab, the agent's replies and diffs are easy to read, and every change is
reviewed before it lands. Learn more on the product page:
[zaseeta.com/aibex](https://zaseeta.com/aibex/) (English:
[zaseeta.com/aibex/index-en.html](https://zaseeta.com/aibex/index-en.html)).
How to use it, from opening a folder to troubleshooting, is in the
[User Guide](https://zaseeta.com/aibex/user-manual-en.html).

日本語は[下](#aibex-日本語)にあります。

## What this repository is

This repository **does not contain the source code**. Aibex's source is not public.
It exists for two things only:

- [Releases](https://github.com/object-zaseeta/Aibex/releases) — the downloads: the DMG for new
  installs, and the signed update archive that the app itself fetches.
- [Issues](https://github.com/object-zaseeta/Aibex/issues) — questions, bug reports and feedback,
  in English or Japanese.

## Download and requirements

- Get the latest `Aibex_<version>_aarch64.dmg` from
  [Releases](https://github.com/object-zaseeta/Aibex/releases/latest), open it and drag Aibex to
  Applications.
- **Apple Silicon Macs only**, **macOS 26 or later**. The app is signed with a Developer ID and
  notarized by Apple.
- Aibex drives the AI through tools you bring yourself: `node`, `pnpm` and the `claude` command-line
  tool must be installed and on your `PATH`. On first launch, Aibex downloads the agent runtime
  it needs after asking you.

## Beta

- The beta is **free**. **The full release will be paid.**
- Each beta build works for **90 days** from the day it was built. Aibex checks GitHub for a newer
  version when it starts and once a day, downloads it in the background, and offers a one-click
  restart; installing a newer version extends the period. When a build expires, the app only
  shows a notice and lets you install the newer version.
- The only network connection Aibex itself makes is that update check against this repository's
  Releases. Everything else — the agent's traffic — goes through the tools you brought.
- Third-party notices are inside the app: **About Aibex** in the menu bar.

---

# Aibex（日本語）

**Aibex** は、複数のプロジェクトで AI のコーディングエージェントを同時に使うための macOS アプリです。
プロジェクトごとにタブを持ち、エージェントの返答と差分を読みやすく出し、変更は取り込む前に必ず確かめます。
くわしくは製品ページ [zaseeta.com/aibex](https://zaseeta.com/aibex/) をご覧ください。
フォルダを開くところから困ったときまでの使い方は、[Aibex の使い方](https://zaseeta.com/aibex/user-manual.html)にまとめています。

## このリポジトリについて

このリポジトリに**ソースコードは置いていません**（Aibex のソースは公開していません）。
置いているのは Releases と Issues の 2 つだけです。

- [Releases](https://github.com/object-zaseeta/Aibex/releases) — ダウンロード。新しく入れる人のための DMG と、
  アプリが自分で取りに来る署名つきの更新の書庫。
- [Issues](https://github.com/object-zaseeta/Aibex/issues) — 質問・不具合の報告・ご意見。日本語でも英語でも。

## ダウンロードと動作の前提

- [Releases](https://github.com/object-zaseeta/Aibex/releases/latest) から最新の `Aibex_<version>_aarch64.dmg` を取り、
  開いて Aibex を Applications に入れてください。
- **Apple Silicon の Mac のみ**、**macOS 26 以降**。アプリは Developer ID で署名し、Apple の公証を受けています。
- AI は持ち込みの道具で動かします。`node`・`pnpm`・`claude` のコマンドラインツールを入れて、`PATH` から
  使える状態にしておいてください。初回の起動で、必要なエージェントのランタイムを確かめてから取得します。

## ベータについて

- ベータは**無料**です。**正式版は有料になる予定です。**
- ベータの各ビルドは、ビルドの日から **90 日**使えます。Aibex は起動時と 1 日 1 回、新しい版があるかを確かめ、
  裏でダウンロードしてから「再起動して更新」を出します。新しい版を入れると期限が延びます。期限が切れたら、
  案内を出して新しい版を入れられるようにするだけで、ほかには何もしません。
- Aibex 自身がつなぐ先は、この更新の確かめで GitHub にだけつなぎます（この Releases）。それ以外の通信
  （エージェントのやり取り）は、持ち込んだ道具のものです。
- 権利表記はアプリの中にあります（メニューバーの **About Aibex**）。

---
title: "作为服务端进行公网传输"
description: "v2rayA 作为服务端进行公网传输介绍"
lead: "v2rayA 作为客户端默认仅开放 http 和 socks5 入站，这些入站均不适合进行公网数据传输。本节介绍作为中转时如何开放适合公网传输的代理端口。"
date: 2020-11-16T13:59:39+01:00
lastmod: 2020-11-16T13:59:39+01:00
draft: false
images: []
menu:
  docs:
    parent: "advanced-application"
toc: true
weight: 680
---

## Requirements

Doks uses npm to centralize dependency management, making it [easy to update]({{< relref "how-to-update" >}}) resources, build tooling, plugins, and build scripts:

- Download and install [Node.js](https://nodejs.org/) (it includes npm) for your platform.

## Start a new Doks project

Create a new site, change directories, install dependencies, and start development server.

### Create a new site

Doks is available as a child theme, and a starter theme:

- Use the Doks child theme, if you do __not__ plan to customize a lot, and/or need future Doks updates.
- Use the Doks starter theme, if you plan to customize a lot, and/or do __not__ need future Doks updates.

Not quite sure? Use the Doks child theme.

#### Doks child theme

```bash
git clone https://github.com/v2rayA/v2raya.github.io-child-theme.git my-doks-site
```

#### Doks starter theme

```bash
git clone https://github.com/v2rayA/v2raya.github.io.git my-doks-site
```

### Change directories

```bash
cd my-doks-site
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run start
```

Doks will start the Hugo development webserver accessible by default at `http://localhost:1313`. Saved changes will live reload in the browser.

## Other commands

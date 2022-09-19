# <img width="64" align="center" src="assets/logo.png" /> Esmerelda

#### Your sweet maid: more than just an open-source assistant.
<!--
#### Your sweet maid: the world's most advanced open-source artificially intelligent software.
-->

<p align="center">
  <a title="Azure Pipeline" target="_blank" href="https://dev.azure.com/CodenameDepth/Esmerelda">
    <img align="left" src="https://dev.azure.com/CodenameDepth/Esmerelda/_apis/build/status/Build%20Pipeline%20(x64)?branchName=main">
  </a>
  <a title="GitHub Releases" target="_blank" href="https://github.com/DepthCDLS/Esmerelda/tree/stable">
    <img align="left" src="https://img.shields.io/github/v/release/DepthCDLS/Esmerelda?include_prereleases" alt="Release" />
  </a>
  <a title="Platform" target="_blank">
    <img align="left" src="https://img.shields.io/badge/Platform-Windows-red" alt="Platform" />
  </a>
</p>

<br/>

---

## ➕ Installation

### Via GitHub

See the [releases page](https://github.com/DepthCDLS/Esmerelda/releases)

### Building from source
###### ⭐Recommended⭐

This is our preferred method.
See [this section](#-building-the-code)

## 🧑‍💻 Contributing

There are multiple ways to participate in the community:

- [Submit bugs and feature requests](https://github.com/DepthCDLS/Esmerelda/issues/new/choose).
- Review source [code changes](https://github.com/DepthCDLS/Esmerelda/commits)

### 🏗️ Codebase Structure

```
.
└──src                               // The source code.
   ├──Esme.Services                  // Simple computer functions that Esme can complete
   └──Esme.Intelligence              // Intelligence repository
```
<!--   └──Esme.Hypervisor                // Simulation software-->
### 🗃️ Contributors

<a href="https://github.com/DepthCDLS/Esmerelda/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DepthCDLS/Esmerelda" />
</a>

## 🦜 Feedback

- [Request a new feature](https://github.com/DepthCDLS/Esmerelda/pulls)
- Upvote popular feature requests
- [File an issue](https://github.com/DepthCDLS/Esmerelda/issues/new/choose)

## 🔨 Building the Code

##### 1. Prerequisites

Ensure you have following components:

- [Git](https://git-scm.com/)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) with following individual components:
  - Python SDK

### 2. Git

Clone the repository:

```git
git clone https://github.com/DepthCDLS/Esmerelda
```

Choose which channel you want via branches. You can choose from either [stable](https://github.com/DepthCDLS/Esmerelda/tree/stable) or [dev](https://github.com/DepthCDLS/Esmerelda/tree/dev).

### 4. Build the project

- Open `Esmerelda.sln`.
- Choose which function you want Esme to start with and right-click on the appropriate project, and select 'Set as startup item'
- Build with `DEBUG|x64`

## 💳 Credit

- Icons8 created the current logo.

## ⚖️ License

Copyright (c) 2022 Depth

Licensed under the MIT license as stated in the [LICENSE](LICENSE.md).

<p align="center">
  <img src="https://raw.githubusercontent.com/reworkd/AgentGPT/main/public/banner.png?token=GHSAT0AAAAAAB7JND3U3VGGF3UYYHGYO4RAZBSDJAQ" height="300"/>
</p>
<p align="center">
  <em>🤖 Assemble, configure, and deploy autonomous AI Agents in your browser. 🤖 </em>
</p>
<p align="center">
    <img alt="Node version" src="https://img.shields.io/static/v1?label=node&message=%20%3E=16.0.0&logo=node.js&color=2334D058" />
      <a href="https://github.com/reworkd/AgentGPT/blob/master/README.md"><img src="https://img.shields.io/badge/lang-English-blue.svg" alt="English"></a>
  <a href="https://github.com/reworkd/AgentGPT/blob/master/docs/README.zh-HANS.md"><img src="https://img.shields.io/badge/lang-简体中文-red.svg" alt="简体中文"></a>
  <a href="https://github.com/reworkd/AgentGPT/blob/master/docs/README.hu-Cs4K1Sr4C.md"><img src="https://img.shields.io/badge/lang-Hungarian-red.svg" alt="Hungarian"></a>
</p>

<p align="center">
<a href="https://agentgpt.reworkd.ai">🔗 Short link</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="#-getting-started">🤝 Contribute</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://twitter.com/asimdotshrestha/status/1644883727707959296">🐦 Twitter</a>
<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
<a href="https://discord.gg/gcmNyAAFfV">📢 Discord</a>
</p>

---

<h2 align="center">
💝 Support the Advancement of AgentGPT!! 💝
</h2>



## 🚀 Tech Stack

- ✅ **Bootstrapping**: [create-t3-app](https://create.t3.gg).
- ✅ **Framework**: [Nextjs 13 + Typescript](https://nextjs.org/).
- ✅ **Auth**: [Next-Auth.js](https://next-auth.js.org)
- ✅ **ORM**: [Prisma](https://prisma.io).
- ✅ **Database**: [Supabase](https://supabase.com/).
- ✅ **Styling**: [TailwindCSS + HeadlessUI](https://tailwindcss.com).
- ✅ **Typescript Schema Validation**: [Zod](https://github.com/colinhacks/zod).
- ✅ **End-to-end typesafe API**: [tRPC](https://trpc.io/).

## 👨‍🚀 Getting Started

### 🐳 Docker Setup

The easiest way to run AgentGPT locally is by using docker.
A convenient setup script is provided to help you get started.

```bash
./setup.sh --docker
```

### Docker-compose

Using `docker-compose` deploy

```bash
./setup.sh --docker-compose
```

### 👷 Local Development Setup

If you wish to develop AgentGPT locally, the easiest way is to
use the provided setup script.

```bash
./setup.sh --local
```

### 🛠️ Manual Setup

> 🚧 You will need [Nodejs +18 (LTS recommended)](https://nodejs.org/en/) installed.

1. Fork this project:

- [Click here](https://github.com/reworkd/AgentGPT/fork).

2. Clone the repository:

```bash
git clone git@github.com:YOU_USER/AgentGPT.git
```

3. Install dependencies:

```bash
cd AgentGPT
npm install
```

4. Create a **.env** file with the following content:

> 🚧 The environment variables must match the following [schema](https://github.com/reworkd/AgentGPT/blob/main/src/env/schema.mjs).

```bash
# Deployment Environment:
NODE_ENV=development

# Next Auth config:
# Generate a secret with `openssl rand -base64 32`
NEXTAUTH_SECRET=changeme
NEXTAUTH_URL=http://localhost:3000
DATABASE_URL=file:./db.sqlite

# Your open api key
OPENAI_API_KEY=changeme
```

5. Modify prisma schema to use sqlite:

```bash
./prisma/useSqlite.sh
```

**Note:** This only needs to be done if you wish to use sqlite.

6. Ready 🥳, now run:

```bash
# Create database migrations
npx prisma db push
npm run dev
```

### 🚀 GitHub Codespaces

Set up AgentGPT in the cloud immediately by using [GitHub Codespaces](https://github.com/features/codespaces).

1. From the GitHub repo, click the green "Code" button and select "Codespaces".
2. Create a new Codespace or select a previous one you've already created.
3. Codespaces opens in a separate tab in your browser.
4. In terminal, run `bash ./setup.sh --local`
5. When prompted in terminal, add your OpenAI API key.
6. Click "Open in browser" when the build process completes.

- To shut AgentGPT down, enter Ctrl+C in Terminal.
- To restart AgentGPT, run `npm run dev` in Terminal.

Run the project 🥳

```
npm run dev
```

---

<h3 align="center">
🙌🏻 Our Sponsers Continued 🙌🏻
</h3>

<div align="center" dir="auto">
  <a href="https://github.com/Trecares" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/Trecares.png" width="50px" alt="Trecares" style="max-width:100%;">
  </a>
  <a href="https://github.com/oryanmoshe" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/oryanmoshe.png" width="50px" alt="oryanmoshe" style="max-width:100%;">
  </a>
  <a href="https://github.com/rekimcn" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/rekimcn.png" width="50px" alt="rekimcn" style="max-width:100%;">
  </a>
  <a href="https://github.com/qwe777897" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/qwe777897.png" width="50px" alt="qwe777897" style="max-width:100%;">
  </a>
  <a href="https://github.com/ClayNelson" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/ClayNelson.png" width="50px" alt="ClayNelson" style="max-width:100%;">
  </a>
  <a href="https://github.com/xuxizhen" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/xuxizhen.png" width="50px" alt="xuxizhen" style="max-width:100%;">
  </a>
  <a href="https://github.com/destro225" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/destro225.png" width="50px" alt="destro225" style="max-width:100%;">
  </a>
  <a href="https://github.com/mouhaxp" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/mouhaxp.png" width="50px" alt="mouhaxp" style="max-width:100%;">
  </a>
  <a href="https://github.com/carlosbartolomeu" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/carlosbartolomeu.png" width="50px" alt="carlosbartolomeu" style="max-width:100%;">
  </a>
  <a href="https://github.com/Agronobeetles" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/Agronobeetles.png" width="50px" alt="Agronobeetles " style="max-width:100%;">
  </a>
  <a href="https://github.com/CloudyGuyThompson" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/CloudyGuyThompson.png" width="50px" alt="CloudyGuyThompson" style="max-width:100%;">
  </a>
  <a href="https://github.com/xinghz" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/xinghz.png" width="50px" alt="xinghz" style="max-width:100%;">
  </a>
  <a href="https://github.com/Jaimbart" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/Jaimbart.png" width="50px" alt="Jaimbart" style="max-width:100%;">
  </a>
  <a href="https://github.com/Jhonvolt17" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/Jhonvolt17.png" width="50px" alt="Jhonvolt17" style="max-width:100%;">
  </a>
  <a href="https://github.com/koltziver" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/koltziver.png" width="50px" alt="koltziver" style="max-width:100%;">
  </a>
  <a href="https://github.com/sirswali" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/sirswali.png" width="50px" alt="sirswali" style="max-width:100%;">
  </a>
  <a href="https://github.com/DixonFyre" style="display: inline-block; margin-right: 20px;">
    <img src="https://github.com/DixonFyre.png" width="50px" alt="DixonFyre" style="max-width:100%;">
  </a>

</div>

# Cloudflare Workers Getting Started Guide

This guide walks you through creating and deploying your first Cloudflare Worker using the command line.

Reference: https://developers.cloudflare.com/workers/get-started/guide/

## Create a New Worker

**Use cmd**

```
npm create cloudflare
```

Follow the prompts:

1. Give your app a name
2. What would you like to start with? → Hello world (choose yours)
3. Which template? → Worker only (choose yours)
4. Which Language? → Typescript (choose yours)

---

## Login to Cloudflare

```
npx wrangler login
```

You will be redirected to this page → Hit allow

[Allow wrangler](https://prnt.sc/L2VBQl4JrIQ8)

## Check Login Status

```
npx wrangler whoami
```

## Deploy Application

Deploy your worker using either:

```
npm run deploy
```

or

```
wrangler deploy
```
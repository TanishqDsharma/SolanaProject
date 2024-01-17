# Project Description:
In this project we created an application that allows users to create a new token mint, create a token account, and then finally mint tokens.

## Setting Up the environment:
You can setup your project directory in anyway you want but I am setting up like below:
Creating a directory for this project first and navigating inside it:
```bash
mkdir tokenproject
cd tokenProject
```
## Install the dependencies:
After navigating inside the project template, now we need to install the below dependencies:
```bash
npm install
or
npm install --legacy-peer-deps
```

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Interacting with Token Minting Application:

After running the development server and visiting "127.0.0.1:3000" address in your browser, you will be getting this:

![Alt text](https://github.com/TanishqDsharma/SolanaProject/blob/main/images/img1.png)

Now, connect your Phantom wallet with application and then you will be getting access to Applications functionalites:

![Alt text](https://github.com/TanishqDsharma/SolanaProject/blob/main/images/img2.png)

In this project, we have created three functions: 
1. Create Mint : This button allow you to create Token Mint account. A token mint Account holds all the metadata information about the token such as supply, decimal precision,MintAuthority, FreezeAuthority.
* After, clicking on "Create Mint" button you will be getting a prompt from your wallet:
![Alt text](https://github.com/TanishqDsharma/SolanaProject/blob/main/images/img3.png)

* Click on "Confirm" and you will be seeing address of your token mint account and link for the transaction in Solana Explorer:
![Alt text](https://github.com/TanishqDsharma/SolanaProject/blob/main/images/img4.png)



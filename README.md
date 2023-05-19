# Fedi Alpha

Fedi Alpha, powered by Fedimint. 

Fedimint is a modular open source protocol to custody and transact bitcoin in a community context, built on a strong foundation of privacy. 

Fedi is the worlds first Federated OS. It works with Fedimint to build Federations, that let communtiies take back control. Your money, your data data and your online life.

Federations are made up of a set of fedimint servers run by independent guardians that collaborate to form a federation. In this repo we have packaged a custom build of Fedimint that will help you setup your own federations and connect using Fedi Alpha.

## 1. Try out Fedi

The simplest way to understand a fedimint is to use one!

**** DOWNLOAD IMAGE LINKS TO FEDI ON APP STORE **** **** AND PLAY STORE ****

Text links for options on .apk and pwa options. 

Whilst we've been zapping eCash around the planet and funding geyser campaigns with for little while now, we recognise that nothing gets an idea across like first hand use. To make this easy we have deployed a public federation to the [MutinyNet bitcoin signet](https://blog.mutinywallet.com/mutinynet/).  

We love the mision of Mutinynet for experimentation and testing long run lightning enabled apps in a more real world environment , we hope to see many more apps and mods deploying test instances here soon - let us know if you join and maybe we can add you to Fedi!

Once you've got the app, you'll want to connect to a federation and get setup with some signet satoshis, just head to [alpha.fedi.xyz](https://alpha.fedi.xyz) to get started.

![image](https://github.com/fedibtc/fedi-alpha/assets/42595944/60a53bdb-3236-40fa-a835-ef8d682ce8da)

> Please be aware that Fedi Alpha operates on a signet Federation, where all the Sats/Bitcoin within this federation, including the faucet website associated with it, hold no monetary value and are solely intended for testing purposes.
>
> We strongly advise against using this version of the app for any significant financial transactions as there is a risk of loss. It is important to note that Fedi assumes no responsibility for any loss or use of the test version of the app and web app.

### 2. Run your own Federation

Once you've had a look around the app, you may decide you want to try this out yourself.

It's important that Federations should be broadly distributed around the world, we hope one day to see millions of Federations deployed in communities across the planet by people like you.  So this repo contains a custom build of the latest Fedimint code that will allow you to setup an alpha federation using a pre-packaged docker images. 

The Fedi team can often be found hanging out and helping out in [the Fedimint Discord](https://discord.gg/Nz6jUj4q), over the course of next you'll find us their hosting deployment parties which we'll record and share to help you through the setup using the [official docker images](https://hub.docker.com/u/fedimint). 

So soon this will get even easier as we are working with several partners to bring 1-click installs to enthusiasts everywhere.

### 3. Contribute to Fedimint and Build out your own modules

The Fedimint COmmunity The Fedi app is designed to be extensible and interoperable with the best of Bitcoin. 

We use open standards to allow you to write your own applications that work with the Fedi app. 

Accounts are managed from your key (via LNURL-Auth), restore your wallet and restore access to every site you have an account on. 

Need to send or withdraw to the wallet, just use simple WebLN integration to move money to your favorite sites.

More than this, Fedimint is a modular open source protocol. 

You can write any consensus application or any smart contract you want in Rust and run it right there in the fedimint. Simple, Scalable and Safe. 

Check out some examples from the [Fedi and Epoch VC hackathon from January 2023](https://www.fedi.xyz/blog/fedimint-hackaton-winners).

To get started with development you can launch a ready to go developer environment on clovyr.

![clovyr_Logo_300](https://github.com/fedibtc/fedi-alpha/assets/42595944/279505fc-4d2c-419b-a178-62915d4f044f)

1-click developer setup with Clovyr

As always though, if you'd prefer to get into the details, please join us on [the Fedimint Discord](https://discord.gg/Nz6jUj4q) to learn more about setting up your developer environment through Nix or head to the [introduction for contributors](https://github.com/fedibtc/fedimint-fedi/blob/master/docs/contributing.md)

We'll also be running a series of webinars, workshops and tutorials which we'll be sharing through the website [fedi.xyz/builders](https://fedi.xyz/builders).

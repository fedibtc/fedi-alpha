# Fedi Alpha - Fedimint Modules

Fedi Alpha, powered by Fedimint.

Fedi is the world's first glimpse of a Federated OS, home for your money, chat, and data. Fedi Alpha is an exclusive version for builders, developers, and pioneers. 

Federated OS is the technology that lets individuals collaborate through Federations to take control of their money, their data, and their digital lives while protecting user privacy and autonomy.

Fedimint is a modular open source protocol to custody and transact bitcoin in a community context, built on a strong foundation of privacy.

Federations are a set of one or (usually) more fedimint servers working collaboratively, each run by an independent guardian. 

In this repo we have packaged a custom build of Fedimint that will help you set up your own federations and connect using Fedi Alpha.

## 1. Run your own Federation

It's important that Federations should be broadly distributed around the world. We hope one day to see millions of Federations deployed in communities across the planet by people like you. So this repo contains a custom build of the latest Fedimint code that will allow you to set up a Federation using pre-packaged docker images.

The Fedi team can often be found hanging out and helping out in [the Fedimint Discord](https://discord.gg/Nz6jUj4q), over the course of the next month you'll find us hosting deployment parties which we'll record and share to help you through the setup using the [official docker images](https://hub.docker.com/u/fedimint).

We are working with several partners to bring 1-click installs to enthusiasts everywhere, so stay tuned!

## 2. Contribute to Fedimint and Build out your own modules

The Fedimint Community has experienced significant growth in the past year, but there are still plenty of exciting opportunities to get involved. From managing and automating lightning gateways to building out new modules, documentation and contributing to the core consensus code, Fedimint is an open source protocol that allows you to make a difference while also benefiting from the project's advancements.

With fedimints, you have the freedom to execute any Rust-based smart contract within the Fedimint ecosystem.

Early this year (January 2023) [Fedi and Epoch VC sposnosed a fedimint module hackathon](https://www.fedi.xyz/blog/fedimint-hackaton-winners) to show what could be done. This sparked a wave of ideas in the communtiy such as [Fedipools](https://www.discreetlog.com/fedipool/) and [Stabilty Pools](https://thebitcoinmanual.com/articles/fedimint-stability-pool/). 

If you need more inspiration you can also [check out the dsicussion boards on fedimint github!](https://github.com/fedimint/fedimint/discussions)

Get ready to jump right in and have hands-on experience! Recently we've been touring giving module development workshops using a[1-click developer setup with Clovyr](https://clovyr.app/instant/code-fedimint) to get a development environment setup.

<a href="https://clovyr.app/instant/code-fedimint" target="_blank"><picture><img src="https://github.com/fedibtc/fedi-alpha/assets/42595944/279505fc-4d2c-419b-a178-62915d4f044f"></picture></a>

As always though, if you'd prefer to get into the details, please join us on [the Fedimint Discord](https://discord.gg/Nz6jUj4q) to learn more about setting up your developer environment through Nix or head to the [introduction for contributors](https://github.com/fedibtc/fedimint-fedi/blob/master/docs/contributing.md).

We'll also be running a series of webinars, workshops and tutorials which we'll be sharing through the website [fedi.xyz/builders](https://fedi.xyz/builders).

## 3. Try out Fedi

The simplest way to understand a fedimint is to use one!

<p float="left">
  <a href="https://testflight.apple.com/v1/app/6444390789?build=112780359" target="_blank"><picture><img src="https://github.com/fedibtc/fedi-alpha/assets/42595944/3ca2c7bc-1278-467a-94f8-da775851bbdd" height="90"></picture></a>
  <a href="https://play.google.com/store/apps/details?id=com.fedimintreactnative&pli=1" target="_blank"><picture><img src="https://github.com/fedibtc/fedi-alpha/assets/42595944/7145aa21-cb2b-432b-878c-a6b863f1a779" height="90"></picture></a>
</p>


Don't like app stores - no problem try [out an this apk](https://github.com/fedibtc/fedi-alpha/releases) or our [Progressive Web App](https://app.fedi.xyz). 

Whilst we've been zapping eCash around the planet and funding geyser campaigns with for little while now, we recognise that nothing gets an idea across like first hand use. To make this easy we have deployed a public federation to the [MutinyNet bitcoin signet](https://blog.mutinywallet.com/mutinynet/).  

We love the mision of Mutinynet for experimentation and testing long run lightning enabled apps in a more real world environment , we hope to see many more apps and mods deploying test instances here soon - let us know if you join and maybe we can add you to Fedi!

Once you've got the app, you'll want to connect to a federation and get setup with some signet satoshis, just head to [alpha.fedi.xyz](https://alpha.fedi.xyz) to get started.

<a href="https://alpha.fedi.xyz" target="_blank"><picture>![Fedi Faucet Preview](https://github.com/fedibtc/fedi-alpha/assets/42595944/60a53bdb-3236-40fa-a835-ef8d682ce8da)</picture></a>

> Please be aware that Fedi Alpha operates on a signet Federation, where all the Sats/Bitcoin within this federation, including the faucet website associated with it, hold no monetary value and are solely intended for testing purposes.
>
> We strongly advise against using this version of the app for any significant financial transactions as there is a risk of loss. It is important to note that Fedi assumes no responsibility for any loss or use of the test version of the app and web app.

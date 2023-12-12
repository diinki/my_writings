# Decentralized Interfaces

A wallet for a blockchain doesn't actually "store" any funds or assets, it simply acts
as an interface to the network that it's connected to.

The biggest pitfalls of wallets these days come twofold:

1. The RPC node the wallet is connected to is usually centralized: The wallet sends
   transactions to an RPC service which proceeds to broadcast it to the blockchain,
   it is entirely possible that this RPC service could track and/or censor the user,
   or even give false RPC responses.
2. The user isn't using a secure offline hardware-wallet to secure their seed-phrase, of which all the
   keypairs are derived. In order to keep the seed-phrase safe, it must never touch any machine
   that's connected to the internet, and should never be shared with anyone. Some individuals
   aren't aware of the importance a simple 24 word seed-phrase _(mnemonic phrase)_ has.

Problem `1` is an engineering problem which isn't impossible to solve at all, it actually has already been
solved to an extent; the user could run their own node and use that node as an RPC endpoint, connecting
their wallet to said node. There also does exist services which aim to provide more open & decentralized
RPC endpoints....

Problem `2` is mainly an education problem as I see it. There should be larger emphasis on
teaching new users of decentralized platforms about the basics & how they can stay secure, self-custody comes with a larger set of responsibilities
which should be instantly made clear to the user. This isn't a draw-back, it's the entire point...

There are some services which are centralized that are widely used, which **shouldn't** be used _imo_, for instance: Opensea is a lazy solution
to digital art which is centralized and _arguably_ pointless. RPC services such as Infura, Non self-custodial or closed-source wallets, and
centralized services built with the illusion of censorship resistance are lazy and a risk, it should be made clear what they actually are and what
they aren't.

The standard "Web 2" way of doing things is quite painful, when I build some web-app with Js 'n'
friends it feels as if I'm building software ontop of crumbling & unoptimized foundations.

Ontop of all that we see some large monopolies in control of a large portion of all Web 2.0
services, whether it's hosting solutions or social media.

My point is that we should not resort to lazy solutions which in the end might resolve to the
same outcome to the mess that "Web 2" has become.

Decentralization is extremely important, and interfaces to the Decentralized applications should be open-source, non-custodial, and should be easy-to-use in a way that
doesn't compromise privacy & security.

<h2 id="distributed_services">Distributed Services</h2>

Let's imagine a protocol that attempts to create a distributed & decentralized RPC service.

It's free for the users, the people running the RPC nodes do it simply because the cost of
running the node is worth having a decentralized solution to access decentralized networks for.

A wallet can send a transaction, and gather "receipts" from multiple nodes, making sure that
all RPC nodes return the same value.

Networking could be done through tor creating a veil of anonymity.

This isn't a bullet proof solution yet, but it's a good basis for what seems to already be
better than the majority of the services currently being used.

One could implement more robust proofs ontop of this, or further adding incentives for RPC
node operators to remain honest, as well as incentives for running a node; it's just important
that these solutions are sustainable.

I do believe plenty of people would run these nodes for the common good, it adds a good buffer
between users that want to run their own node, and users that want to _not_ do that but still
use a service that keeps anonymity and remains censorship resistant.

<h2 id="vulture_wallet">Vulture Wallet</h2>

### Note:

Vulture is now deprecated software.

My goal for Vulture wallet is to create a wallet that I personally want to use, I've been
thinking quite a lot before each decision in development, but the most important set of
features that I will prioritize for Vulture will be:

- Open-source & Non-custodial, forever
- Use of **decentralized** & sustainable RPC services
- Easy-to-use Hardware wallet support
- Multi-chain
- Sleek and informative UI

I want vulture to become an unstoppable interface for decentralized ledgers; no company,
government, or person should be able to stop someone from using Vulture to access
and use a decentralized system, and remember:

Finance is only one application, many systems which are centralized today should and
probably will be decentralized: governance, social media, etc.

I hope that by the end of this year _(2022 :p)_ I can write about all the advancements in
the space, as well as my implementations of some solutions; creating decentralized applications for decentralized systems.

## End

If you are a Web 3.0 developer, don't be lazy; don't resort to centralized solutions when
developing decentralized applications.

Cya

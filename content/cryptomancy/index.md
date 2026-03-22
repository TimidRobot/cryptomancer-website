+++
title = "Cryptomancy"
+++

## Shards and Shardnets

![Shard use illustration](/img/shards.jpg)

Shards are magical gems that allow mortals to interact with the Shardscape.
Think of them as mobile endpoints, like smart phones. Small shards that are
split from a single, larger shard form a shardnet: a private network where each
mortal holding one of these shards can communicate with each other silently and
instantly, regardless of the distance between them. However, each shardnet
operates as if each of the endpoints were connected by a hub. That means that
everyone using the shardnet can see everyone else’s communications. Achieving
privacy and security over a shardnet requires cryptomancy.


## Clear-Text Messages

![Alice](/img/alice.jpg) | Alice holds a shard and thinks the message: "Hello, Bob."
--- | ---
![Bob](/img/bob.jpg) | Bob, holding a shard, sees the message: "Hello, Bob."
![Chuck](/img/chuck.jpg ) | Chuck, an eavesdropper, holds a shard and sees the message: "Hello, Bob."

Alice, Bob, and Chuck are part of the same shardnet. If Alice holds her shard,
closes her eyes, and thinks “Hello Bob,” that message will echo throughout the
shardnet in clear-text (that is, language that is perfectly legible to anyone
and everyone). This means that anyone with one of the shards will be able to
intercept the message. Though Alice intended her message to be received by Bob,
Chuck was also able to receive the message. That might be OK if the message is
“Hello Bob.” However, if the message is “Watch out, Chuck is working for the
enemy,” this might be problematic.


## Encrypted Messages

![Alice injecting key](/img/alice_hand.jpg) | Alice holds a shard, raises her other hand, and injects the key phrase: "Gallows Goblets Gold."
------------------------ | ---
![Alice](/img/alice.jpg) | She then lowers her hand, and thinks her message: "Hello Bob."
![Chuck](/img/bob.jpg) | Bob, who knows the keyphrase "Gallows Goblets Gold" sees the message: "Hello, Bob."
![Bob](/img/chuck.jpg) | Chuck, who does not know the keyphrase, sees only jumbled cypher-text

Luckily, Alice and Bob previously agreed on a shared keyphrase... a string of
words that encrypt the clear-text into cipher-text (that is, unintelligible
nonsense). The cipher-text can only be decrypted (transformed back into
clear-text) by someone who knows this keyphrase. Alice raises her hand to her
shard and thinks the keyphrase. She then lowers her hand, and thinks the
message “Watch out, Chuck is working for the enemy.” Bob, who knows the
keyphrase, receives the message loud and clear. Chuck, however, only receives
confusing cipher-text. He now knows that Alice and Bob are keeping a secret
from him, but does not know what that secret is.


## Network Warfare

This very simple example is just the beginning.

Cryptomancer’s fantasy infrastructure is easily taught to players with no IT
background, but complex enough to provide even seasoned security-heads a
playground to test their offensive and defensive chops. The game's
infrastructure sections cover the following:

- Symmetric and asymmetric encryption schemes to ensure privacy, verify one’s
  identity, and securely exchange keyphrases over hostile networks full of
  eavesdroppers.
- A public shardnet that functions like the Internet: a vast fount of
  knowledge, a gathering ground for distributed communities, and a veritable
  warzone.
- Industrial control systems composed of cryptogears receiving instructions
  from remote administrators, and steam-powered automata serving as firewalls
  and proxies between hostile shardnets.
- Techniques to enumerate shardnets, investigate breaches, geolocate users,
  scry through shards (as if they were IP cameras), and more.

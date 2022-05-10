# Awesome Zeronet

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An Awesome & curated list of [ZeroNet](https://en.wikipedia.org/wiki/ZeroNet) implementations, plugins, tools, and zites.

> ZeroNet is a decentralized web-like network of peer-to-peer users.

# Contents

- [Awesome Zeronet](#awesome-zeronet)
  - [Zites](#zites)
    - [Search Engine](#search-engine)
      - [Zite Indexes](#zite-indexes)
    - [Communication](communication)
      - [Chat](#chat)
      - [Froums](#froums)
      - [Mail](#mail)
      - [Social Media](#social)
    - [Movies](#movies)
    - [ID Providers](#id-providers)
    - [Productivity](#productivity)
    - [Block lists](#block-lists)
  - [Implementations](#implementations)
    - [Python](#python)
    - [Rust](#rust)
    - [Go](#go)
    - [Javascript](#javascript)
    - [Android Clients](#android-clients)
  - [Plugins](#plugins)
  - [Guides And Documentations](#guides-and-documentations)
    - [Installation](#installation)
    - [Site Development](#site-development)
- [License](#license)

## Zites

> Zite is shortened version of ZeroNet Site.

### Search Engine

| Name | Address | Domain Name | Description | Active Maintenance |
|:---- | :---: | :---: | :--- | :---: |
| Kaffine Search | `1Mr5rX9TauvaGReB4RjCaE6D37FJQaY5Ba` | N/A | Caffeinated Search & Index | :heavy_check_mark: |
| Zoogle Zearch | `13EYKqmPpwzBU4iaQq9Y4vfVMgj8dHeLkc` | N/A | Google Search for ZeroNet | :heavy_check_mark: |
| Dream Search | `1JBFNPrAGp1nQX6RsAN6oRqCfvtoeWoion` | N/A | Dream Search - The most data scanning search engine in ZeroNet | :heavy_check_mark: |

#### Zite Indexes

| Name | Address | Domain Name | Description | Active Maintenance |
|:---- | :---: | :---: | :--- | :---: |
| ZeroSites | `1SiTEs2D3rCBxeMoLHXei2UYqFcxctdwB` | `Sites.ZeroNetwork.bit` | Sites of ZeroNet | :heavy_multiplication_x: |
| ZeroSitesX | `1SitesVCdgNfHojzf2aGKQrD4dteAZR1k` | `Sites.ZeroNetX.bit` | Sites of ZeroNetX | :heavy_check_mark: |

### Communication

#### Chat

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| ZeroChat | `1AvF5TpcaamRNtqvN1cnDEWzNmUtD47Npg` | N/A | Original ZeroChat | :heavy_multiplication_x: |
| ThunderWave | `1CWkZv7fQAKxTVjZVrLZ8VHcrN6YGGcdky` | N/A | A beautiful chat for ZeroNet | :heavy_multiplication_x: |
| ZeroMedia | `12qKywomfW5Hj5sQPYTH9wFQVrWzgaJj66` | `zeromedia.bit` | Decentralized chat-room | :heavy_multiplication_x: |

#### Froums
 
| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| ZeroTalk | `1TaLkFrMwvbNsooF4ioKAY9EuxTBTjipT` | `talk.zeronetwork.bit` | Decentralized forum with ZeroID | :heavy_multiplication_x: |
| The All-Night Bookstore and Cafe | `13gLfTixjjktySEGHBMnmrQu4qMJpoRuXw` | N/A | A Friendly Local Forum | :heavy_check_mark: |
| UnlimitTalk | `1HMLvnRWViMnuvZc5LK4Dm86sZNcSH1jdh` | N/A | For those who are cramped in ZeroTalk limits | :heavy_check_mark: |
| ThreadIt | `15UYrA7aXr2Nto1Gg4yWXpY3EAJwafMTNk` | `ThreadIt.bit` | Decentralized Forum from ZeroNetX Team | :heavy_check_mark: |
| NetTalk | `1LfvE91ZF18jdG3wW62Dw7NtfTZh737KPL` | N/A | Discussion about interne…s and other electronics | :heavy_check_mark: |

#### Mail

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| ZeroMail | `1MaiL5gfBM1cyb4a8e3iiL8L5gXmoAJu27` | `mail.zeronetwork.bit` | End-to-end encrypted messaging | :heavy_multiplication_x: |
| ZeroMailX | `1MaiLX6j5MSddyu8oh5CxxGrhMcSmRo6N8` | `Mail.ZeroNetX.bit` | End-to-end encrypted messaging | :heavy_check_mark: |

#### Social Media

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| ZeroMe | `1MeFqFfFFGQfa1J3gJyYYUvb5Lksczq7nH` | `me.zeronetwork.bit` | Twitter-like social media | :heavy_multiplication_x: |
| Sakana | `1SAkaNabHzB8ovdGXxfEbmfdWkJ6ay3yt` | `sakana.bit` | An alternative frontend to ZeroMe | :heavy_multiplication_x: |

### Movies

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| Play | `1PLAYgDQboKojowD3kwdb3CtWmWaokXvfp` | `0play.bit` | Movie torrents | :heavy_check_mark: |

### ID Providers

| Name | Address | Domain Name | UniqueIDs | Centralized | Description | Active Maintenance |
| :--- | :---: | :---: | :---: | :---: | :--- | :---: |
| ZeroId | `1iD5ZQJMNXu43w1qLB8sfdHVKppVMduGz` | `zeroid.bit` | :heavy_check_mark: | :heavy_check_mark: | Sample trusted authorization provider | :heavy_multiplication_x: |
| CryptoId | `1oWoUktrXo1p6vkviJUyNXkGHyWznTtRH` | `cryptoid.bit` | :heavy_multiplication_x: | :heavy_multiplication_x: | Decentralized ID provider | :heavy_multiplication_x: |
| KaffieId | `1K3tM7irQqSX4Hx3JvNgkimkQzY6jPtBfz` | `kaffie.bit` | :heavy_multiplication_x: | :heavy_multiplication_x: | Decentralized ID provider | :heavy_check_mark: |
| Id@ZeroVerse | `1HPgDoReCFtE9qy71hnp55ksBVvV1gHJLQ` | `zeroverse.bit` | :heavy_check_mark: | :heavy_multiplication_x: | A trusted authorization provider without a central server **Note: ZeroVerse seems to be not working anymore** | :heavy_multiplication_x: |
| KxoId | `1GTVetvjTEriCMzKzWSP9FahYoMPy6BG1P` | `kxonet.bit` | :heavy_check_mark: | :heavy_multiplication_x: | Semi-centralized id provider **Note: KxoId is not working anymore** | :heavy_multiplication_x: |

### Productivity

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| ZeroTodos | `1B8LmXYHzMGZzcRWoidAQb5SmKSyfjN63f` | N/A | Encrypted ToDo App | :heavy_multiplication_x: |
| NullPaste | `1MgHVPCE1ve6QfKrgsqCURzRj72HrRWioz` | N/A | Decentralized paste-bin | :heavy_multiplication_x: |

### Block lists

| Name | Address | Domain Name | Description | Active Maintenance |
| :--- | :---: | :---: | :--- | :---: |
| Privact blocklist | `18zoKfKYPnVBuHtKpK1mhAuVsWXV72obA1` | N/A | Blocks websites with external files | :heavy_check_mark: |
| Kaffie's Spamlist | `1CufK1ZtvekbFXEpSyKT2gDjf9jnqW8KwG` | N/A | Mute/ban list for spammers | :heavy_check_mark: |

## Implementations

### Python

| Repo Url | Fork | Description | Active Maintenance |
| :--- | :---: | :--- | :---: |
| https://github.com/HelloZeroNet/ZeroNet/ | :heavy_multiplication_x: | The Original ZeroNet | :heavy_multiplication_x: |
| https://github.com/ZeroNetX/ZeroNet | :heavy_check_mark: | A fork of ZeroNet with HiddenService v3 support | :heavy_check_mark: |

### Rust

| Repo Url | Description | Active Maintenance |
| :--- | :--- | :---: |
| https://github.com/canewsin/zerunet | Rust Implementation of zeronet. Note: **This project is not completed yet** | :heavy_check_mark: |
| https://github.com/canewsin/zeronet-rs | Rust Implementation of ZeroNet Core. Note: **This project is not completed yet** | :heavy_check_mark: |

### Go

| Repo Url | Description | Active Maintenance |
| :--- | :--- | :---: |
| https://github.com/G1itchZero/ZeroGo | Very basic ZeroNet client implementation | :heavy_multiplication_x: |

### Javascript

| Repo Url | Description | Active Maintenance |
| :--- | :--- | :---: |
| https://github.com/ZeroNetJS/zeronet-js | A JS version of ZeroNet, using libp2p | :heavy_multiplication_x: |

### Android Clients

| Repo Url | Description | Active Maintenance |
| :--- | :--- | :---: |
| https://github.com/HelloZeroNet/ZeroNet-kivy | A simple android client for ZeroNet | :heavy_multiplication_x: |
| https://github.com/ZeroNetX/zeronet_mobile | ZeroNet Mobile is an Native Client for Mobile Devices running Android | :heavy_check_mark: |

## Plugins

| Name | Url | Description | Active Maintenance |
| :--- | :--- | :--- | :---: |
| PeerMessage Plugin | https://github.com/HelloZeroNet/Plugin-PeerMessage | It enables peer-to-peer communication via messages by extending ZeroFrame API and peer API. | :heavy_multiplication_x: |
| Name.Yo Plugin | https://github.com/ZeroNetX/Plugin-NameYo | Centralized Domain Names for zeronet | :heavy_check_mark: | 

## Guides and Documentations

### Installation

| Description | Url |
| :--- | :--- |
| Original ZeroNet installation guide **Note: Original ZeroNet is not maintained anymore** | https://github.com/HelloZeroNet/ZeroNet#how-to-join |
| ZeroNetX installation guide | https://github.com/ZeroNetX/ZeroNet#how-to-join |

### Site Development

| Description | Url |
| :--- | :--- |
| Original ZeroNet's guide on site development | https://zeronet.io/docs/site_development/getting_started/ |
| The Truth about ZeroNet by [imachug](https://github.com/imachug) | https://github.com/imachug/The-Truth-about-ZeroNet |
| How to build a decentralized chatroom in ZeroNet | http://127.0.0.1:43110/Blog.ZeroNetwork.bit/?Post:99:ZeroChat+tutorial ([mirror](https://zerolink.ml/Blog.ZeroNetwork.bit/?Post:99:ZeroChat+tutorial)) |

# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

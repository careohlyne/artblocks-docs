---
Order: 600
description: Frequently asked questions.
---

# FAQs

To suggest a question be added, fill out this form: [Creator FAQs Suggestion Box](https://forms.gle/P3TJcZ8ydqFmMyiw9)

## Application

### How do I apply?

There are two steps. First, submit an application at https://artblocks.io/apply. Artists will receive a project shell on our staging site. Artists upload their project to Art Blocks for review via this project shell. Only the wallet address connected to Art Blocks will have access to the project shell when applying. Second, once a project is ready to be reviewed, please email apply@artblocks.io with a link to the staging shell.

### How do I publish my generative art project on Art Blocks?

Art Blocks has a selective application process. The application form can be found here: 
[artblocks.io/apply](https://www.artblocks.io/apply)

Upon application, artists automatically receive a staging shell on the Art Blocks staging site accessible with the wallet they provide. This staging shell is where artists upload their projects for screening.

### Once I’m ready to have my project reviewed, how do I notify Art Blocks?

Please email apply@artblocks.io with a link to the staging shell. Before screening, ensure the work has a project description detailing the work's technical, aesthetic, and conceptual approaches. Applications should include 20-40 test outputs, as well as feature traits. If an artist has an individual website and/or has created an external website to accompany the project, link them in the “artist site” field on the project page.

### After I submit my application, when can I expect to hear back?

Project screening can take several weeks. Art Blocks will notify artists of the decision via email.

### Will I be notified if my project is not selected?

Yes, artists will be notified whether their project was accepted or rejected.

### If I change my mind about the collection I’d like to submit, can I just change it in my current project shell, or should I re-apply?

Artists can make as many changes to their staging shell as they’d like, prior to notifying apply@artblocks.io that a project is ready for screening. Artists will not be able to delete mints but rather will upload a new script and then can refresh to have existing mints reflect the updated script.

After submitting a project, artists are required to take a two-month “cool down” period between project submissions. Artists may only release one Curated project every six months. Artists can then reuse their staging shell for future project submissions by selecting the “Refresh Renders” button in the right-hand column under “Management.” 

### What happens after I apply?

The Art Blocks team will provide artists with a timeline as to when their project will be reviewed and when they will be notified whether their project was selected for an Art Blocks release. Please note, Art Blocks accepts less than 10% of projects submitted for release.

Once artists have applied, they will have access to a staging shell on testnet. There, they can upload their generative script and mint test outputs. Prototypes should have 20-40 mints, a project description, and feature traits. They should also include an artist profile and links to any ancillary material about the work on the project page. When they’re ready to proceed to the screening stage, email apply@artblocks.io with a link to the staging shell. All prototypes should be completely finished before review. 

### How do I know the application period to send my first work?

Applications will remain open indefinitely. To learn more about the application process, visit [artblocks.io/apply](artblocks.io/apply). 

### What is the process for submitting my first work?

Artists may apply using [this application form](artblocks.io/apply). 

### I received a link to upload my prototype, but it's not working; what should I do? 

Artists should first clear their cache and ensure they are connected to the wallet they applied with. They will also need to be on the Goerli test network. 

## What is the Art Blocks Marketplace?

Art Blocks Marketplace is a secondary sales marketplace for projects that were originally minted on Art Blocks. We created it as a way to ensure a safe, secure, authentic and pro-artist secondary sales experience for collectors. Read more about it [here](https://www.artblocks.io/info/spectrum/art-blocks-secondary-market].

## Staging 

### Is it possible to see my project without being connected to my wallet? So I can test it across different devices and browsers without connecting?

No, this is not possible. Artis need to be signed in with their wallet to access their project. It is possible however to view liveview links without being connected to a wallet. 

### What is the MinterSuite, and how does it work? 

The MinterSuite allows artists to set specific minting contracts on a per-project basis. The MinterSuite includes the following minter options:

**Set Price - ETH** is used for fixed price releases.

**Automated Exponential Dutch Auction**: For exponential Dutch auctions, artists specify the starting price, ending price, and the half-life for price drops.

**Automated Linear Dutch Auction:** For linear Dutch auctions, artists will specify the starting price, ending price, starting time, and ending time of the auction. The price will then gradually decrease each block over the total auction time.

**Dutch Auction (w/ settlement):** All collectors pay the same net price, determined by the last buyer during the auction. If any tokens remain unsold at the end of the auction, all collectors will pay the resting price. This is typically the most fair and equitable Dutch auction type as all buyers pay the same price, making it the recommended auction type for most projects.

Collectors who purchase above the lowest price will be able to claim a settlement after the auction. The settlement will be the difference between the price they purchased at and the last purchase price. All funds are held non-custodially by the smart contract until the auction ends and revenues are collected by the artist.

**Set price in custom ERC20:** Set price in ERC20 is a fixed price for a sale with a custom token. Artists will specify the address for the custom token sale. 

**Set Price - ETH, Allowlisted Users Only (V1)** these are addresses that are allowed to mint as many times as they want until they reach the mint limit (artists sets mint/wallet)

To find out how to set the project price using the MinterSuite visit [this page](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/project-form-fields-guide/#minter). 

### The documentation states that only one external library can be used, and then there is a list of some libraries. Can I use a library (e.g., game engine) that is not on that list? 

If the library is on the list, it is compatible. Here is a [full list](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/#limited-dependencies) of platform compatible limited dependencies.

### I have opened my shell on the staging site but cannot upload test mints of my prototype. 

Artists must first upload their prototype script and then mint test outputs. Learn how to mint without unpausing a project here: https://docs.artblocks.io/creator-docs/creator-onboarding/testnet-checklist/#test-minting

### Is it possible to create a project on the site without a library code?

Yes, it is possible to create a project without a library. Read more [here]( https://docs.artblocks.io/creator-docs/creator-onboarding/readme/#limited-dependencies)

All Art Blocks work is completely on-chain. Artists must upload their technically-compatible project scripts to their staging shell to produce a collection. All projects must use the limited dependencies outlined in our Creator Documentation: https://docs.artblocks.io/creator-docs/creator-onboarding/readme/#limited-dependencies

### Is it possible to host a project based on IPFS, or should everything be generated exclusively on Art Blocks? 

No, it is not possible to host a project on Art Blocks based on IPFS. All projects must be generated via a script uploaded to the Art Blocks platform.

### My script works and is shown in "Explore Possibilities," but my test mints are not showing. The console is showing many NextJs script errors. Could my script be causing this issue?

Artists’ script must be the same version of the [limited dependencies](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/#limited-dependencies) accepted by the platform. 

Consider using this starter template, which provides an environment similar to Art Blocks: https://github.com/ArtBlocks/artblocks-starter-template 

### Where do I add my public files in the staging environment (html, CSS)? 

Art Blocks projects do not contain public files. Artists only need to submit the prototype script, and then can choose a single library in the `script` tab of the `edit project` which will add the container(canvas) and the script import.

### Why are my project’s thumbnails different from the live views?

Renders may need to be refreshed. To do so, select the “Refresh Renders” button in the right-hand column under “Management” on the Creator Dashboard.



### My artwork depends on some deterministic Random function calls, and features depend on it. In the staging environment, the features script is separated from the artwork script. How can I calculate the features? Are there any simpler solutions than rewriting the random calls in the feature script in the same order they are called in the artwork script?

Artists will need to rewrite the random calls in the feature script in the same order they are called in the artwork script. More info [here]( https://docs.artblocks.io/creator-docs/creator-onboarding/readme/features/).

### I set up the features, types, and options in my staging shell, and copied my original code into the `Calculate Features` section, removed all the p5.js drawing, then set it up to build key-value pairs. Right now, I have the key-value pairs being assigned to an object called "features." How do I get the script to return the right object? The code isn't giving me any errors, but no features appear when I look at the mints. 

Artists should have the function return the dictionary with the features iirc, using the syntax `return {object name}`. If the problem still occurs, clear the cache. There may also be an authentication issue, so log out and back into the wallet. 

### Can I visually verify my code is working properly through the Art Blocks staging platform?

If test outputs can be minted successfully, the script will likely be compatible with the platform. Technical documentation can be reviewed here: https://docs.artblocks.io/creator-docs/creator-onboarding/readme/#documentation

### Where is the mint button? 
Learn how to mint without unpausing a `project here: 
For more information, visit [#test-minting]( https://docs.artblocks.io/creator-docs/creator-onboarding/testnet-checklist/#test-minting)

### Do we have to set a price? 
Yes, prices must be set prior to release. Go to [Project Pricing Model](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/project-pricing-model/) for further information.



## Artist Pipeline 

### What are the steps to release my project and how do I know when I've completed them?

Please see [Artist Onboarding Steps](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/artist-onboarding-steps/) for a more detailed overview of the onboarding process. The Art Team will stay in contact via the Discord Artist DM about the timeline and next steps before a project is ready for release.

### Approximately how long will each step of the process take?

Once a project is accepted for release, it takes approximately 1-2 months to finalize a project on testnet, upload the script onto mainnet, schedule a launch date, and release the project. The length of each step differs and depends somewhat on how quickly artists finalize their scripts. Please see our [Artist Onboarding Steps](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/artist-onboarding-steps/) for more information about the timeline of each step.

### What  should I do if I have additional questions?

For questions related to an application, please post in #artist-applications or #help channel.

## Curation Review 

### What are the general standards for achieving curation status? 

The Curated collection includes projects that have been selected by Art Blocks’ Curation Board for their world-class innovation, technical rigor, and aesthetic beauty. They cover new territory using code that employs inventive, never-before-seen techniques to support an original intention and concept. Board members look for collections that evoke emotional, intellectual, and conceptual qualities through aesthetics while sustaining the viewer’s interest.

### Are rarities judged as a metric for curation?

Rarities are not included as a metric for determining curation status. However, the overall variety of a collection is important so that the project contains diversity across a large number of mints.

### Will I receive feedback from the Curation Board on my submissions?

Feedback from the Curation Board will be provided. The goal of this feedback will be to highlight observations that the Curation Board made about the submitted project.

### Who is on the Curation Board?

Art Blocks has invited individuals to our Curation Board based on their expertise, passion for the evolution and growth of on-chain generative art, as well as their industry leadership.

Read more about the Curation Board [here](https://info.artblocks.io/spectrum/meet-the-art-blocks-curation-board).

## Technical Requirements

### Are all browsers supported for Art Blocks releases? Is mobile supported?

All modern browsers are supported (including mobile), though Internet Explorer may cause issues. We recommend using [Browserstack] (https://www.browserstack.com/) to test across devices.

### Do I need to know Solidity (to write my own smart contract)?

No. Art Blocks handles the smart contract.

### Can I load external assets into my project (textures, audio, etc)?

No. Everything must be included in the script file. For small and critical assets, artists may be able to use `base-64` encoding to encode the asset into their script, but that will count as data to be stored.

### Can I use text? What fonts can I use?

Yes, artists can use text in their project. Font choice is technically at their discretion, but artists are encouraged to embed them in their scripts directly or use the core web fonts to ensure universal support and maintain the piece's integrity over the longer term. (`serif,` `sans-serif,` `monospace`, and less commonly, `cursive` and `fantasy.`)

### What are the minimum hardware requirements? What type of graphics card do I need?

Artists can upload their project from any computer with an internet connection. No special graphics cards are required.

## Uploading Your Script to Mainnet

### How much money / ETH do I need to upload my project?

The cost depends on the complexity of a project and how many lines of code it requires. See [here](readme.md#cost) for more specific information about how to budget for a release.

### My project is uploaded and ready to go. How do I mint my first output?

Artists can use the “Artist Mint” button to mint both on the artist staging platform and mainnet _**without**_ unpausing their project. We suggest using this method for Mint #0 to avoid any accidental early mints.

### Are there limits on script length?

If a script is especially large, consider minifying it. There are no limits to the total script length. That said, scripts that are larger than 24 kilobytes will need to be broken up into segments of 24kb. Segments can be added from using the "add new segment" button when uploading a script. Be aware that artists will have to pay transaction gas fees proportional to the size of the script upload.

###  Does the size include the library that I'm using?

No, the library artists use is not stored on-chain with their project. A script tag linking to a CDN hosting the library they choose will be injected into the window scope when the project runs.

### Can I share information about my release on social media before it's announced?

Once artists finalize a release date with the Art Blocks team, they are welcome to share and promote their release across social media. We have created a [Marketing  101](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/marketing101/#marketing-101) document to support artists’ efforts in the lead-up to their release.

### When will I know when my release is scheduled? When will the release be announced?

Once an application is approved, it takes approximately 1-2 months to reach a launch date for a project. Artists will work closely with our team to schedule the release date. Projects will be announced in #upcoming-projects in Discord the Thursday prior to their release.

### Can I mint pieces of my own artwork? How many?

All artists on Art Blocks mint at least one initial piece for themselves: Mint #0. In addition, artists have the opportunity to pre-mint #1 directly into the Art Blocks Corporate Collection. If a project is an artist collaboration, artists can each mint one of the first outputs before the project goes live.

For Presents category projects: Please consult with the Art Blocks team via Discord DM about minting more pieces of the collection for gifts or giveaways.

Generative art source code is generally published under permissive copyright licensing, making it often widely available including commercial usage. If your project contains any code not written by you, please inform the Art Blocks team so it’s properly attributed.

###How will my work be licensable? 

Generative art source code is generally published under permissive copyright licensing, making it often widely available including commercial usage. If your project contains any code not written by you, please inform the Art Blocks team so it’s properly attributed.

Artists can decide which source code license to use. Common ones (in creative coding) include:

- [CC BY](https://creativecommons.org/licenses/by/4.0/): The original author and license must be clearly and appropriately stated.
- [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/): As CC BY, but all derivatives must also be licensed under CC BY-SA.
- [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/): As CC BY-SA, but no commercial use is allowed.
- [MIT](https://choosealicense.com/licenses/mit/): similar to CC BY
- [GPL](https://choosealicense.com/licenses/gpl-3.0/): similar to CC BY-SA

There are many other free-to-use licenses commonly used on open source software. Please carefully read the full details on any re-used or modified licensed code before including it in your project.


## Price Mechanics 

### How should I price my artwork?

Once artists’ project is nearly finalized, they’ll be in close dialogue with our team about pricing. We have a [Project Pricing Model](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/project-pricing-model/) that guides the decision on the pricing of Art Blocks collections. 

### How is project revenue shared?

Art Blocks is allotted 30% of total primary sales and 1/3 of total secondary royalties. Artists have the option of donating a percentage of sales to a charity of their choice.

### What percent of secondary sales do artists receive?

Artists should be aware of recent changes in royalty rate determination at OpenSea and Blur, which have resulted in a range of royalty payment percentages (from 0% to 5%). Due to this change, Art Blocks has had to adjust our royalty payout calculations.

Art Blocks has chosen to uphold the same secondary sales split ratio between artists and Art Blocks (2/3 for the artist and 1/3 for Art Blocks). Art Blocks handles the distribution of royalty payments received from marketplaces that do not offer direct splits through the Royalty Registry, following an internal review of secondary sales transactions.

### How can I customize revenue splits?
Setting up revenue splits can be done through the [Payout](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/project-form-fields-guide/#payout) fields in the project form. Artists can use the additional payee field within the form directly to send a portion of the revenue to that account. Many artists use this to make a charitable donation. To split revenue with more than one account, we recommend using [0xSplits](https://www.0xsplits.xyz/). Instructions on how to create a Split can be found [here](https://www.youtube.com/watch?v=P_uqQJghNAo). Once a Split is created, paste the address into the additional payee field. Artists donating to charity often create two splits. In the first split, the charity is included in primary sales, while in the second split, the charity is excluded from secondary sales.

### Do you have access to historical data of other Art Blocks sales? 

A helpful tool for this is:
https://artacle.io/ 

This resource has most Art Blocks projects and will show the distribution of sales for Dutch auctions.

## Charitable Giving 

### What is Art Blocks' commitment to charitable giving?

To maintain our commitment to charitable giving, Art Blocks asks artists to consider donating a portion of artist proceeds to an eligible charity of their choice. Artists can decide where and how they donate, but may want to consider whether the charity can receive tax-deductible donations. We recommend consulting with a tax professional to understand local tax liability. Below answers a number of common questions about how to donate and where to find crypto-friendly charities.


### How can I donate to charity?

Here are a few donation options:

**1)** **On-chain donations through Endaoment.org**

Endaoment is a 501(c)(3) organization that accepts crypto and distributes donations to any US-based 501(c)(3) charity in good standing with the IRS. Donations through Endaoment are set at the contract level and automatically routed at the time of payment without passing through artists’ wallet (potentially avoiding tax liability/deductibility).

Via Endaoment, there are two methods to donate: 

1. Create a fund to donate to multiple charities
2. Donate to one charity directly

To use Endaoment, go to [Endaoment.org](https://endaoment.org), connect a wallet and create a fund. Then, enter the fund's contract address (shown on the newly created fund page) in the additional payee field. Many artists prefer this route so they can support multiple charities with smaller donations rather than a single charity with one large donation, but it’s also possible to set up an organization as an additional payee directly. In this case, go to [Endaoment.org](https://endaoment.org/explore), use their search bar to locate the org in question, and copy the contract address directly from the organization's profile page to the payee field (artists can do this for multiple charities if desired). If the organization(s) shows as 'Not Deployed', simply click 'Deploy' to create a smart contract for that nonprofit. When that process completes, a contract address will populate on the organization's profile page. Please note - Endaoment charges 1.5% to receive, convert, and distribute money to nonprofits.

Here is a tutorial of how to use Endaoment [here](https://www.loom.com/share/822350f1a1c84f25b253cc9e4d2cee38), can find direct support in their Discord server [here](https://discord.gg/endaoment) by creating a ticket in the #🙋｜get․help channel, and can review their documentation [here](https://docs.endaoment.org).



**2)** **Create a second wallet**

To create a second wallet separate from a personal wallet, enter the wallet's address in the additional payee field to collect the total donation amount that will be donated. If using the additional payee field for donations, this field can be cleared before lowering to resting price.

**3)** **Receive funds in your primary wallet**

Artists can receive all funds from a project’s sale in the artist’s primary wallet if preferred, but please communicate the total donations with Art Blocks. Please be aware that receiving money in a personal wallet may incur tax obligations and reduce the total donation amount.

## What has Art Blocks donated to charity in the past?

To learn more about Art Blocks commitment to charitable giving, see our [Charity on Chain: 2021 Wrap-Up](https://medium.com/the-link-art-blocks/charity-on-chain-2021-wrap-up-c69782fa7f4a).

## Security 

### Where can I learn more about best practices for security, including hardware wallets?

We recommend that all users have a hardware wallet that they use to interact with MetaMask.

Learn more about security in the NFT space [here](https://medium.com/the-link-art-blocks/how-to-secure-your-collection-3dca5c073aef) (how to keep your collection safe) and [here](https://medium.com/the-link-art-blocks/avoiding-scams-and-staying-safe-9a6808a4146e) (how to avoid scams).

This [After Dinner Mints episode](https://www.youtube.com/watch?v=u8MK99grAfI) is also dedicated to security.

## Artist Community 

### Is there a place I can connect with other artists and chat?

All artists are added to the artist-exclusive #artist-general channel in Discord, where they can interact with other Art Blocks artists, share projects, and ask questions. We encourage artists to participate in our Discord community. In addition, Art Blocks hosts a weekly [Office Hours](https://calendar.google.com/calendar/u/1?cid=Y192a2RxdWluZ3ZsM2EyMmJudWxxZnFkb2sxOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t). This dedicated time is the place for artists to chat synchronously, meet the Art Blocks team, participate in artist development-focused programming, and group critiques. If a project has been chosen for an Art Blocks Curated release, we will establish a dedicated artist’s Discord channel for them to centralize discussions of that project. For all artists releasing on Art Blocks, the #block-talk channel is a great place to interact with fellow artists, collectors, and community members. 

## Post-Release

### How long do I need to wait before releasing a project through Art Blocks again?

When an artist’s project is 100% minted (i.e. “complete”), the artist is eligible to submit a new project for screening. Please note: there is a six month “cool-off” period after a Curated project is complete before the artist may submit another project for consideration as Curated. 

### Will I have access to my testnet shell after I release my project?

Yes. Please note, as of Aug 2, 2022, Art Blocks switched testing networks from Ropsten to Goerli.

If artists previously had a testnet shell on the Ropsten network, they may still access their project shell using https://ropsten-artist-staging.artblocks.io/ as a read-only set of data. As a returning artists, please write in the artist DM, or in #artist-general. 

### What is the process upon returning to Art Blocks as an artist?

After completing a project, artists will be eligible to submit a new project for screening consideration. Artists will continue to have access to their testnet shell. New projects can be submitted for review via an existing testnet shell. To submit a new project for screening by sending a message via the Artist DM in Discord. 

The first screening determines if a work is accepted onto the platform. A committee made up of Art Blocks' staff and generative art experts conducts this screening. This review focuses on overall aesthetics, mint variety, and the degree to which a project explores new territory technically, visually, and conceptually. Returning artists are still subject to the highly-selective screening process.

If the work is accepted to be released on Art Blocks artists will then move through the same onboarding process as their previous project, which is also outlined [here](https://docs.artblocks.io/creator-docs/creator-onboarding/readme/artist-onboarding-steps/#5-feedback-check).

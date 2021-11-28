<!-- copyright 2020 rug.farm && the contributors -->
<p align="center">
 <img src="https://user-images.githubusercontent.com/82294478/142774471-26598744-8497-420c-a4db-4e4fabb9795c.png" align="right" width="350">
	<h1 align="left">RIPs</h1>
 <h3 align="center"> </h3>
 <p align="center">
<align="center">
 
![Validate](https://github.com/rugenerous/RIPS/workflows/Validate/badge.svg?branch=master) [![Discord](https://img.shields.io/discord/734804446353031319.svg?color=768AD4&label=discord&logo=https%3A%2F%2Fdiscordapp.com%2Fassets%2F8c9701b98ad4372b58f13fd9f65f966e.svg)](https://discord.gg/N5dgz3Nbpz/) [![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/rugenerousfinance) [![Twitter Follow](https://img.shields.io/twitter/follow/iearnfinance.svg?label=iearnfinance&style=social)](https://twitter.com/rugenerous)

- [RIPs](#rips)
  * [Contributing](#contributing)
  * [RIP Statuses](#rip-statuses)
  * [Validation](#validation)
  
[Visit the Governance Proposal Documentation Webpage](https://docs.rug.farm/governance/proposal-repository)
	
**Rugenerous DAO Improvement Proposals (RIPs)** describe standards for the Rugenerous platform, including:

- core protocol specification
- client APIs
- contract standards
- governance operations
- and more 
 
## Contributing

1.  Review [RIP-0](RIPS/rip-0.md).
2.  Fork the repository by clicking "Fork" in the top right.
3.  Add your RIP to your fork of the repository. There is a [template RIP here](rip-X.md).
4.  Submit a Pull Request to Rugenerous's [RIPs repository](https://github.com/iearn-finance/RIPS/).

Your first PR should be a first draft of the final RIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new RIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [gov.rug.farm](https://gov.rug.farm/) where people can discuss the RIP as a whole.

If your RIP requires images, the image files should be included in a subdirectory of the `assets` folder for that RIP as follow: `assets/rip-X` (for rip **X**). When linking to an image in the RIP, use relative links such as `../assets/rip-X/image.png`.

When you believe your RIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the next governance call where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the RIP editors will update the state of your RIP to 'Approved'.

## RIP Statuses

- **WIP** - a RIP that is still being developed.
- **Proposed** - a RIP that is ready to be reviewed in a governance call.
- **Approved** - a RIP that has been accepted for implementation by the Rugenerous community.
- **Implemented** - a RIP that has been released to mainnet.
- **Rejected** - a RIP that has been rejected.
- **Withdrawn** - a RIP that has been withdrawn by the author(s).
- **Deferred** - a RIP that is pending another RIP/some other change that should be bundled with it together.
- **Moribund** - a RIP that was implemented but is now obsolete and requires no explicit replacement.

## Validation

RIPs must pass some validation tests. The RIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer) and [rip_validator](https://rubygems.org/gems/yip_validator).

It is possible to run the RIP validator locally:

```
gem install yip_validator
yip_validator <INPUT_FILES>
```

## RIP Generator

A RIP Generator is available [as a nodejs package here](https://github.com/camdengrieh/generator-rip).

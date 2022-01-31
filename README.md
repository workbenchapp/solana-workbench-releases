# solana-workbench-releases
![](https://avatars.githubusercontent.com/u/94653053?s=200)

Download the Workbench, report issues, and feature requests here.

Solana Workbench is alpha software. It might be a little rough, and we might make breaking changes. Eventually, things will get much more stable.

## Disclaimer

The Crypto Workbench team does not encourage, induce, or sanction the development or deployment of any applications in violation of applicable laws or regulations. Download and use the Cryto Workbench at your own risk.

## Downloads

Downloads are available on the [Releases](https://github.com/workbenchapp/solana-workbench-releases/releases) section.

## Dependencies

Currently, [Docker for Mac/Windows](https://docker.com) is required for the Workbench's local validator functionality to work. Usage of a local validator that you run yourself is also supported. For Windows and x86_64 Macbooks, the Docker validator should work well, but for M1, we recommend using a local validator.

Having the [Anchor](https://github.com/project-serum/anchor) binary available in your `PATH` is also required for the Anchor functionality to work. (We want to port this to Docker, or install it locally for you automatically, to make it more magic eventually)

## Usage

The [demo video](https://www.youtube.com/watch?v=b0V0FcI-upo) is worth a watch to understand how the Workbench is meant to be used. We will get proper docs up eventually.

## FAQ

**How do we make feature requests and report bugs?**

Please file bugs and feature requests in the [Issues](https://github.com/workbenchapp/solana-workbench-releases/issues) section. Your feedback on the product is valued! We are also actively seeking user interviews. If you are willing to hop on a Zoom call (just voice is fine if you're identity sensitive), please email nathan@cryptoworkbench.io as I'd love to set something up with you.

**Why is the code for this not open source?**

First, we'd like to clarify that open source is definitely in our DNA, we want to see as much open source as possible in the ecosystem, and we are building towards an open source release of Workbench at some point. Our experience working with open source in the past has been that being open source from day one can interfere with product development. There are a few contributing factors here:

1. **It increases developer workload.** Even small open source projects start to grow a sizable backlog of issues that need triaging, and ignoring these is easier said than done. Sometimes users in the issues can become grumpy, which is demoralizing to maintainers.
2. **Unmerged PRs can lead to hurt feelings.** Inevitably, differences of opinion tend to crop up. When the project is in its infancy, the risk of these getting nasty is higher, as it hasn't had time to "settle" yet. Instead of making contributors jump through hoops on PRs that might not ever get merged, we want to focus on nailing the core experience.
3. **It makes changing direction difficult.** We want to reserve some space for the project to [break some workflows](https://xkcd.com/1172/). With a small pool of contributors, this is far easier, since fewer people get attached to code that needs to be ripped out.

And, of course, we want to delay the day that people roast us over our code. If you'd like early access to the source code, send an email to nathan@cryptoworkbench.io and we can chat about it.

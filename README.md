# maxforums.org

<img width="3354" height="2382" alt="image" src="https://github.com/user-attachments/assets/34f92509-f220-4d2f-bf90-f3363af2af17" /><br>

## Overview

This repository drives [maxforums.org](https://maxforums.org) and is a 1:1 representation of the static website that GitHub automatically builds, deploys, and hosts through their free [GitHub Pages](https://docs.github.com/en/pages) system.

As of 8 September, 2025, maxforums.org is pointing to a continuation of the [last valid `html`](https://web.archive.org/web/20231205223116/https://www.maxforums.org/) to appear under the Maxforums banner before the domain had been temporarily owned and controlled by a non-community-affiliated third party.

## Architecture

[GitHub Pages](https://docs.github.com/en/pages) uses [Jekyll](https://jekyllrb.com), a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator), to build and deploy changes to the website. Real-time dynamic applications on GitHub Pages are only possible with services, such as with a [Jamstack](https://en.wikipedia.org/wiki/JavaScript_stack#JAMstack) architecture.

This back-end was chosen for its low cost, low latency, developer friendliness, and simple, maintainable, robust, and secure nature that is well suited for static splash pages like what is being served now. As there is currently no functional forum in place, there is currently no need for real-time server-side processing.

## Web Hosting

This site is currently deployed using GitHub Pages based on the latest valid state of this repository. While GitHub Pages functions in this case as a web host, it is distinct in a key way. By design, GitHub does not give users (even enterprise users) direct access to the servers that build and deploy their statically generated websites. GitHub Pages is entirely a black box outside of user-controlled repositories like this one that trigger re-builds when there's a change.

As described in the Architecture section above, since there is no server access, nothing can be installed. It's not possible to run a custom PHP/MySQL server on GitHub Pages for example. For that kind of real-time back-end driven website, another hosting and/or cloud services provider would be required.

For information about storage, bandwidth, rate limits, and restrictions, see [GitHub Pages Limits](https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits) on GitHub Docs.

## Domain

`maxforums.org` DNS records are being managed for free through [CloudFlare](https://www.cloudflare.com/plans/free/). The domain is temporarily registerd with NameBright. There is an [open issue](https://github.com/maxforums/maxforums.org/issues/6) to select a suitable long-term domain registrar.

## Contributing

If you would like to get involved, post your thoughts in the `#maxforums-org` channel of the [Maxforums Discord](https://discord.com/invite/b9Qbqfe) or check out the open [Issues](https://github.com/maxforums/maxforums.org/issues) and open a [Pull Request]([url](https://github.com/maxforums/maxforums.org/pulls)).

If a Pull Request is approved and merged then the changes should be live on the web within minutes.

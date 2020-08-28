A [docusaurus](https://v2.docusaurus.io/) site that powers [docs.getdbt.com](https://docs.getdbt.com/).

## Branching

There are two long-lived branches in this repo:
- `current`: This branch is what is reflected at at [docs.getdbt.com](https://docs.getdbt.com/)
- `next`: This branch represent the next release of dbt, and is deployed [next.docs.getdbt.com](https://next.docs.getdbt.com/)

## Contributing
We welcome contributions from community members to this repo:
- **Fixes**: If you notice an error (there are likely many), use the `Edit this page` button at the bottom of each page to suggest a change. We recommend you contribute small changes directly from the GitHub interface.
- **New documentation**: If you contributed code in [dbt-core](https://github.com/fishtown-analytics/dbt), we encourage you to also write the docs here!
- **Refactors**: At this time, we are unable to support community members who wish to re-write sections of docs.getdbt.com. We hope to change this in the future!

If you are contributing significant changes, it may be worth setting up the repo to run locally, as follows:
1. Ensure node is installed: `brew install node`
2. Clone this repo: `git clone git@github.com:fishtown-analytics/docs.getdbt.com.git`
3. `cd` into the repo: `cd docs.getdbt.com`
3. And then `cd` into the `website` subdirectory: `cd website`
4. Install the required node packages: `npm install`
5. Build the website: `npm start`
6. Before pushing your changes to a branch, check that all links work by using the `make build` script.

You can also check out [this Loom video](https://www.loom.com/share/7037780b86eb4f16953664b8f15f1e21) that I recorded for co-workers — it covers setting up docs.getdbt.com locally, and adding a page with links and images. Heads up — this was very much something I did on the fly, so is not super polished!

## Custom components
Check out [docs.getdbt.com/styles](https://docs.getdbt.com/styles) for examples of different components that can be used in these docs.

You can also use components directly from the [docusaurus library](https://v2.docusaurus.io/docs/markdown-features/).

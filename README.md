# Ceres Improvement Proposals (CIPs)

Ceres Improvement Proposals (CIPs) describe standards for the Ceres platform, including core protocol specifications, client APIs, and contract standards.

**Before you initiate a pull request**.Ideas should be thoroughly discussed prior to opening a pull request, in a GitHub issue in this repository.

This repository tracks the ongoing status of CIPs. It contains:

- [Draft](https://eips.ethereum.org/all#draft) proposals which intend to complete the CIP review process.
- [Last Call](https://eips.ethereum.org/all#last-call) for proposals that may become final (see also [RSS feed](https://eips.ethereum.org/last-call.xml)).
- [Accepted](https://eips.ethereum.org/all#accepted) proposals which are awaiting implementation or deployment by Ceres client developers.
- [Final](https://eips.ethereum.org/all#final) and [Active](https://eips.ethereum.org/all#active) proposals that are recorded.
- The [CIP process](./EIPS/eip-1.md#eip-work-flow) that governs the CIP repository.

Achieving "Final" status in this repository only represents that a proposal has been reviewed for technical accuracy. It is solely the responsibility of the reader to decide whether a proposal will be useful to them.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft CIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your CIP contains either your GitHub username or your email address inside \<triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

## Project Goal

The Ceres Improvement Proposals repository exists as a place to share concrete proposals with potential users of the proposal and the Ethereum community at large.

## Preferred Citation Format

The canonical URL for a EIP that has achieved draft status at any point is at https://eips.ethereum.org/. For example, the canonical URL for EIP-1 is https://eips.ethereum.org/EIPS/eip-1.

# Validation

CIPs must pass some validation tests.  The CIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer) and [eip_validator](https://rubygems.org/gems/eip_validator).

It is possible to run the CIP validator locally:
```sh
gem install cip_validator
cip_validator <INPUT_FILES>
```

# Automerger

The CIP repository contains an "auto merge" feature to ease the workload for EIP editors.  If a change is made via a PR to a draft EIP, then the authors of the EIP can GitHub approve the change to have it auto-merged by the [eip-automerger](https://github.com/eip-automerger/automerger) bot.

# Local development

## Prerequisites

1. Open Terminal.

2. Check whether you have Ruby 2.1.0 or higher installed:

```sh
$ ruby --version
```

3. If you don't have Ruby installed, install Ruby 2.1.0 or higher.

4. Install Bundler:

```sh
$ gem install bundler
```

5. Install dependencies:

```sh
$ bundle install
```

## Build your local Jekyll site

1. Bundle assets and start the server:

```sh
$ bundle exec jekyll serve
```

2. Preview your local Jekyll site in your web browser at `http://localhost:4000`.

More information on Jekyll and GitHub pages [here](https://help.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll).

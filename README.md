<p align="center">
  <a href="https://www.clerk.dev/?utm_source=github&utm_medium=starter_repos&utm_campaign=rails_starter" target="_blank" align="center">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./docs/clerk-logo-light.png">
      <img src="./docs/clerk-logo-light.png" height="64">
    </picture>
  </a>
  <br />
</p>

# Clerk Rails Starter

Official guide on how to add authentication to Rails with Clerk.dev

![Sign up with Clerk.dev](/sign_up.gif)

## Getting started on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/clerkinc/clerk-rails-starter)

Get your `CLERK_PUBLISHABLE_KEY` and `CLERK_SECRET_KEY` environment variables from [Clerk Dashboard](https://dashboard.clerk.dev).

## Getting started locally

1. Fork this repo
2. Clone your fork locally with `git clone`
3. `cd` into your freshly cloned git repo
4. `cp .env.sample .env.local`
5. Find your instance configuration in the [Clerk
   dashboard](https://dashboard.clerk.dev/) and edit your .env.local accordingly
6. Run `bundle install` (you need to have [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [bundler](https://bundler.io/) installed)
7. Run `yarn install` (you need to have [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) and
   [yarn 1](https://classic.yarnpkg.com/en/docs/install) installed)
8. Run the server with `rails s`

## Learn More

To learn more about Clerk.dev take a look at the [official documentation](https://docs.clerk.dev/).

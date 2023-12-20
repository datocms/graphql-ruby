<!--datocms-autoinclude-header start-->
<a href="https://www.datocms.com/"><img src="https://www.datocms.com/images/full_logo.svg" height="60"></a>

👉 [Visit the DatoCMS homepage](https://www.datocms.com) or see [What is DatoCMS?](#what-is-datocms)
<!--datocms-autoinclude-header end-->

# graphql <img src="https://cloud.githubusercontent.com/assets/2231765/9094460/cb43861e-3b66-11e5-9fbf-71066ff3ab13.png" height="40" alt="graphql-ruby"/>

[![Build Status](https://travis-ci.org/rmosolgo/graphql-ruby.svg?branch=master)](https://travis-ci.org/rmosolgo/graphql-ruby)
[![Gem Version](https://badge.fury.io/rb/graphql.svg)](https://rubygems.org/gems/graphql)
[![Code Climate](https://codeclimate.com/github/rmosolgo/graphql-ruby/badges/gpa.svg)](https://codeclimate.com/github/rmosolgo/graphql-ruby)
[![Test Coverage](https://codeclimate.com/github/rmosolgo/graphql-ruby/badges/coverage.svg)](https://codeclimate.com/github/rmosolgo/graphql-ruby)
[![built with love](https://cloud.githubusercontent.com/assets/2231765/6766607/d07992c6-cfc9-11e4-813f-d9240714dd50.png)](https://rmosolgo.github.io/react-badges/)

A Ruby implementation of [GraphQL](https://graphql.org/).

- [Website](https://graphql-ruby.org/)
- [API Documentation](https://www.rubydoc.info/gems/graphql)
- [Newsletter](https://tinyletter.com/graphql-ruby)

## Installation

Install from RubyGems by adding it to your `Gemfile`, then bundling.

```ruby
# Gemfile
gem 'graphql'
```

```
$ bundle install
```

## Getting Started

```
$ rails generate graphql:install
```

After this, you may need to run `bundle install` again, as by default graphiql-rails is added on installation.

Or, see ["Getting Started"](https://graphql-ruby.org/getting_started.html).

## Upgrade

I also sell [GraphQL::Pro](https://graphql.pro) which provides several features on top of the GraphQL runtime, including [Pundit authorization](https://graphql-ruby.org/authorization/pundit_integration), [CanCan authorization](https://graphql-ruby.org/authorization/can_can_integration), [Pusher-based subscriptions](https://graphql-ruby.org/subscriptions/pusher_implementation) and [persisted queries](https://graphql-ruby.org/operation_store/overview). Besides that, Pro customers get email support and an opportunity to support graphql-ruby's development!

## Goals

- Implement the GraphQL spec & support a Relay front end
- Provide idiomatic, plain-Ruby API with similarities to reference implementation where possible
- Support Ruby on Rails and Relay

## Getting Involved

- __Say hi & ask questions__ in the [#ruby channel on Slack](https://graphql-slack.herokuapp.com/) or [on Twitter](https://twitter.com/rmosolgo)!
- __Report bugs__ by posting a description, full stack trace, and all relevant code in a  [GitHub issue](https://github.com/rmosolgo/graphql-ruby/issues).
- __Start hacking__ with the [Development guide](https://graphql-ruby.org/development).

<!--datocms-autoinclude-footer start-->
-----------------
# What is DatoCMS?
<a href="https://www.datocms.com/"><img src="https://www.datocms.com/images/full_logo.svg" height="60"></a>

[DatoCMS](https://www.datocms.com/) is the REST & GraphQL Headless CMS for the modern web.

Trusted by over 25,000 enterprise businesses, agency partners, and individuals across the world, DatoCMS users create online content at scale from a central hub and distribute it via API. We ❤️ our [developers](https://www.datocms.com/team/best-cms-for-developers), [content editors](https://www.datocms.com/team/content-creators) and [marketers](https://www.datocms.com/team/cms-digital-marketing)!

**Quick links:**

- ⚡️ Get started with a [free DatoCMS account](https://dashboard.datocms.com/signup)
- 🔖 Go through the [docs](https://www.datocms.com/docs)
- ⚙️ Get [support from us and the community](https://community.datocms.com/)
- 🆕 Stay up to date on new features and fixes on the [changelog](https://www.datocms.com/product-updates)

**Our featured repos:**
- [datocms/react-datocms](https://github.com/datocms/react-datocms): React helper components for images, Structured Text rendering, and more
- [datocms/js-rest-api-clients](https://github.com/datocms/js-rest-api-clients): Node and browser JavaScript clients for updating and administering your content. For frontend fetches, we recommend using our [GraphQL Content Delivery API](https://www.datocms.com/docs/content-delivery-api) instead.
- [datocms/cli](https://github.com/datocms/cli): Command-line interface that includes our [Contentful importer](https://github.com/datocms/cli/tree/main/packages/cli-plugin-contentful) and [Wordpress importer](https://github.com/datocms/cli/tree/main/packages/cli-plugin-wordpress)
- [datocms/plugins](https://github.com/datocms/plugins): Example plugins we've made that extend the editor/admin dashboard
- [datocms/gatsby-source-datocms](https://github.com/datocms/gatsby-source-datocms): Our Gatsby source plugin to pull data from DatoCMS
- Frontend examples in different frameworks: [Next.js](https://github.com/datocms/nextjs-demo), [Vue](https://github.com/datocms/vue-datocms) and [Nuxt](https://github.com/datocms/nuxtjs-demo), [Svelte](https://github.com/datocms/datocms-svelte) and [SvelteKit](https://github.com/datocms/sveltekit-demo), [Astro](https://github.com/datocms/datocms-astro-blog-demo), [Remix](https://github.com/datocms/remix-example). See [all our starter templates](https://www.datocms.com/marketplace/starters).

Or see [all our public repos](https://github.com/orgs/datocms/repositories?q=&type=public&language=&sort=stargazers)
<!--datocms-autoinclude-footer end-->

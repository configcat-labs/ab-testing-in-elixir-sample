# How to Conduct an A/B Test in Elixir

## [Read the blog post here](https://configcat.com/blog/)

This repository contains the accompanying sample code for the blog article titled 'How to Conduct an A/B Test in Elixir' The application relies on a web-based framework for Elixir called [Pheonix](https://www.phoenixframework.org/) to serve the app through the browser. To conduct the A/B test experiment, I've integrated [ConfigCat feature flags](https://configcat.com) for switching between and deploying each version to the user sample set. Additionally, I've incorporated [Amplitude's data analytics platform](https://amplitude.com/) to track and compare the clicks from each version, to decide on the best one.

## Getting started

### Prerequisites

- [An installation of Elixir](https://elixir-lang.org/install.html)
- [An installation of Pheonix](https://hexdocs.pm/phoenix/overview.html) - A framework for building Elixir-based web apps.

### Build

1. Clone this repository
2. Create a `.env` file in the root of the repo with the following content. Then replace the placeholder values with your own:

```sh
AMPLITUDE_API_KEY="YOUR-AMPLITUDE-API-KEY-GOES-HERE"
CONFIGCAT_SDK_KEY="YOUR-CONFIGCAT-SDK-KEY-GOES-HERE"
```

3. Install the dependencies:

```sh
mix setup
```

### Run

1. Start Phoenix endpoint with:

```sh
mix phx.server
```

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

## Learn more

Useful links to technical resources.

- [Official website](https://www.phoenixframework.org/)
- [Guides](https://hexdocs.pm/phoenix/overview.html)
- [Docs](https://hexdocs.pm/phoenix)
- [Forum](https://elixirforum.com/c/phoenix-forum)
- [Source](https://github.com/phoenixframework/phoenix)

[**ConfigCat**](https://configcat.com) also supports many other frameworks and languages. Check out the full list of supported SDKs [here](https://configcat.com/docs/sdk-reference/overview/).

You can also explore other code samples for various languages, frameworks, and topics here in the [ConfigCat labs](https://github.com/configcat-labs) on GitHub.

Keep up with ConfigCat on [X](https://twitter.com/configcat), [Facebook](https://www.facebook.com/configcat), [LinkedIn](https://www.linkedin.com/company/configcat/), and [GitHub](https://github.com/configcat).

## Author

[Chavez Harris](https://github.com/codedbychavez)

## Contributions

Contributions are welcome!

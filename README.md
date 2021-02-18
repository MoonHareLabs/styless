<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/pmarsceill/just-the-docs/actions?query=workflow%3A%22Master+branch+CI%22"><img src="https://github.com/pmarsceill/just-the-docs/workflows/Master%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">Styless</h1>
    <p align="center">A modern, highly customizable, and unstyled Jekyll theme for developers with built-in dark mode.<br>Easily hosted on GitHub Pages with few dependencies.</p>
    <p align="center"><strong><a href="https://pmarsceill.github.io/just-the-docs/">See it in action!</a></strong></p>
    <br><br><br>
</p>

## Installation

### Github Pages Installation
Add Styless to your Jekyll site’s _config.yml as a remote theme
```yaml
remote_theme: moonharelabs/styless
```
> You must have GitHub Pages enabled on your repo, one or more Markdown files, and a _config.yml file. See an example repository

### Local Installation
Add this line to your Jekyll site's Gemfile:

```ruby
gem "styless"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: styless
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install styless

Alternatively, you can run it inside Docker while developing your site

    $ docker-compose up

## Usage

[View the documentation](https://moonharelabs.github.io/styless/) for usage information.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/moonharelabs/styless. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Submitting code changes:

- Open a [Pull Request](https://github.com/moonharelabs/styless/pulls)
- Ensure all CI tests pass
- Await code review
- Bump the version number in `styless.gemspec` and `package.json` according to [semantic versioning](https://semver.org/).

### Design and development principles of this theme:

1. As few dependencies as possible
2. No build script needed
3. First class mobile experience
4. Make the content shine

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [Unlicense License](http://opensource.org/licenses/unlicense).

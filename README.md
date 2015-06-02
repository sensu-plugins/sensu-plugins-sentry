## Sensu-Plugins-sentry

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-sentry.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-sentry)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-sentry.svg)](http://badge.fury.io/rb/sensu-plugins-sentry)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sentry/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sentry)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sentry/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-sentry)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-sentry.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-sentry)
[ ![Codeship Status for sensu-plugins/sensu-plugins-sentry](https://codeship.com/projects/cd5993d0-ea2f-0132-feb9-32dfa18a9fce/status?branch=master)](https://codeship.com/projects/83067)

## Functionality

## Files
 * bin/handler-sentry

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-sentry -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-sentry`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-sentry' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-sentry' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes

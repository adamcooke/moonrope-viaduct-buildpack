# Moonrope Buildpack for Viaduct

This buildpack can be used to automatically generate & host Moonrope documentation
for an application.

At the moment, it will always build using the latest version of Moonrope from
the core repository.

## Setup

1. Create the application on Viaduct with the repository as the application that
   contains your Moonrope API.

2. Choose no templates

3. Once the application is created goto **Settings -> General** and choose a
   suitable Ruby platform and enter the buildpack URL as this repository.

4. Deploy!

## TODO

* Use the correct version of Moonrope based on the application's Gemfile
* Allow use of directories other than `api`

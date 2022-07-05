# Alfred Workflow - Wifi Speedtest
Test the Upload/Download speed of the wifi you're currently on.

## Installation

1. Install `speedtest` on your system using homebrew: `brew tap teamookla/speedtest
brew update
# Example how to remove conflicting or old versions using brew
# brew uninstall speedtest --force
brew install speedtest --force
`.
2. Download the [workflow](https://github.com/NKR00711/alfred-speedtest/blob/master/Speedtest.alfredworkflow).
3. Double click the downloaded workflow to install it in Alfred.

## Usage

Using the keyword `speedtest` in alfred, select the workflow then wait 30 seconds while the speedtest is running (a notification will appear letting you know it's started the test). After 30 seconds, view the notification that pops up with the results of the speedtest.

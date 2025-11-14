# KeepReadingII-Grav

*A lightweight, modern TailwindCSS blog theme for Grav CMS.*

## Features

* Clean, minimal design based on TailwindCSS
* Fully responsive layout for all devices
* Built-in light/dark mode
* Social media link support with optional icon mode
* Customizable footer (headline, description, feed link, link groups)
* Tracking code injection (HTML/JS)
* Optimized for blogs and content-heavy websites
* Easy configuration through the Grav Admin Panel

## Installation

### Manual installation

Clone or download the theme into your Grav installation:

```
cd user/themes
git clone https://github.com/cheinisch/KeepReadingII-Grav keepreading-ii
```
### Activate the theme

In your `user/config/system.yaml`:
```
system:
  pages:
    theme: keepreading-ii
```
Or simply activate it via Grav Admin -> Themes.

## Configuration

All options are available in the Grav Admin Panel under:
Themes -> KeepReading II

Alternatively, edit:
```
user/config/themes/keepreading-ii.yaml
```

### Footer Settings

* Enable the footer - turn the footer on/off
* Footer Headline - title displayed above the footer content
* Footer Description - short descriptive text
* Feed URL - e.g., `/feed` for RSS/Atom feeds

### Social Media

* Headline - title above the link section
* Show only social media icons - switch between icon-only or text link list
  * Social fields:
  * GitHub
  * Instagram
  * X (Twitter)
  * YouTube
  * LinkedIn

### Link List & Tracking

* Link list headline - custom title
* Tracking enabled - toggle tracking on/off
* Tracking Code (HTML/JS) - inject analytics or custom scripts at the bottom of the page

## Requirements

* Grav CMS (latest version recommended)
* TailwindCSS (precompiled CSS included)
* Optional: Feed plugin for RSS support

## License

Released under the MIT License.
See the `LICENSE` file for details.

## Demo

Live demo available at:
[https://demo.heinisch-design.de/keepreading-ii](https://demo.heinisch-design.de/keepreading-ii)
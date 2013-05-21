# Segmented Control

A drop-in remplacement for UISegmentedControl that mimic iOS 6 AppStore tab controls.

![The only good piece of UI to extract for this terrible app](http://d.pr/i/Fn5X+)

<!-- MacBuildServer Install Button -->
<div class="macbuildserver-block">
    <a class="macbuildserver-button" href="http://macbuildserver.com/project/github/build/?xcode_project=Example%2FExample.xcodeproj&amp;target=Example&amp;repo_url=https%3A%2F%2Fgithub.com%2Frs%2FSDSegmentedControl&amp;build_conf=Release" target="_blank"><img src="http://com.macbuildserver.github.s3-website-us-east-1.amazonaws.com/button_up.png"/></a><br/><sup><a href="http://macbuildserver.com/github/opensource/" target="_blank">by MacBuildServer</a></sup>
</div>
<!-- MacBuildServer Install Button -->


## Features

- Segments with image, image and text or text only
- Interface Builder support (just throw a UISegmentedControl and change its class SDSegmentedControl)
- Animated segment selection
- Content aware dynamic segment width
- Scrollable if there are too many segments for width
- Animated segment selection, with animated arrow
- Appearance customization thru UIAppearance
- UIControl events for value changes
- Enable or disable specific segments
- Indiviual customizable segment width

### TODO

- Shadow effect / arrows, which show that the segment control is scrollable

## Usage

Import `SDSegmentedControl.h` and `SDSegmentedControl.m` into your project and add `QuartzCore` framework to `Build Phases` -> `Link Binary With Libraries`.

You can then use `SDSegmentedControl` class as you would use normal `UISegmentedControl`.

## Licenses

All source code is licensed under the [MIT-License](https://raw.github.com/rs/SDSegmentedControl/master/MIT-LICENSE).

The icons in the example project are taken from [Glypish Free Iconscreated by Joseph Wain](http://glyphish.com) and licensed under the Creative Commons Attribution 3.0 United States License.

## Authors

- Olivier Poitrey <rs@dailymotion.com>
- Marius Rackwitz <git@mariusrackwitz.de>

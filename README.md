# Sass CSS3 Mixins! The Cross-Browser CSS3 Sass Library

By: Matthieu Aussaguel, http://www.mynameismatthieu.com, @matthieu_tweets

List of CSS3 Sass Mixins File to be @imported and @included as you need

The purpose of this library is to facilitate the use of CSS3 on different browsers avoiding HARD TO READ and NEVER
ENDING css files

* Note
All CSS3 Properties are being supported by Safari 5
more info: http://www.findmebyip.com/litmus/#css3-properties

## Mixins available:

  -   background-gradient     - arguments: Start Color: #3C3C3C, End Color: #999999
  -   background-size         - arguments: Width: 100%, Height: 100%
  -   border-radius           - arguments: Radius: 5px
  -   border-radius-separate  - arguments: Top Left: 5px, Top Left: 5px, Bottom Left: 5px, Bottom Right: 5px
  -   box                     - arguments: Orientation: horizontal, Pack: center, Align: center
  -   box-rgba                - arguments: R: 60, G: 3, B: 12, Opacity: 0.23, Color: #3C3C3C
  -   box-shadow              - arguments: X: 2px, Y: 2px, Blur: 5px, Color: rgba(0,0,0,.4)
  -   box-sizing              - arguments: Type: border-box
  -   columns                 - arguments: Count: 3, Gap: 10
  -   double-borders          - arguments: Color One: #3C3C3C, Color Two: #999999, Radius: 0
  -   flex                    - arguments: Value: 1
  -   flip                    - arguments: ScaleX: -1
  -   font-face               - arguments: Font Family: myFont, Eot File Src: myFont.eot, Woff File Src: myFont.woff, Ttf File Src: myFont.ttf
  -   opacity                 - arguments: Opacity: 0.5
  -   outline radius          - arguments: Radius: 5px
  -   resize                  - arguments: Direction: both
  -   rotate                  - arguments: Degree: 0, M11: 0, M12: 0, M21: 0, M22: 0
  CSS Matrix Rotation Calculator http://www.boogdesign.com/examples/transforms/matrix-calculator.html
  -   text-shadow             - arguments: X: 2px, Y: 2px, Blur: 5px, Color: rgba(0,0,0,.4)
  -   transform               - arguments: Parameters: null
  -   transition              - arguments: What: all, Length: 1s, Easing: ease-in-out
  -   triple-borders          - arguments: Color One: #3C3C3C, Color Two: #999999, Color Three: #000000, Radius: 0

## Examples and Instructions


@import "css3-mixins.scss"

@include opacity();
@include border-radius(3px); 
@include transition(color, .5s, ease-in); 

## Demo Page

Coming soon...


## Changelog

* Initial Release
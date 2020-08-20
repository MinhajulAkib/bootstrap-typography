# bootstrap-typography
Bootstrap typography, including global settings, headings, body text, lists, and more.
Global settings
Bootstrap sets basic global display, typography, and link styles. When more control is needed, check out the textual utility classes.

Use a native font stack that selects the best font-family for each OS and device.
For a more inclusive and accessible type scale, we assume the browser default root font-size (typically 16px) so visitors can customize their browser defaults as needed.
Use the $font-family-base, $font-size-base, and $line-height-base attributes as our typographic base applied to the <body>.
Set the global link color via $link-color and apply link underlines only on :hover.
Use $body-bg to set a background-color on the <body> (#fff by default).
These styles can be found within _reboot.scss, and the global variables are defined in _variables.scss. Make sure to set $font-size-base in rem.

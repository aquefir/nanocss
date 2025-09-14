<p>
<picture>
<source media="(prefers-color-scheme: dark)"
srcset="https://cdn.tohoku.ac/nanocss-dark.svg" />
<source media="(prefers-color-scheme: light)"
srcset="https://cdn.tohoku.ac/nanocss-light.svg" />
<img alt="nanoCSS" src="https://cdn.tohoku.ac/nanocss-light.svg"
width="190" height="66" />
</picture>
</p>

_**Minimal CSS framework for semantic HTML**_

-----

**nanoCSS** is a minimal CSS framework forked from [Pico CSS][1] that
prioritises semantics-oriented syntax. For the most part, nanoCSS works
the same as Pico CSS does, but with a different symbol prefix (`nano`
instead of `pico`) and a colouring provision that tracks the 8-colour
palette of IBM-PC compatible terminal consoles.

nanoCSS was forked from the v2.1.1 point release of its parent project.
Since it is a hard fork, its inaugural version is v1.0.0.

For now, follow the [Pico CSS][2] documentation to get started with
nanoCSS.

-----

A lot of the webdev-style infrastructure has been gutted due to lack of
necessity. As sure as you probably want to use plain CSS in your project
we also wish to employ the same philosophy.

nanoCSS provides the standard 8 colours of the console in a pleasing,
pastel tincture that is 15-bit RGB555 compatible, along with their
&lsquo;bright&rsquo; or &lsquo;bold&rsquo; variants. The eight colours,
canonically, are as follows:

| black  |  red   | green  | yellow |  blue  |  pink  |  cyan  | white |
| `#000` | `#F00` | `#0F0` | `#FF0` | `#00F` | `#F0F` | `#0FF` | `#FFF`|

Additionally, nanoCSS provides two &lsquo;extra&rsquo; colours &ndash;
steel and brown &ndash; which should fall back to cyan and red,
respectively, in the event one cannot or does not wish to render extra
colours.

[1]: https://github.com/picocss/pico
[2]: https://picocss.com/docs

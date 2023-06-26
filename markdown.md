---
icon: material/view-grid-plus
---

# Markdown

Material for MkDocs offers a wide range of options for customizing your
documentation. In this section, we will explain how you can create a meaningful
structure for your site, change the look and feel, add a blog and comment system,
and build a highly optimized site.

## Site structure

Set up and customize the structure of your documentation by configuring the
header and footer to your taste, choosing among many modes of navigation,
setting up site search, and more.

<div class="grid cards" markdown>

- :fontawesome-solid-earth-americas: __[Language]__ – Choose out of the 60+ supported languages or add a new one
- :material-page-layout-sidebar-left: __[Navigation]__ – Create a clear, concise, and comprehensive navigation structure
- :material-page-layout-header: __[Header]__ – Customize the behavior of the header, add an announcement bar
- :material-page-layout-footer: __[Footer]__ – Add links to your social media profiles or websites in the footer 
- :material-tab-search: __[Search]__ – Set up and configure search, running entirely in the user's browser
- :material-tag-plus-outline: __[Tags]__ – Categorize your pages with tags and group related pages

</div>

  [Language]: changing-the-language.md
  [Navigation]: setting-up-navigation.md
  [Header]: setting-up-the-header.md
  [Footer]: setting-up-the-footer.md
  [Search]: setting-up-site-search.md
  [Tags]: setting-up-tags.md


## Appearance

Match your brand's colors, fonts, icons, logo, and more with a few lines of
configuration – Material for MkDocs makes it easy to extend the basic
configuration or alter the appearance.

<div class="grid cards" markdown>

- :material-brush-variant: __[Colors]__ Change colors with an existing color palette or customize with CSS
- :material-format-font: __[Fonts]__ – Choose among 1,000 Google Fonts or load self-hosted fonts
- :material-google-downasaur: __[Logo & Icons]__ – Change the logo, use any of the 8,000+ icons, or add new ones
- :material-cards-variant: __[Social Cards]__ – Automatically create social media previews when sharing links

</div>

  [Colors]: changing-the-colors.md
  [Fonts]: changing-the-fonts.md
  [Logo & Icons]: changing-the-logo-and-icons.md
  [Social Cards]: setting-up-social-cards.md

## Content

Create a blog, integrate a comment system, connect a git repository, and set up
versioned documentation that matches your project's versioning methodology.

<div class="grid cards" markdown>

- :material-book-open-outline: __[Blog]__ – Set up a standalone blog or host it alongside your documentation
- :material-comment-text-outline: __[Comment System]__ – Add a third-party comment system on any page or footer
- :octicons-versions-16: __[Versioning]__ – Deploy multiple versions by integrating with external utilities
- :octicons-repo-16: __[Repository]__ – Connect your documentation to your git repository

</div>

  [Blog]: setting-up-a-blog.md
  [Comment System]: adding-a-comment-system.md
  [Versioning]: setting-up-versioning.md  
  [Repository]: adding-a-git-repository.md

## Optimization

Add site analytics and build an optimized site by adding automatic image
compression, complying with GDPR data privacy regulations, and making it
offline-capable.

<div class="grid cards" markdown>

- :material-google-analytics: __[Site analytics]__ – Learn how your users experience your documentation
- :material-screwdriver: __[Optimized site]__ – Create optimized sites that rank great on search engines
- :octicons-lock-16: __[Data Privacy]__ – Ensure compliance with data privacy regulations
- :octicons-cloud-offline-16: __[Offline usage]__ – Build an online and offline-capable documentation

</div>

  [Site analytics]: setting-up-site-analytics.md
  [Optimized site]: building-an-optimized-site.md
  [Data Privacy]: ensuring-data-privacy.md
  [Offline usage]: building-for-offline-usage.md
  
[Subscribe to our newsletter](#){.md-button}

### Goals

The following section lists all funding goals. Each goal contains a list of
features prefixed with a checkmark symbol, denoting whether a feature is
:octicons-check-circle-fill-24:{ style="color: #00e676" } already available or 
:octicons-check-circle-fill-24:{ style="color: var(--md-default-fg-color--lightest)" } planned, but not yet implemented. When the funding goal is hit, the features
are released for general availability.

<div class="mdx-columns" markdown>

- [x] [Instant prefetching] :material-alert-decagram:{ .mdx-pulse title="Added on June 15, 2023" }
- [x] [Social plugin: custom layouts] :material-alert-decagram:{ .mdx-pulse title="Added on May 8, 2023" }
- [x] [Social plugin: background images] :material-alert-decagram:{ .mdx-pulse title="Added on May 8, 2023" }
- [x] [Code range selection]
- [x] [Code annotations: custom selectors]
- [x] [Privacy plugin: optimization support]
- [x] [Optimize plugin]
- [x] [Navigation path] (Breadcrumbs)
- [x] [Typeset plugin]
- [x] [Privacy plugin: external links]
- [x] [Navigation subtitles]
- [x] [Tags plugin: allow list] + [custom sorting]
- [x] [Blog plugin: custom index pages]
- [x] [Blog plugin: related links]
- [x] [Blog plugin]
- [x] [Navigation status]
- [x] [Meta plugin]
- [x] [Tags plugin: additional indexes]
- [x] [Document contributors]
- [x] [Automatic light / dark mode]
- [x] [Content tabs: anchor links]
- [x] [Navigation pruning]
- [x] [Tooltips]
- [x] [Chinese search support]
- [x] [Card grids]
- [x] [Privacy plugin]
- [x] [Annotations]
- [x] [Navigation icons]

</div>

#### $ 12,000 – Piri Piri

- [x] [Blog plugin]
- [x] [Chinese search support]
- [x] [Annotations]
- [x] [Navigation icons]
- [x] [Navigation pruning]
- [x] [Navigation status]

  [Blog plugin]: ../setup/setting-up-a-blog.md
  [Chinese search support]: ../blog/posts/chinese-search-support.md
  [Annotations]: ../reference/annotations.md
  [Navigation icons]: ../reference/index.md#setting-the-page-icon
  [Navigation pruning]: ../setup/setting-up-navigation.md#navigation-pruning
  [Navigation status]: ../reference/index.md#setting-the-page-status

## Requirements
------------

SysIdentPy requires:

| Dependency | version     | Comment                                              |
|------------|-------------|------------------------------------------------------|
| python     | >=3.7,<3.10 |                                                      |
| numpy      | >=1.9.2     | for all numerical algorithms                         |
| scipy      | >=1.7.0     | for some linear regression methods                   |
| matplotlib | >=3.3.2     | for static plotting and visualizations               |
| torch      | >=1.7.1     | Only necessary if you want to use Neural NARX models |


| Platform | Status |
|----------|--------|
| Windows  | ok     |
| Linux    | ok     |
| Mac OS   | ok     |

SysIdentPy **do not** to support Python 2.7.

<figure style="min-width:15.6rem">
  <blockquote class="twitter-tweet" data-conversation="none" data-dnt="true">
    <a href="https://twitter.com/WillingCarol/status/1603416470616088576?ref_src=twsrc%5Etfw"></a>
  </blockquote>
  <script async src="https://platform.twitter.com/widgets.js"></script>
</figure>


__Important__: If you're sponsoring @squidfunk through a GitHub organization,
please send a short email to sponsors@squidfunk.com with the name of your
organization and the GitHub account of the individual that should be added as a 
collaborator.[^4]

You can cancel your sponsorship anytime.[^5]

  [^4]:
    It's currently not possible to grant access to each member of an
    organization, as GitHub only allows for adding users. Thus, after
    sponsoring, please send an email to sponsors@squidfunk.com, stating which
    account should become a collaborator of the Insiders repository. We're
    working on a solution which will make access to organizations much simpler.
    To ensure that access is not tied to a particular individual GitHub account,
    create a bot account (i.e. a GitHub account that is not tied to a specific
    individual), and use this account for the sponsoring. After being added to
    the list of collaborators, the bot account can create a private fork of the
    private Insiders GitHub repository, and grant access to all members of the
    organizations.

  [^5]:
    If you cancel your sponsorship, GitHub schedules a cancellation request
    which will become effective at the end of the billing cycle. This means
    that even though you cancel your sponsorship, you will keep your access to
    Insiders as long as your cancellation isn't effective. All charges are
    processed by GitHub through Stripe. As we don't receive any information
    regarding your payment, and GitHub doesn't offer refunds, sponsorships are
    non-refundable.

 

> Lacerda et al., (2020). SysIdentPy: A Python package for System Identification using NARMAX models. Journal of Open Source Software, 5(54), 2384, https://doi.org/10.21105/joss.02384
```
	@article{Lacerda2020,
	  doi = {10.21105/joss.02384},
	  url = {https://doi.org/10.21105/joss.02384},
	  year = {2020},
	  publisher = {The Open Journal},
	  volume = {5},
	  number = {54},
	  pages = {2384},
	  author = {Wilson Rocha Lacerda Junior and Luan Pascoal Costa da Andrade and Samuel Carlos Pessoa Oliveira and Samir Angelo Milani Martins},
	  title = {SysIdentPy: A Python package for System Identification using NARMAX models},
	  journal = {Journal of Open Source Software}
	}
```
## Inspiration

The documentation and structure (even this section) is openly inspired by sklearn, einsteinpy, and many others as we used (and keep using) them to learn.
 

## Contributors

<a href="https://github.com/araguaci/o-dominio-de-si-mesmo/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=araguaci/o-dominio-de-si-mesmo" width = 100/>
</a>


## Citation  

> If you use SysIdentPy on your project, please drop me a line.

[Send email :fontawesome-solid-paper-plane:](mailto: wilsonrljr@outlook.com){.md-button .md-button--primary }


<figure class="mdx-video" markdown>
  <div class="mdx-video__inner">
    <iframe src="https://streamable.com/e/yslhdu" allowfullscreen></iframe>
  </div>
  <figcaption markdown>

This documentation is built with Insiders
[squidfunk.github.io/mkdocs-material][Material for MkDocs]

  </figcaption>
</figure> 

## Grids

Material for MkDocs makes it easy to arrange sections into grids, grouping
blocks that convey similar meaning or are of equal importance. Grids are just
perfect for building index pages that show a brief overview of a large section
of your documentation.

## Configuration

This configuration enables the use of grids, allowing to bring blocks of
identical or different types into a rectangular shape. Add the following lines
to `mkdocs.yml`:

``` yaml
markdown_extensions: # (1)!
  - attr_list
  - md_in_html
```

1.  Note that some of the examples listed below use [icons and emojis], which
    have to be [configured separately].

See additional configuration options:

- [Attribute Lists]
- [Markdown in HTML]

  [icons and emojis]: icons-emojis.md
  [configured separately]: icons-emojis.md#configuration
  [Attribute Lists]: ../setup/extensions/python-markdown.md#attribute-lists
  [Markdown in HTML]: ../setup/extensions/python-markdown.md#markdown-in-html

## Usage

Grids come in two flavors: [card grids], which wrap each element in a card that
levitates on hover, and [generic grids], which allow to arrange arbitrary block
elements in a rectangular shape.

  [card grids]: #using-card-grids
  [generic grids]: #using-generic-grids

### Using card grids

[:octicons-heart-fill-24:{ .mdx-heart } Sponsors only][Insiders]{ .mdx-insiders } ·
[:octicons-tag-24: insiders-4.12.0][Insiders] ·
:octicons-beaker-24: Experimental

Card grids wrap each grid item with a beautiful hover card that levitates on
hover. They come in two slightly different syntaxes: [list] and [block syntax],
adding support for distinct use cases.

  [Insiders]: ../insiders/index.md
  [list]: #list-syntax
  [block syntax]: #block-syntax

#### List syntax

The list syntax is essentially a shortcut for [card grids], and consists of an
unordered (or ordered) list wrapped by a `div` with both, the `grid` and `cards`
classes:

``` html title="Card grid"
<div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

</div>
```

<div class="result" markdown>
  <div class="grid cards" markdown>

- :fontawesome-brands-html5: __HTML__ for content and structure
- :fontawesome-brands-js: __JavaScript__ for interactivity
- :fontawesome-brands-css3: __CSS__ for text running out of boxes
- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

  </div>
</div>

List elements can contain arbitrary Markdown, as long as the surrounding `div`
defines the `markdown` attribute. Following is a more complex example, which
includes icons and links:

``` html title="Card grid, complex example"
<div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

    ---

    Install [`mkdocs-material`](#) with [`pip`](#) and get up
    and running in minutes
    
    [:octicons-arrow-right-24: Getting started](#)

-   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site
    
    [:octicons-arrow-right-24: Reference](#)

-   :material-format-font:{ .lg .middle } __Made to measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines
    
    [:octicons-arrow-right-24: Customization](#)

-   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

    ---

    Material for MkDocs is licensed under MIT and available on [GitHub]

    [:octicons-arrow-right-24: License](#)

</div>
```

<div class="result" markdown>
  <div class="grid cards" markdown>

-   :material-clock-fast:{ .lg .middle } __Set up in 5 minutes__

    ---

    Install [`mkdocs-material`][mkdocs-material] with [`pip`][pip] and get up
    and running in minutes
    
    [:octicons-arrow-right-24: Getting started][getting started]

-   :fontawesome-brands-markdown:{ .lg .middle } __It's just Markdown__

    ---

    Focus on your content and generate a responsive and searchable static site
    
    [:octicons-arrow-right-24: Reference][reference]

-   :material-format-font:{ .lg .middle } __Made to measure__

    ---

    Change the colors, fonts, language, icons, logo and more with a few lines
    
    [:octicons-arrow-right-24: Customization][customization]

-   :material-scale-balance:{ .lg .middle } __Open Source, MIT__

    ---

    Material for MkDocs is licensed under MIT and available on [GitHub]

    [:octicons-arrow-right-24: License][license]

  </div>
</div>

If there's insufficient space to render grid items next to each other, the items
will stretch to the full width of the viewport, e.g. on mobile viewports. If
there's more space available, grids will render in items of 3 and more, e.g.
when [hiding both sidebars].

  [mkdocs-material]: https://pypistats.org/packages/mkdocs-material
  [pip]: ../getting-started.md#with-pip
  [getting started]: ../getting-started.md
  [reference]: ../reference/index.md
  [customization]: ../customization.md
  [license]: ../license.md
  [GitHub]: https://github.com/squidfunk/mkdocs-material
  [hiding both sidebars]: ../setup/setting-up-navigation.md#hiding-the-sidebars

#### Block syntax

The block syntax allows for arranging cards in grids __together with other
elements__, as explained in the section on [generic grids]. Just add the `card`
class to any block element inside a `grid`:

``` html title="Card grid, blocks"
<div class="grid" markdown>

:fontawesome-brands-html5: __HTML__ for content and structure
{ .card }

:fontawesome-brands-js: __JavaScript__ for interactivity
{ .card }

:fontawesome-brands-css3: __CSS__ for text running out of boxes
{ .card }

> :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

</div>
```

<div class="result" markdown>
  <div class="grid" markdown>

:fontawesome-brands-html5: __HTML__ for content and structure
{ .card }

:fontawesome-brands-js: __JavaScript__ for interactivity
{ .card }

:fontawesome-brands-css3: __CSS__ for text running out of boxes
{ .card }

> :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

  </div>
</div>

While this syntax may seem unnecessarily verbose at first, the previous example
shows how card grids can now be mixed with other elements that will also stretch
to the grid.

### Using generic grids

[:octicons-heart-fill-24:{ .mdx-heart } Sponsors only][Insiders]{ .mdx-insiders } ·
[:octicons-tag-24: insiders-4.12.0][Insiders] ·
:octicons-beaker-24: Experimental

Generic grids allow for arranging arbitrary block elements in a grid, including
[admonitions], [code blocks], [content tabs] and more. Just wrap a set of blocks
by using a `div` with the `grid` class:

```` html title="Generic grid"
<div class="grid" markdown>

=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

``` title="Content tabs"
=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci
```

</div>
````

<div class="result" markdown>
  <div class="grid" markdown>

=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

``` title="Content tabs"
=== "Unordered list"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci

=== "Ordered list"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci
```

  </div>
</div>

  [admonitions]: admonitions.md
  [code blocks]: code-blocks.md
  [content tabs]: content-tabs.md

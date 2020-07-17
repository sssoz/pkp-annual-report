# PKP Annual Report: 2019

A static one-pager for the Public Knowledge Project’s (PKP) annual report built with Jekyll.

--- 

## Structure 

- Only one page layout style, in `_layouts/home`
- Reusable HTML fragments, in `_includes`
  - `svg/` for logo and icons 
  - `head.html`
  - `footer.html`
- Styles are broken down into partials in `_sass/`
  - `_base/`: variables, mixins, & typography 
  - `_components/`: HTML elements, basic components
  - `_themes`: print styles overrides 
  - All partials are imported in `css/main.scss`
- Sections of the report are in `_sections`
  - Each section is prefixed with a number, determining its order
  - One Markdown file per section
  - Every section has frontmatter: 
    - `heading`: section title
    - `subheading`: section subtitle / tagline
    - `intro`: description 
    - `inverted`: section has a dark background & white text, set to `true` or `false`
    - `highlighted`: section has a highlighted background, set to `true` or `false`

---

## Setting up the site

Ruby must be installed.

1. `gem install jekyll`

### Running the site locally

1. `git clone https://github.com/sssoz/pkp-annual-report.git`
2. `cd pkp-annual-report`
3. `jekyll s`

### Building the website

1. `jekyll build`
2. Content to be published will be found in `/_site`

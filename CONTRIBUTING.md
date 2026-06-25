---
title: "How to contribute"
---

# Install [Quarto](https://quarto.org/)

The install should update your path and run from any command terminal.

Change to the project directory (if using GitHub Desktop, select "Repository - Open in Command prompt", or `Ctrl+\`)

Run the "[Quarto preview](https://quarto.org/docs/cli/preview.html)" command to start a live preview session that will render the updated pages as you edit. Some changes may not be automatically rendered by the preview, and you may need to exit (type `Ctrl-c` in the command window) and then restart the preview.

The site will be served locally by Quarto and should open a browser session at: http://localhost:xxxx/, with a default port in the range of 3000-8000 being assigned. The system console will indicate the port that is selected.

The site may need to be re-built (run "Quarto render") after edits are complete. This is usually only needed prior to deploying a site to the server.

## Publishing site

Quarto provides [several methods](https://quarto.org/docs/publishing/) to publish a website. The Alaska Region Data Management User Guide [GitHub repositoty](https://github.com/USFWS/ak-dm-guide) is configured to ignore the `/docs` directory and uses the Quarto [publish command](https://quarto.org/docs/publishing/github-pages.html#publish-command) to deploy sites. (Attempting to render GitHub pages from the `/docs` directory often results in numerous conflicts if the site is edited my multiple individuals.)


# Style guide

## Graphics

### Image format

Graphics should be saved as a Portable Netwotk Graphics (PNG) format whenever possible. Images should be scaled to width of 1200 pixels for landscape orientation, or a height of 1200 pixels for portrait orientation.


### Image names
Images should be stored in the `/assets` directory. Use short (this is subjective, so use your best judgement) but desriptive names. 

```
Good: rdr-uri-elements.png
Bad: image (8).png
Bad: regionalDataRepository-uri-components.png
```



## Callout boxes

Come up with some guidance on when callout boxes should be used. See Quarto [Callout Blocks](https://quarto.org/docs/authoring/callouts.html) documentation for details.

:::{.callout-note}
Note that there are five types of callouts, including:
`note`, `warning`, `important`, `tip`, and `caution`.
:::

:::{.callout-tip}
## Custom title can be added
Tip callout. Use this for a general tip.
:::

:::{.callout-warning}
Warning callout
:::

:::{.callout-caution}
Caution callout
:::

:::{.callout-important}
Important callout. Maybe use this to higlight destructive operations.
:::


## Icons

Quarto uses [Bootstrap icons](https://icons.getbootstrap.com/) for various components (e.g., [Sidebar Tools](https://quarto.org/docs/reference/projects/websites.html#sidebar-tools)). Icons are referenced by name, as displayed on the Bootstrap icon page.

:::{.callout-note}
There is an extension that allows for the display of [Font Awesome](https://fontawesome.com/icons) icons within the body of the text, however, it is not currently installed.
:::


## Directories

A directory renders as a collapsable section. Do we want to limit the depth to one subdirectory-level?
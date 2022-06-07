| **Blazor UI Components** Suggestions | <img src="./media/image1.png" style="width:2.79214in;height:2.1913in" /> |
|--------------------------------------|--------------------------------------------------------------------------|
| *Last updated:* **June 1, 2022**     |                                                                          |

<!-- TOC -->

- [Overview](#overview)
    - [Updates](#updates)
        - [2022 -06-01](#2022--06-01)
    - [Note on GIFs](#note-on-gifs)
    - [Implemented](#implemented)
- [Components](#components)
    - [Sticky components](#sticky-components)
        - [Sticky Side Menu](#sticky-side-menu)
        - [Sticky Table of Contents](#sticky-table-of-contents)
        - [Sticky Header](#sticky-header)

<!-- /TOC -->

# Overview

This is a list of commonly used components. We will be adding to this
list as new ideas come up. You can find a log of our updates to this
file in the section below.

For comments or questions, please leave a comment in this document or
[contact the UX
team](mailto:experienceutilisateur-userexperience@ec.gc.ca).

## Updates

### 2022-06-01

-   Initial version of the document

## Note on GIFs

Some of the images in this document are GIFs, but for some reason they
are not animated by either Word Web or Word Desktop apps. All assets
used in this document are also stored here:
[Assets](https://007gc.sharepoint.com/:f:/s/BeSD-SADSAI-AS-UXTeam/EgAZxjy8CtdOiIIwIJDIiBsB64wMvV_p5VqjeraT8B6T6g?e=aba4Ys)

## Implemented

The following components were implemented in the scope of the Data
Submission Portal (DSP) (dev: <https://dsp-psd-dev.np.az.ec.gc.ca/>)
application:

-   Drag and drop file upload

-   WET Datatable

-   Modal that looks like the WET modals

-   Anchor navigation (pound signs break the client-side routing in
    Blazor)

-   Loading icon

-   The component displaying success or error messages (this one is
    probably not that useful for other projects)

# Components

## Sticky components

### Sticky Side Menu

<dl>
    <dt><img src="./media/image2.gif"/></dt>
    <dt>Details</dt>
    <dd>A Menu with a header label and sub menu items that are links that sticks to the top of the page as you scroll.</dd>
    <dd>Live Example: <a href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">NPRI Link</a><dd>
</dl>

### Sticky Table of Contents

<dl>
    <dt><img src="./media/image3.gif"/></dt>
    <dd>Live Example: <a href="https://species-registry.canada.ca/index-en.html#/species/963-646">Species at Risk</a><dd>
</dl>

### Sticky Header

<dl>
    <dt><img src="./media/image2.gif"/></dt>
    <dt>Details</dt>
    <dd>Sticky header with customizable body (similar to how it’s implemented in GitHub issue pages).</dd>
    <dt>Live Examples</dt>
    <dd>
        <a href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">SSA Figma Link</a>
    </dd>
    <dd>
        <a href="https://github.com/ramp4-pcar4/story-ramp/issues/213">The Time Slider in the Maps blocks data on Small-Medium extents · Issue #213 · ramp4-pcar4/story-ramp (github.com)</a>
    </dd>
</dl>
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
        - [Sticky Footer](#sticky-footer)
    - [Cards](#cards)
    - [Dropdowns / Menus](#dropdowns--menus)
    - [Export to Excel/CSV](#export-to-excelcsv)
    - [Faceted Search](#faceted-search)
        - [Faceted Filter Menu](#faceted-filter-menu)
        - [Selected Filter Option (Pills)](#selected-filter-option-pills)
    - [Multi Select](#multi-select)

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

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image2.gif"
style="width:5in;height:4.15625in" /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>A Menu with a header label and sub menu items that are links that
sticks to the top of the page as you scroll.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">NPRI
Link</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

### Sticky Table of Contents

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image3.gif"
style="width:6.11458in;height:5.07292in"
alt="francais Search Canada.ca Species search )usky Salapander (Desmognathus ian population Table of contents Species summary. us ochrophaeus o Legal list o COSEWIC assessment o Related Species Species details o Description " /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://species-registry.canada.ca/index-en.html#/species/963-646">Species
at Risk</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

### Sticky Header

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image4.gif"
style="width:6.875in;height:2.57292in"
alt="Government of Canada Gouvernement du Canada Application name Overview Section 1 Section 2 Section 3 Section 4 Page Page Page Page Page John Doe - November 4, 2021 2:27 PM O Open Reference ID: a9ebe89d-d3ee-44e8-aef8-bb54525da22f1 " /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>Sticky header with customizable body (similar to how it’s
implemented in GitHub issue pages).</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">SSA
Figma Link</a></p></li>
<li><p><a
href="https://github.com/ramp4-pcar4/story-ramp/issues/213">The Time
Slider in the Maps blocks data on Small-Medium extents · Issue #213 ·
ramp4-pcar4/story-ramp (github.com)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

### Sticky Footer

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image5.gif"
style="width:6.83334in;height:3.11458in"
alt="2021 Date modified: 2019-03-08 2022 2023 Previous Page nditions • Privacy Save &amp; Next Page Canadå " /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>Sticky footer with buttons for long forms that require scrolling.
The sticky footer allows action buttons to be accessible at all
times.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">NPRI
Link</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

## Cards

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><img src="./media/image6.png"
style="width:6.35416in;height:3.05208in"
alt="Bearded Owl-clover Legal information Name Bearded Owl-clover COSEWIC information Name Bearded Owl-clover Range British Columbia Taxonomic group Vascular Plants Scientific name Triphysaria versicolor Status on Schedule 1 Endangered Status Endangered Date added 2003-06-05 Last assessed 2011-11 " /></p>
<p><img src="./media/image7.png"
style="width:6.35417in;height:2.727in" /></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>A card is a flexible and extensible content container. It includes
options for headers and footers, a wide variety of content, contextual
background colors.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://species-registry.canada.ca/index-en.html#/species?ranges=2,7&amp;sortBy=commonNameSort&amp;sortDirection=asc&amp;pageSize=10">Species
at Risk</a></p></li>
<li><p><a
href="https://lakeclearmoon.z27.web.core.windows.net/report/part_1a/part_1a_disposals.html">Disposals
- National Pollutant Release Inventory (windows.net)</a></p></li>
<li><p><a
href="https://getbootstrap.com/docs/4.0/components/card/">Cards ·
Bootstrap (getbootstrap.com)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

## Dropdowns / Menus

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="./media/image8.gif"
style="width:2.96875in;height:1.5625in" /></th>
<th><img src="./media/image9.png"
style="width:1.73958in;height:1.65625in"
alt="Bulk Action v e Approve Deny " /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="./media/image10.png"
style="width:2.38542in;height:2.03125in"
alt="Dropdown button • Action Another action Something else here (button class=&quot;btn btn-se " /></td>
<td><img src="./media/image11.png"
style="width:3.22917in;height:2.53125in"
alt="Primary Exampl &lt;div class= (button t (button t (span c &lt;/button&gt; Secondary Action Another action Something else here Separated link suc btn btn ogg: " /></td>
</tr>
</tbody>
</table></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>Keyboard- and accessibility-friendly dropdowns/menus; useful for
embedding into tables and having additional actions hidden from
immediate view to not clutter the screen.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://lakeclearmoon.z27.web.core.windows.net/reporting_dashboard.html">Reporting
dashboard - National Pollutant Release Inventory
(windows.net)</a></p></li>
<li><p><a
href="https://www.figma.com/file/ezbIuyTPtc0yN66BaRfGYN/SSA-wireframes-%2B-mockups?node-id=698%3A55291">https://www.figma.com/file/ezbIuyTPtc0yN66BaRfGYN/SSA-wireframes-%2B-mockups?node-id=698%3A55291</a></p></li>
<li><p><a
href="https://getbootstrap.com/docs/5.2/components/dropdowns/#single-button">Dropdowns
· Bootstrap v5.2 (getbootstrap.com)</a></p></li>
<li><p><a
href="https://getbootstrap.com/docs/5.2/components/dropdowns/#split-button">Dropdowns
· Bootstrap v5.2 (getbootstrap.com)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

## Export to Excel/CSV

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image12.png"
style="width:2.19792in;height:0.97917in" alt="호 10 E뚀이 " /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>This is more of a common functionality than a UI component: export
search results (based on filters) in CSV/Excel format.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://species-registry.canada.ca/index-en.html#/species?sortBy=commonNameSort&amp;sortDirection=asc&amp;pageSize=10">Species
search - Species at risk registry (canada.ca)</a></p></li>
<li><p><a
href="https://environmental-protection.canada.ca/offenders-registry#:~:text=Search-,Export%20all%20records%20of%20the%20Environmental%20Offenders%20Registry,-Click%20on%20the">Environmental
Offenders Registry - Canada.ca</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

## Faceted Search

### Faceted Filter Menu

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image13.png"
style="width:7.36667in;height:2.30208in" /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>A collapsible menu that checkboxes or radio button options for
filtering through a data table or other UI components (like cards).</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://species-registry.canada.ca/index-en.html#/species?ranges=2,7&amp;sortBy=commonNameSort&amp;sortDirection=asc&amp;pageSize=10">Species
at Risk</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

### Selected Filter Option (Pills)

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><img src="./media/image14.png"
style="width:6.14583in;height:0.48655in" /></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>A horizontal list of selected filter options that can be dismissed
individually or can all be cleared with a button.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://species-registry.canada.ca/index-en.html#/species?ranges=2,7&amp;sortBy=commonNameSort&amp;sortDirection=asc&amp;pageSize=10">Species
at Risk</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

## Multi Select 

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><img src="./media/image15.png"
style="width:7.27945in;height:1.07675in" /></p>
<p><img src="./media/image16.png"
style="width:7.16667in;height:0.62708in" /></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Details</strong></td>
<td>A drop down multi select component with text input to filter down
available options. Each selection appears as a pill that can be
dismissed to remove the selection.</td>
</tr>
<tr class="even">
<td><strong>Live Example</strong></td>
<td><ul>
<li><p><a
href="https://www.figma.com/proto/ezbIuyTPtc0yN66BaRfGYN/SSA-wireframes-%2B-mockups?node-id=1279%3A82050&amp;scaling=min-zoom&amp;page-id=351%3A1604&amp;starting-point-node-id=1279%3A86906&amp;show-proto-sidebar=1">Figma
Link for SSA</a></p></li>
<li><p><a href="https://choices-js.github.io/Choices/">Choices
(choices-js.github.io)</a></p></li>
<li><p><a href="https://vue-multiselect.js.org/">Vue-Multiselect | Vue
Select Library</a></p></li>
</ul></td>
</tr>
</tbody>
</table>

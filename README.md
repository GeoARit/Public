# GeoAR.it Issues

This repository is the public issue tracker for the GeoAR.it platform.

Main repository: https://github.com/GeoARit

To open a new issue, head to https://github.com/GeoARit/Public/issues/new?labels=area:web,bug and choose an area label and a normal label.

## How to label issues

Every issue should have **two labels**:

1. **One Area label** (what part of the platform it relates to)
2. **One Type label** (what kind of issue it is)

This keeps triage fast and makes filtering reliable.

<table class="table table-dark">
  <thead>
    <tr>
      <th>Area label</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>area:ai</code></td>
      <td>AI and agent issues (Geordie Genie, prompts, tool calls, model behaviour)</td>
    </tr>
    <tr>
      <td><code>area:api</code></td>
      <td>API issues for api.GeoAR.it (endpoints, authentication responses, data integrity)</td>
    </tr>
    <tr>
      <td><code>area:app</code></td>
      <td>Mobile app issues for GeoAR.it (Unity AR client, performance, device behaviour)</td>
    </tr>
    <tr>
      <td><code>area:web</code></td>
      <td>Website issues for GeoAR.it (UI, pages, forms, frontend behaviour)</td>
    </tr>
  </tbody>
</table>

<table class="table table-dark">
  <thead>
    <tr>
      <th>Type label</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>bug</code></td>
      <td>Something isn't working</td>
    </tr>
    <tr>
      <td><code>documentation</code></td>
      <td>Improvements or additions to documentation</td>
    </tr>
    <tr>
      <td><code>duplicate</code></td>
      <td>This issue or pull request already exists</td>
    </tr>
    <tr>
      <td><code>enhancement</code></td>
      <td>New feature or request</td>
    </tr>
    <tr>
      <td><code>good first issue</code></td>
      <td>Good for newcomers</td>
    </tr>
    <tr>
      <td><code>help wanted</code></td>
      <td>Extra attention is needed</td>
    </tr>
    <tr>
      <td><code>invalid</code></td>
      <td>This doesn't seem right</td>
    </tr>
    <tr>
      <td><code>question</code></td>
      <td>Further information is requested</td>
    </tr>
    <tr>
      <td><code>wontfix</code></td>
      <td>This will not be worked on</td>
    </tr>
  </tbody>
</table>

<table class="table table-dark">
  <thead>
    <tr>
      <th>Example</th>
      <th>Labels</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Website login broken</td>
      <td><code>area:web</code> + <code>bug</code></td>
    </tr>
    <tr>
      <td>App crash near hotspot</td>
      <td><code>area:app</code> + <code>bug</code></td>
    </tr>
    <tr>
      <td>API returns 401 unexpectedly</td>
      <td><code>area:api</code> + <code>bug</code></td>
    </tr>
    <tr>
      <td>Geordie Genie response is incorrect</td>
      <td><code>area:ai</code> + <code>bug</code></td>
    </tr>
    <tr>
      <td>Improve API docs</td>
      <td><code>area:api</code> + <code>documentation</code></td>
    </tr>
  </tbody>
</table>

## Mermaid overview

```mermaid
flowchart LR
  R["Choose 1 Area + 1 Type"]

  R --> W["Web Area"]
  R --> A["App Area"]
  R --> P["API Area"]
  R --> I["AI Area"]

  W --> W_BUG["web:bug"]
  W --> W_DOC["web:documentation"]
  W --> W_DUP["web:duplicate"]
  W --> W_ENH["web:enhancement"]
  W --> W_GFI["web:good first issue"]
  W --> W_HELP["web:help wanted"]
  W --> W_INV["web:invalid"]
  W --> W_Q["web:question"]
  W --> W_WONT["web:wontfix"]

  A --> A_BUG["app:bug"]
  A --> A_DOC["app:documentation"]
  A --> A_DUP["app:duplicate"]
  A --> A_ENH["app:enhancement"]
  A --> A_GFI["app:good first issue"]
  A --> A_HELP["app:help wanted"]
  A --> A_INV["app:invalid"]
  A --> A_Q["app:question"]
  A --> A_WONT["app:wontfix"]

  P --> P_BUG["api:bug"]
  P --> P_DOC["api:documentation"]
  P --> P_DUP["api:duplicate"]
  P --> P_ENH["api:enhancement"]
  P --> P_GFI["api:good first issue"]
  P --> P_HELP["api:help wanted"]
  P --> P_INV["api:invalid"]
  P --> P_Q["api:question"]
  P --> P_WONT["api:wontfix"]

  I --> I_BUG["ai:bug"]
  I --> I_DOC["ai:documentation"]
  I --> I_DUP["ai:duplicate"]
  I --> I_ENH["ai:enhancement"]
  I --> I_GFI["ai:good first issue"]
  I --> I_HELP["ai:help wanted"]
  I --> I_INV["ai:invalid"]
  I --> I_Q["ai:question"]
  I --> I_WONT["ai:wontfix"]

  click W_BUG "https://github.com/GeoARit/Public/issues/new?labels=area:web,bug&assignees=MetARverse-Ian" _blank
  click W_DOC "https://github.com/GeoARit/Public/issues/new?labels=area:web,documentation&assignees=MetARverse-Ian" _blank
  click W_DUP "https://github.com/GeoARit/Public/issues/new?labels=area:web,duplicate&assignees=MetARverse-Ian" _blank
  click W_ENH "https://github.com/GeoARit/Public/issues/new?labels=area:web,enhancement&assignees=MetARverse-Ian" _blank
  click W_GFI "https://github.com/GeoARit/Public/issues/new?labels=area:web,good%20first%20issue&assignees=MetARverse-Ian" _blank
  click W_HELP "https://github.com/GeoARit/Public/issues/new?labels=area:web,help%20wanted&assignees=MetARverse-Ian" _blank
  click W_INV "https://github.com/GeoARit/Public/issues/new?labels=area:web,invalid&assignees=MetARverse-Ian" _blank
  click W_Q "https://github.com/GeoARit/Public/issues/new?labels=area:web,question&assignees=MetARverse-Ian" _blank
  click W_WONT "https://github.com/GeoARit/Public/issues/new?labels=area:web,wontfix&assignees=MetARverse-Ian" _blank

  click A_BUG "https://github.com/GeoARit/Public/issues/new?labels=area:app,bug&assignees=MetARverse-Ian" _blank
  click A_DOC "https://github.com/GeoARit/Public/issues/new?labels=area:app,documentation&assignees=MetARverse-Ian" _blank
  click A_DUP "https://github.com/GeoARit/Public/issues/new?labels=area:app,duplicate&assignees=MetARverse-Ian" _blank
  click A_ENH "https://github.com/GeoARit/Public/issues/new?labels=area:app,enhancement&assignees=MetARverse-Ian" _blank
  click A_GFI "https://github.com/GeoARit/Public/issues/new?labels=area:app,good%20first%20issue&assignees=MetARverse-Ian" _blank
  click A_HELP "https://github.com/GeoARit/Public/issues/new?labels=area:app,help%20wanted&assignees=MetARverse-Ian" _blank
  click A_INV "https://github.com/GeoARit/Public/issues/new?labels=area:app,invalid&assignees=MetARverse-Ian" _blank
  click A_Q "https://github.com/GeoARit/Public/issues/new?labels=area:app,question&assignees=MetARverse-Ian" _blank
  click A_WONT "https://github.com/GeoARit/Public/issues/new?labels=area:app,wontfix&assignees=MetARverse-Ian" _blank

  click P_BUG "https://github.com/GeoARit/Public/issues/new?labels=area:api,bug&assignees=MetARverse-Ian" _blank
  click P_DOC "https://github.com/GeoARit/Public/issues/new?labels=area:api,documentation&assignees=MetARverse-Ian" _blank
  click P_DUP "https://github.com/GeoARit/Public/issues/new?labels=area:api,duplicate&assignees=MetARverse-Ian" _blank
  click P_ENH "https://github.com/GeoARit/Public/issues/new?labels=area:api,enhancement&assignees=MetARverse-Ian" _blank
  click P_GFI "https://github.com/GeoARit/Public/issues/new?labels=area:api,good%20first%20issue&assignees=MetARverse-Ian" _blank
  click P_HELP "https://github.com/GeoARit/Public/issues/new?labels=area:api,help%20wanted&assignees=MetARverse-Ian" _blank
  click P_INV "https://github.com/GeoARit/Public/issues/new?labels=area:api,invalid&assignees=MetARverse-Ian" _blank
  click P_Q "https://github.com/GeoARit/Public/issues/new?labels=area:api,question&assignees=MetARverse-Ian" _blank
  click P_WONT "https://github.com/GeoARit/Public/issues/new?labels=area:api,wontfix&assignees=MetARverse-Ian" _blank

  click I_BUG "https://github.com/GeoARit/Public/issues/new?labels=area:ai,bug&assignees=MetARverse-Ian" _blank
  click I_DOC "https://github.com/GeoARit/Public/issues/new?labels=area:ai,documentation&assignees=MetARverse-Ian" _blank
  click I_DUP "https://github.com/GeoARit/Public/issues/new?labels=area:ai,duplicate&assignees=MetARverse-Ian" _blank
  click I_ENH "https://github.com/GeoARit/Public/issues/new?labels=area:ai,enhancement&assignees=MetARverse-Ian" _blank
  click I_GFI "https://github.com/GeoARit/Public/issues/new?labels=area:ai,good%20first%20issue&assignees=MetARverse-Ian" _blank
  click I_HELP "https://github.com/GeoARit/Public/issues/new?labels=area:ai,help%20wanted&assignees=MetARverse-Ian" _blank
  click I_INV "https://github.com/GeoARit/Public/issues/new?labels=area:ai,invalid&assignees=MetARverse-Ian" _blank
  click I_Q "https://github.com/GeoARit/Public/issues/new?labels=area:ai,question&assignees=MetARverse-Ian" _blank
  click I_WONT "https://github.com/GeoARit/Public/issues/new?labels=area:ai,wontfix&assignees=MetARverse-Ian" _blank


<table style="border:0;border-collapse:collapse;">
  <tr>
    <td style="border:0;padding:0 12px 0 0;">
      <img src="https://GeoAR.it/images/logos/GeoARIt_517x517.png" alt="GeoAR.it logo" width="80" />
    </td>
    <td style="border:0;padding:0;">
      <h1>GeoAR.it Public Issues</h1>
    </td>
  </tr>
</table>

This repository is the public issue tracker for the GeoAR.it platform.

Main repository: https://github.com/GeoARit

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

## Quick Links

<table class="table table-dark">
  <thead>
    <tr>
      <th>Web</th>
      <th>App</th>
      <th>API</th>
      <th>AI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:web,bug&assignees=MetARverse-Ian&title=i.e..%20Website%20form%20won%27t%20submit&body=i.e..%20Description:%20The%20website%20form%20fails%20to%20submit%20and%20shows%20no%20error."><code>web:bug</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:app,bug&assignees=MetARverse-Ian&title=i.e..%20App%20crashes%20on%20launch&body=i.e..%20Description:%20The%20mobile%20app%20crashes%20during%20startup%20on%20Android."><code>app:bug</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:api,bug&assignees=MetARverse-Ian&title=i.e..%20API%20returns%20500&body=i.e..%20Description:%20The%20API%20returns%20500%20when%20requesting%20venue%20details."><code>api:bug</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:ai,bug&assignees=MetARverse-Ian&title=i.e..%20Genie%20answer%20is%20incorrect&body=i.e..%20Description:%20The%20Geordie%20Genie%20gives%20an%20incorrect%20response%20to%20a%20venue%20query."><code>ai:bug</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:web,documentation&assignees=MetARverse-Ian&title=i.e..%20Update%20website%20FAQ&body=i.e..%20Description:%20The%20website%20FAQ%20is%20missing%20the%20latest%20venue%20editing%20steps."><code>web:documentation</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:app,documentation&assignees=MetARverse-Ian&title=i.e..%20Update%20app%20setup%20guide&body=i.e..%20Description:%20The%20mobile%20app%20setup%20guide%20is%20outdated%20for%20the%20latest%20release."><code>app:documentation</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:api,documentation&assignees=MetARverse-Ian&title=i.e..%20Add%20API%20auth%20examples&body=i.e..%20Description:%20The%20API%20docs%20lack%20authentication%20examples%20for%20new%20clients."><code>api:documentation</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:ai,documentation&assignees=MetARverse-Ian&title=i.e..%20Update%20Genie%20prompt%20docs&body=i.e..%20Description:%20The%20Geordie%20Genie%20prompt%20documentation%20needs%20clarification."><code>ai:documentation</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:web,duplicate&assignees=MetARverse-Ian&title=i.e..%20Duplicate%20website%20issue&body=i.e..%20Description:%20This%20report%20duplicates%20an%20existing%20website%20issue%20already%20tracked."><code>web:duplicate</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:app,duplicate&assignees=MetARverse-Ian&title=i.e..%20Duplicate%20app%20issue&body=i.e..%20Description:%20This%20report%20duplicates%20an%20existing%20mobile%20app%20issue%20already%20tracked."><code>app:duplicate</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:api,duplicate&assignees=MetARverse-Ian&title=i.e..%20Duplicate%20API%20issue&body=i.e..%20Description:%20This%20report%20duplicates%20an%20existing%20API%20issue%20already%20tracked."><code>api:duplicate</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:ai,duplicate&assignees=MetARverse-Ian&title=i.e..%20Duplicate%20Genie%20issue&body=i.e..%20Description:%20This%20report%20duplicates%20an%20existing%20Geordie%20Genie%20issue%20already%20tracked."><code>ai:duplicate</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Feature&labels=area:web,enhancement&assignees=MetARverse-Ian&title=i.e..%20Add%20venue%20filters%20to%20website&body=i.e..%20Description:%20It%20would%20help%20to%20filter%20venues%20by%20category%20on%20the%20website."><code>web:enhancement</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Feature&labels=area:app,enhancement&assignees=MetARverse-Ian&title=i.e..%20Add%20offline%20mode%20to%20app&body=i.e..%20Description:%20Allow%20the%20mobile%20app%20to%20cache%20venues%20for%20offline%20use."><code>app:enhancement</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Feature&labels=area:api,enhancement&assignees=MetARverse-Ian&title=i.e..%20Add%20bulk%20venue%20endpoint&body=i.e..%20Description:%20Provide%20a%20bulk%20endpoint%20to%20fetch%20multiple%20venues%20in%20one%20request."><code>api:enhancement</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Feature&labels=area:ai,enhancement&assignees=MetARverse-Ian&title=i.e..%20Have%20multiple%20Genie%20personalities&body=i.e..%20Description:%20The%20Geordie%20Genie%20Character%20is%20brilliant%20but%20it%20would%20be%20better%20to%20have%20a%20different%20character%20for%20each%20region%20of%20the%20UK."><code>ai:enhancement</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:web,good%20first%20issue&assignees=MetARverse-Ian&title=i.e..%20Website%20starter%20fix&body=i.e..%20Description:%20A%20small%20website%20change%20suitable%20for%20newcomers."><code>web:good first issue</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:app,good%20first%20issue&assignees=MetARverse-Ian&title=i.e..%20App%20starter%20fix&body=i.e..%20Description:%20A%20small%20mobile%20app%20change%20suitable%20for%20newcomers."><code>app:good first issue</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:api,good%20first%20issue&assignees=MetARverse-Ian&title=i.e..%20API%20starter%20fix&body=i.e..%20Description:%20A%20small%20API%20change%20suitable%20for%20newcomers."><code>api:good first issue</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:ai,good%20first%20issue&assignees=MetARverse-Ian&title=i.e..%20Genie%20starter%20fix&body=i.e..%20Description:%20A%20small%20Geordie%20Genie%20change%20suitable%20for%20newcomers."><code>ai:good first issue</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:web,help%20wanted&assignees=MetARverse-Ian&title=i.e..%20Need%20help%20with%20website%20task&body=i.e..%20Description:%20Extra%20attention%20is%20needed%20to%20complete%20this%20website%20task."><code>web:help wanted</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:app,help%20wanted&assignees=MetARverse-Ian&title=i.e..%20Need%20help%20with%20app%20task&body=i.e..%20Description:%20Extra%20attention%20is%20needed%20to%20complete%20this%20mobile%20app%20task."><code>app:help wanted</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:api,help%20wanted&assignees=MetARverse-Ian&title=i.e..%20Need%20help%20with%20API%20task&body=i.e..%20Description:%20Extra%20attention%20is%20needed%20to%20complete%20this%20API%20task."><code>api:help wanted</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:ai,help%20wanted&assignees=MetARverse-Ian&title=i.e..%20Need%20help%20with%20Genie%20task&body=i.e..%20Description:%20Extra%20attention%20is%20needed%20to%20complete%20this%20Geordie%20Genie%20task."><code>ai:help wanted</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:web,invalid&assignees=MetARverse-Ian&title=i.e..%20Invalid%20website%20report&body=i.e..%20Description:%20This%20website%20issue%20does%20not%20appear%20to%20be%20valid."><code>web:invalid</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:app,invalid&assignees=MetARverse-Ian&title=i.e..%20Invalid%20app%20report&body=i.e..%20Description:%20This%20mobile%20app%20issue%20does%20not%20appear%20to%20be%20valid."><code>app:invalid</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:api,invalid&assignees=MetARverse-Ian&title=i.e..%20Invalid%20API%20report&body=i.e..%20Description:%20This%20API%20issue%20does%20not%20appear%20to%20be%20valid."><code>api:invalid</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Bug&labels=area:ai,invalid&assignees=MetARverse-Ian&title=i.e..%20Invalid%20Genie%20report&body=i.e..%20Description:%20This%20Geordie%20Genie%20issue%20does%20not%20appear%20to%20be%20valid."><code>ai:invalid</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:web,question&assignees=MetARverse-Ian&title=i.e..%20Question%20about%20website%20usage&body=i.e..%20Description:%20Clarification%20needed%20on%20how%20to%20use%20the%20website%20feature."><code>web:question</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:app,question&assignees=MetARverse-Ian&title=i.e..%20Question%20about%20app%20usage&body=i.e..%20Description:%20Clarification%20needed%20on%20how%20to%20use%20the%20mobile%20app%20feature."><code>app:question</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:api,question&assignees=MetARverse-Ian&title=i.e..%20Question%20about%20API%20usage&body=i.e..%20Description:%20Clarification%20needed%20on%20how%20to%20use%20the%20API%20endpoint."><code>api:question</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:ai,question&assignees=MetARverse-Ian&title=i.e..%20Question%20about%20Genie%20usage&body=i.e..%20Description:%20Clarification%20needed%20on%20how%20to%20use%20the%20Geordie%20Genie%20feature."><code>ai:question</code></a></td>
    </tr>
    <tr>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:web,wontfix&assignees=MetARverse-Ian&title=i.e..%20Won%27t%20fix%20website%20request&body=i.e..%20Description:%20This%20website%20request%20is%20out%20of%20scope%20and%20will%20not%20be%20worked%20on."><code>web:wontfix</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:app,wontfix&assignees=MetARverse-Ian&title=i.e..%20Won%27t%20fix%20app%20request&body=i.e..%20Description:%20This%20mobile%20app%20request%20is%20out%20of%20scope%20and%20will%20not%20be%20worked%20on."><code>app:wontfix</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:api,wontfix&assignees=MetARverse-Ian&title=i.e..%20Won%27t%20fix%20API%20request&body=i.e..%20Description:%20This%20API%20request%20is%20out%20of%20scope%20and%20will%20not%20be%20worked%20on."><code>api:wontfix</code></a></td>
      <td><a href="https://github.com/GeoARit/Public/issues/new?type=Task&labels=area:ai,wontfix&assignees=MetARverse-Ian&title=i.e..%20Won%27t%20fix%20Genie%20request&body=i.e..%20Description:%20This%20Geordie%20Genie%20request%20is%20out%20of%20scope%20and%20will%20not%20be%20worked%20on."><code>ai:wontfix</code></a></td>
    </tr>
  </tbody>
</table>

## Mermaid overview

```mermaid
%%{init: {"themeCSS": "#WEB_LABELS rect { fill: rgba(220, 53, 69, 0.2); } #APP_LABELS rect { fill: rgba(13, 110, 253, 0.2); } #API_LABELS rect { fill: rgba(255, 193, 7, 0.2); } #AI_LABELS rect { fill: rgba(25, 135, 84, 0.2); }"}}%%
flowchart LR
  R["Choose 1 Area + 1 Type"]

  R --> I["AI Area"]
  R --> P["API Area"]
  R --> A["App Area"]
  R --> W["Web Area"]

  style W fill:#dc3545,fill-opacity:0.2
  style A fill:#0d6efd,fill-opacity:0.2
  style P fill:#ffc107,fill-opacity:0.2
  style I fill:#198754,fill-opacity:0.2

  subgraph AI_LABELS[" "]
    I_BUG["ai:bug"]
    I_DOC["ai:documentation"]
    I_DUP["ai:duplicate"]
    I_ENH["ai:enhancement"]
    I_GFI["ai:good first issue"]
    I_HELP["ai:help wanted"]
    I_INV["ai:invalid"]
    I_Q["ai:question"]
    I_WONT["ai:wontfix"]
  end

  I --> I_BUG
  I --> I_DOC
  I --> I_DUP
  I --> I_ENH
  I --> I_GFI
  I --> I_HELP
  I --> I_INV
  I --> I_Q
  I --> I_WONT

  subgraph API_LABELS[" "]
    P_BUG["api:bug"]
    P_DOC["api:documentation"]
    P_DUP["api:duplicate"]
    P_ENH["api:enhancement"]
    P_GFI["api:good first issue"]
    P_HELP["api:help wanted"]
    P_INV["api:invalid"]
    P_Q["api:question"]
    P_WONT["api:wontfix"]
  end

  P --> P_BUG
  P --> P_DOC
  P --> P_DUP
  P --> P_ENH
  P --> P_GFI
  P --> P_HELP
  P --> P_INV
  P --> P_Q
  P --> P_WONT

  subgraph APP_LABELS[" "]
    A_BUG["app:bug"]
    A_DOC["app:documentation"]
    A_DUP["app:duplicate"]
    A_ENH["app:enhancement"]
    A_GFI["app:good first issue"]
    A_HELP["app:help wanted"]
    A_INV["app:invalid"]
    A_Q["app:question"]
    A_WONT["app:wontfix"]
  end
  A --> A_BUG
  A --> A_DOC
  A --> A_DUP
  A --> A_ENH
  A --> A_GFI
  A --> A_HELP
  A --> A_INV
  A --> A_Q
  A --> A_WONT

  subgraph WEB_LABELS[" "]
    W_BUG["web:bug"]
    W_DOC["web:documentation"]
    W_DUP["web:duplicate"]
    W_ENH["web:enhancement"]
    W_GFI["web:good first issue"]
    W_HELP["web:help wanted"]
    W_INV["web:invalid"]
    W_Q["web:question"]
    W_WONT["web:wontfix"]
  end

  W --> W_BUG
  W --> W_DOC
  W --> W_DUP
  W --> W_ENH
  W --> W_GFI
  W --> W_HELP
  W --> W_INV
  W --> W_Q
  W --> W_WONT

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



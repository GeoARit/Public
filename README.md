# GeoAR.it Public Issues

This repository is the public issue tracker for the GeoAR.it platform.

## How to label issues

Every issue should have **two labels**:

1. **One Area label** (what part of the platform it relates to)
2. **One Type label** (what kind of issue it is)

This keeps triage fast and makes filtering reliable.

### Area labels
- [`area:web`](#areaweb)
- [`area:app`](#areaapp)
- [`area:api`](#areaapi)
- [`area:ai`](#areaai)

### Type labels
- [`bug`](#typebug)  Something isn't working  
- [`documentation`](#typedocumentation)  Improvements or additions to documentation  
- [`duplicate`](#typeduplicate)  This issue or pull request already exists  
- [`enhancement`](#typeenhancement)  New feature or request  
- [`good first issue`](#typegood-first-issue)  Good for newcomers  
- [`help wanted`](#typehelp-wanted)  Extra attention is needed  
- [`invalid`](#typeinvalid)  This doesn't seem right  
- [`question`](#typequestion)  Further information is requested  
- [`wontfix`](#typewontfix)  This will not be worked on  

## Tag structure

The rule is simple:

- **Area** answers: *Where is the problem?*
- **Type** answers: *What is the problem?*

Examples:
- Website login broken: `area:web` + `bug`
- App crash near hotspot: `area:app` + `bug`
- API returns 401 unexpectedly: `area:api` + `bug`
- Geordie Genie response is incorrect: `area:ai` + `bug`
- Improve API docs: `area:api` + `documentation`

## Mermaid overview

```mermaid
flowchart TD
  R["Root<br/>Choose 1 Area + 1 Type<br/><br/>- [area:web](#areaweb) + [bug](#typebug)<br/>- [area:app](#areaapp) + [enhancement](#typeenhancement)<br/>- [area:api](#areaapi) + [documentation](#typedocumentation)<br/>- [area:ai](#areaai) + [question](#typequestion)"]

  R --> W["Web Area<br/><br/>- [area:web](#areaweb)<br/>- [bug](#typebug)"]
  R --> A["App Area<br/><br/>- [area:app](#areaapp)<br/>- [bug](#typebug)"]
  R --> P["API Area<br/><br/>- [area:api](#areaapi)<br/>- [bug](#typebug)"]
  R --> I["AI Area<br/><br/>- [area:ai](#areaai)<br/>- [bug](#typebug)"]

  W --> W1["Web Types<br/><br/>- [area:web](#areaweb)<br/>- [bug](#typebug)<br/>- [documentation](#typedocumentation)<br/>- [duplicate](#typeduplicate)<br/>- [enhancement](#typeenhancement)<br/>- [good first issue](#typegood-first-issue)<br/>- [help wanted](#typehelp-wanted)<br/>- [invalid](#typeinvalid)<br/>- [question](#typequestion)<br/>- [wontfix](#typewontfix)"]

  A --> A1["App Types<br/><br/>- [area:app](#areaapp)<br/>- [bug](#typebug)<br/>- [documentation](#typedocumentation)<br/>- [duplicate](#typeduplicate)<br/>- [enhancement](#typeenhancement)<br/>- [good first issue](#typegood-first-issue)<br/>- [help wanted](#typehelp-wanted)<br/>- [invalid](#typeinvalid)<br/>- [question](#typequestion)<br/>- [wontfix](#typewontfix)"]

  P --> P1["API Types<br/><br/>- [area:api](#areaapi)<br/>- [bug](#typebug)<br/>- [documentation](#typedocumentation)<br/>- [duplicate](#typeduplicate)<br/>- [enhancement](#typeenhancement)<br/>- [good first issue](#typegood-first-issue)<br/>- [help wanted](#typehelp-wanted)<br/>- [invalid](#typeinvalid)<br/>- [question](#typequestion)<br/>- [wontfix](#typewontfix)"]

  I --> I1["AI Types<br/><br/>- [area:ai](#areaai)<br/>- [bug](#typebug)<br/>- [documentation](#typedocumentation)<br/>- [duplicate](#typeduplicate)<br/>- [enhancement](#typeenhancement)<br/>- [good first issue](#typegood-first-issue)<br/>- [help wanted](#typehelp-wanted)<br/>- [invalid](#typeinvalid)<br/>- [question](#typequestion)<br/>- [wontfix](#typewontfix)"]


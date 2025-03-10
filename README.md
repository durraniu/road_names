
# `road_names`

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

## Project Description

An app to find all roads with similar names in US and Canada.

### Required Features

- Enter any road name and find roads with similar names:
  - decide if all roads or just a few e.g., 5 roads
  - decide if speed and any other information should be provided  
  - type of road
- Plot the roads:
  - could be one large map with all roads  
  - {mapgl} based storytelling map

### Challenges

- Querying for similar road names:
  - decide to use a database or {osmdata}/something else  
  - if a database is to be used: {duckdb}/{duckplyr} or parquet files
    with {arrow} and {geoarrow}  
  - bundling data files with app for deployment is a challenge (possible
    to use remote parquet files?)

## Deliverables

**Start date: 2025-02-19**  
**End date: 2025-03-05**

- Day 1 and 2:
  - [x] Initial wireframing. You may use AI tools such as
    [tldraw](https://www.tldraw.com/), [shiny
    assistant](https://gallery.shinyapps.io/assistant/#) or [ploomber AI
    editor](https://editor.ploomber.io/)
  - Framework to use:
    - [x] shiny only
    - [ ] [golem](https://github.com/ThinkR-open/golem)
    - [ ] [rhino](https://github.com/Appsilon/rhino)
    - [ ] shiny + [ambiorix](https://ambiorix.dev/)
- Day 3:
  - [x] First meeting for discussing UI and features
    ([Recording](https://www.youtube.com/watch?v=5XG-MPh0t_A&list=PL3x6DOfs2NGiU6K4FAkVE3y0dZAcaTN3O&index=3))  
- Day 10:
  - [x] Second meeting for discussing deployment
    ([Recording](https://www.youtube.com/watch?v=qo3ge3Qck6Q&list=PL3x6DOfs2NGiU6K4FAkVE3y0dZAcaTN3O&index=4))  
- Day 15 or before:
  - [x] Deployment

## Meetings

Projects start on Wednesdays with meetings on Fridays. We have a shiny
club channel on the [DSLC
Slack](https://dslcio.slack.com/archives/C08A52V98TY) for chatting. Zoom
link appears 10 minutes before meeting on Fridays in the slack channel.
If you’re not a member of DSLC, [join here](https://dslc.io/join).

## How to Contribute

- Fork this repository
- Create a new branch for your feature
- Make your changes
- Submit a pull request
- Wait for review and address any feedback

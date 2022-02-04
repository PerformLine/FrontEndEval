# FrontEndEval
Evaluation Task for Front-End Engineers

## Task
Use the [Met API](https://metmuseum.github.io/) to build a UI allowing users to search for artworks with different criteria.

## The API
The Met hosts a public API of its works. See link above for more info. Some example queries are:
* Get details for one object (artwork): [https://collectionapi.metmuseum.org/public/collection/v1/objects/437406](https://collectionapi.metmuseum.org/public/collection/v1/objects/437406)
* Query objects by a keyword found in the object data, and another field: [https://collectionapi.metmuseum.org/public/collection/v1/search?q=sunflowers&isOnView=true](https://collectionapi.metmuseum.org/public/collection/v1/search?q=sunflowers&isOnView=true)

## Requirements
* Build a clean & usable UI that has three fields to search/filter artwork:
    * (Required) Keyword field where users can search art based on keyword(s) (”portrait,” “flowers,” etc)
    * Century created (1800s, 1300s, etc)
    * Whether the work is in the public domain
* Displays first 5 results.
* Includes in each result: Artwork title, picture, artist name, and where to find it in the museum (department).

### Details
* This task should be doable within a couple hours. It should display JS competency and general UX sensibilities.
* It's up to you which tools and libraries to use, and how to build the UI. Again, functionality/usability is key.

## Deliverable:
* A zip file containing the git repository for your project.
* Instructions for running / hosting the application. It should be able to work in a Linux environment.

# AlfredWorkflow__DevHints-io
Quick and simple Alfred Workflow for launching Cheatsheets on DevHints.io
The workflow is very basic, taking advantage of Ryan's clean and sensible naming convention of https://devhints.io/{sheetname}.

## Requirements
* Requires Alfred for MacOS
* I'm using Aflred v3.5.1. I don't know if earlier versions will work, but this is a very basic flow so I imagine it _should_ run fine on at least any 3.x.x.

## USAGE

Download the workflow and double-click to add it into your Alfred workflows.
After that, trigger Alfred in the usual way and then type "dh" to get started. 

#### dh
Launches the DevHints home page.

#### dh {sheetname}
Launches the DevHints cheatsheet page for {sheetname}

Examples:
dh sass -> https://devhints.io/sass
dh bash -> https://devhints.io/bash

If the requested sheet doesn't exist, you'll end up on the DevHints 404 page which includes a search tool.

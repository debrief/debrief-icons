## debrief-icons

Set of graphic icons for use across Debrief suite of applications

## Standard Colors
* Red :  204 0 51
* Blue : 0 0 51
* White : 255 255 255

## Standard sizes
* 16 px : all icons
* 24 px : all *create* icons: arc, circle, coast, ellipse, etopo, furthest_circles, grid, grid4w, label, line, local_grid, polygon, range_rings, rectangle, scale, track_segment, vector, wheel
* 48 px : *_file.ai

## Workflow
### Initial
1. Designer logs into GitHub
2. Designer forks this repo
3. Designer uses git client (such as SourceTree) to clone the repo to their local disk

### Per-Issue
1. Designer selects (or is given a) GitHub issue
2. Designer does "Pull" on their local copy of the repo  [**SourceTree**]
3. Designer creates local branch from master (something that includes the issue number and a brief summary of the issue subject, like ````issue4_file_types````)  [**SourceTree**]
4. Designer works on .ai icon files locally [**GitHub**]
5. Designer adds changed/new .ai & png files to local copy [**SourceTree**]
5. Designer commits new updates [**SourceTree**]
6. Designer then Push updated branch to GitHub [**SourceTree**]
7. Designer then creates Pull Request [**GitHub**] [see here](https://help.github.com/articles/creating-a-pull-request/)
8. **Project lead(( reviews Pull Request, potenially asking designer to update designs, finally merges updated icons. [**GitHub**] [see here](https://help.github.com/articles/merging-a-pull-request/)

### Post-Issue
1. Switch back to master branch [**SourceTree**]
2. If previous change has been merged, delete local branch that was used for previous issue.  [**SourceTree**]
3. **Pull** updates from the parent repository [**SourceTree**]

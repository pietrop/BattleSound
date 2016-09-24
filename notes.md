#Some notes

## Approach
Designing in balsamiq mockups using bootstrap symbols library and grid system.

Using [Tabletop](https://github.com/jsoma/tabletop) to have google spreadsheet backend. to decouple CMS from front end. 
Drawing and [refining prototype approach from earlier project with WIP interview](https://github.com/pietrop/interactive-transcription-display-proof-of-concept). 

This allows to decouple content from presentation. And easy interface to curate content for non-developers.

## setting up balsamiq with Bootstrap symbols library

[Balsamiq mockup with bootstrap to components](https://blogs.balsamiq.com/ux/tag/bootstrap/).

>The main advantage of pairing a pattern library with Balsamiq Mockups is that it can free you from worrying about look, feel, and behavior when designing yet provide pixel-perfect renditions of the final product components.

[Bootstrap Mockups To Go library](https://mockupstogo.mybalsamiq.com/projects/web/Bootstrap) download [Download BMML](https://mockupstogo.mybalsamiq.com/projects/web/Bootstrap.bmml)

![Bootstrap Mockups To Go library mapping example](https://blogs.balsamiq.com/ux/files/2014/07/mockups-bootstrap.png)

from toolbar, import bml library.
`project` -> `import` -> `BML Symbol library`


[grid bml](https://mockupstogo.mybalsamiq.com/projects/template-bootstrap/grid)

[some more sumbol libraries](https://mockupstogo.mybalsamiq.com/projects)


## Table top 

See table top REAMDE for [instructions](https://github.com/jsoma/tabletop)

[Battle sounds spreadhseet link](https://docs.google.com/spreadsheets/d/1YlaEx8yftVVGlK7dcINtDdHZc3tZi_LUCJUNldtyXws/pubhtml)



## Bootswatch 

"click a [Bootswatch](https://bootswatch.com) theme, last thing you want is for someone to say "oh, you used bootstrap" as that distracts from the experience.


## Sleek transitions

[Fullscreen Layout with Page Transitions](http://tympanus.net/codrops/2013/04/23/fullscreen-layout-with-page-transitions/) also [on github](https://github.com/codrops/FullscreenLayoutPageTransitions)


## Making an Overlay 
[w3c](http://www.w3schools.com/howto/howto_js_fullscreen_overlay.asp)

## github + github pages for demo preview

use github and put project containing `index.html` inside a colder called `docs` in root of project you can set github pages to read/render page from there and get a live demo right there and then.

Make sure your [`.gitignore`](/.gitignore) excludes media file. and store video /audio elsewhere, eg dropbox public folder, or amazon s3 bucket. Don't commit media to git. makes the repo heavy, because of how git stores snapshots of files.




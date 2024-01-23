# annotations24




Steps for annotations conservation


Get csv from kpobosqulite

Drag koboreader.sqlite into folder on desktop.

copy into terminal (on mac) : python3 /Users/astrid/Desktop/export-kobo/export-kobo.py /Users/astrid/Desktop/export-kobo/KoboReader.sqlite --csv --output /Users/astrid/Desktop/export-kobo/KoboHighlights.csv

Upload into google sheets and edit into desired format
	I like to remove the "annotations" - what I wrote and the bookmarks and only keep the highlights
If you would like to do the same:
        delete hi f d. H or I contains the annotations. 
        sort a and remove bookmarks. 
        delete a. 
        move date to first position. 


Follow sortable table instructions

--
	How to added to sortable table

1. Either 

[A] manually add <thead><tr><th title="Field #1">Date</th>
<th title="Field #2">Author</th>
<th title="Field #3">Title</th>
<th title="Field #4">Quote</tr></thead> 

Or 
[B] upload into google docs and modify (style won't carry over but number of columns and title at top of column will. Then download as csv



2. Insert downloaded csv into https://www.convertcsv.com/csv-to-html.htm

3. Open that file in text edit and copy everything below (but not including)

		<table class="table table-bordered table-hover table-condensed">

Into the section indicated by the comments <here to...> <here>






# TreeLine
TreeLine shows your family tree as an interactive horizontal timeline. 

Load a GEDCOM file and you see a person's full ancestor line, siblings, partners and descendants as lifespan bars on one shared time axis. You can see at once who lived at the same time, how generations overlapped, and where data is missing. TreeLine is a single HTML file that runs in the browser. Try it with the built-in sample family or your own export from Geni, MyHeritage, Ancestry or similar.

Most genealogy tools show who is related to whom, but not when they lived. Classic tree charts hide time, so it is hard to see that a grandfather and a great-grandchild shared decades, or that a large group of siblings spread across half a century. TreeLine puts time first: family trees show who, not when. It also finds gaps, listing people with missing dates, places or parents, so you get a research to-do list.

Everything runs locally. Your GEDCOM file is read in the browser with the FileReader API and is never uploaded, stored or sent anywhere. There are no cookies, no tracking and no server-side processing, and photos linked in the file are never loaded. Open the page at hseeberg.github.io/TreeLine or download the HTML file from this repo, pick a .ged file, and click any person to make them the focus.

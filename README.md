# NeoSphere.Live
## Explore the New Smart Economy

At first the map may look familiar to you, however once you take a closer look you see this is not the world you're used to...

NeoSphere.Live is the first visual representation and search portal for the current Neo blockchain global economy. Here you can find information on the latest smart contract and software developments, look for test networks to test your code, find ongoing projects to join, search for the news portals, and explore live running Neo smart contracts.

The portal is hosted through a Github repository and published through github.io. This allows for it to become a community development within itself. Changes can be easily submitted and reviewed, and if for any reason the current host fails, a new one can easily be setup, this provides a level of security, redundancy, and transparency, as the community involved becomes a democratic force, unrelying of the original host.

It is light-weight, being mainly designed on JQuery and CSS. This allows for easy developments, client side rendering, and speed.

The future of NeoSphere will include elections to determine important decisions regarding the overall community. These will be hard coded into the Neo blockahin. Implementation and details TBD.

More information to come so check back regularly...

* This is a work in progress and is not ready for live implmentation yet, information may be incorrect or unavailable from moment to momeent. 
* FORK THE REPO! Get involved, if you see something to be improved on don't hesitate to mark your place in NeoSphere history.

## Roadmap, from this point...

* Fix bugs, Finalize system of governance, Elect the initial Government...

- Design needs to be worked on to better represent the NEO brand. I feel like the vintage look is simplistic but not overall appealing, it allows for the colors of the avatars and business logos to pop, but doesn't click the the NEO brand just yet. Editing colors is a matter of editing a few PSDs and CSS code.

- There needs to be an easy mechanism for the addition and editing of smart contract listings. Logo 100x100, status img (live, inProgress, or concept.png), author name, etc. There are little colored icons used to represent this on the listing. There needs to be a database of sorts that can be cloned regularly and available to all, Github seems like the perfect setup, but there may be better options.

- The mapping framework needs to be improved. Right now the icons are hardcoded into pixel places, if the user resizes their screen, the icons do not follow the map re-rendering, a small JS snippet was added to simply reload the page so it all reloads together and the icons show up in their proper places. This has introduced a new problem. On mobile browsers, scrolling triggers the reload sometimes when not needed.

-- Also, I am still trying to think of the proper way to handle the avatars on the map. Creating a system where users can zoom around would begin to introduce a lot of bloat to the system, not to mention the point of the map is to provide visualization and interactivity, but not become THE place to be looking around. Clicking on a country will load its list of developments, this is where the true information is.

--- I think one of the best ways to deal with an overloaded and messy looking map is to only allow live projects to have an icon on the map, sponsors to only have an icon (the funds can go to locked charity contract, viewable by the community), user voting on the most popular or most useful developers, etc. If we have too many icons in one area, we can introduce a fadein-fadeout feature to scroll through a list of icons around that area of the map. TBD.

If there are any question please feel free to contact me at:
http://www.reddit.com/u/cplusconcepts
http://www.reddit.com/r/antshares
http://antshares.slack.com 

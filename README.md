<a href="http://jlord.github.io/forkngo"><img src='https://github.com/jlord/forkngo/blob/gh-pages/badges/charcoal.png?raw=true' width="200"></a>

# Federal Government

This is a [website](https://jlord.github.io/federal-gov) generated from a [Google Spreadsheet](https://docs.google.com/spreadsheets/d/17H2IL-o2G-JAwaukZCZ0aCfL09nEthZb_EUrB3wikwY/edit#gid=0) of articles about the actions of the United States Federal Government in 2017.


---

## Why

There are a lot of things happening daily as a new administration prepares to take the helm of the US Government. I see links scattered throughout my social media feeds and I wanted to try consolidating these things in a way where I (and others) might be able to see the breadth of what's going on in a simplified but informative way.

### Selection

I am selecting events which challenge the way the US Government functions. Right now these are broadly categorized by what it is that made each event newsworthy: Is it an illegal conflict of interest? Is a lie? Does it intend to hinder the normal functions of the government? Is it a shocking break with convention? If the government does something good that's great, but those aren't the things to cover here. Feel free to [fork this repository and create that site](http://jlord.github.io/forkngo) if you so desire.  

### Sources

Right now the information is added by me to a spreadsheet manually as I read about events either through my social media feeds or directly from the publication.

#### Week 1

Since I'm starting this a week into the new year, I used an [existing list of events](http://textuploader.com/ddzqv) (which were [derived from this tweet](https://twitter.com/sarahkendzior/status/818547688383848449)) to cover last week.

### Presentation

The way the information is presented on the site has to do with some experiments that were in my head.

#### Simplify Information

Similar to my [Essential Electron](http://jlord.us/essential-electron) project, I wanted to challenge myself to simplify as much as I could. Of course full articles for more in depth information is provided.

#### Don't use names

Rather than use proper nouns, I'm using titles or relationships. Abstracting them one level seems more like the reflection on the country as a whole and our government rather than an individual, which is interesting to me.

## Future

I want to experiment with formats more (calendar? table?) and add sorting and filtering.

## Technical

This site uses a band-aided version of my [sheetsee.js](https://github.com/jlord/sheetsee.js) (I am gonna be refreshing the project soon!) library and tabletop.js to visual data from a Google Spreadsheet.

### Want to use the data in your project?

The data from the spreadsheet is public and accessible through this Google Spreadsheet key: `17H2IL-o2G-JAwaukZCZ0aCfL09nEthZb_EUrB3wikwY`. You can use the Google API to work with it or a library like [Tabletop.js](https://github.com/jsoma/tabletop) which will return the contents to you as nice, clean JSON.

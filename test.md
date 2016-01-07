# Google Analytics Account Info

--

**Navigation**  
[Account Name](#account-name-as-df)  
[Properties](#properties)  
[Production Views](#production-views)  
[Account Views](#account-views)  

--

### Account Name: `as df`

### Properties

Each Property has a tracking id associated with it.  It functions as a tracking unit, typically a website or mobile app.  All the tracking data is stored in the same location and can be compared.

The following outlines our current Property structue _(each has a dev, qa, and production property to keep our data sets clean)_ :

* Web
  * `asdf`
  * `asdf`
* Mobile
  * `asdf`
  * `asdf`


### Production Views
Each production property has by default 3 views.

* `Unfiltered Data`
* `Test View`
* `Master View`

Once filters are applied to views, the data for that view can never be “re-filtered”.  As such we keep an **unfiltered** view in case we ever need to find data that a filter/view combo accidentally excluded.

The **test** view is, as expected, a place to test filter applications, and make sure they are the changes we want before filtering the master view.

The **master** view is the view we care about the most.  It contains the “best” data and is what we observe on a regular basis to see if we are hitting our metrics goals.

--

#### A Note on Web Production Views
I have selected the exclude known bots and spiders from web traffic for the master views of Giving Center and Planner.  This provides a good understanding of what it is and why I did it: [Understanding Bot and Spider Filtering from Google Analytics](http://www.lunametrics.com/blog/2014/08/07/bot-spider-filtering-google-analytics/).

--

### Account Views



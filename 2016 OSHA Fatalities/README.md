Courtesy of <a href="https://www.osha.gov/dep/fatcat/dep_fatcat.html">the official OSHA website</a>, I compiled the data on reported 2016 fatalities in a few different ways

Firstly, there's the raw data, in order by date. Each row contains the date, victim name (if available), description of death, company, city, state, and zip code. This sheet is simply just the data given by OSHA.

In the next sheet, I wanted to find fatality reports by state. To do this, I took the state abbreviation, manually paired it with the full name, and counted each occurance. I used Google's graphing utility and <a href="http://mapinseconds.com">mapinseconds.com</a>, a site I found on Reddit.

Next, I took the ZIP code & State abbreviation to find each occurance's county. Using this information, I first found how many times each ZIP code came up; but I found this to be almost useless as there can be many ZIP codes in every county. To get around this I used my findings on each county, along with a few different Sheets' addons and a lot of VLOOKUP, to find each occurance for a county-state pair. Then, I converted the county-state pair to a FIPS county code in order to use mapinseconds once again.

Now in the next sheet I wanted to sort by cause of death. The only reliable way to do this was to count each occurance of a few key words (fall, bee sting, etc.) in the raw descriptions. Because key words may show up a few times, and I wanted to keep this as simple as possible, this isn't an exact measure; but it is pretty darn close. I simply used a Google Sheets' pie graph for this.

Lastly, I wanted to graph by month of each fatality. This is self explanatory, but the results are pretty interesting. I want to combine this with cause of death when I have time in the future.



<h3>Here is <a href="https://docs.google.com/spreadsheets/d/1Kjtj9YobdI9CYt29luJYt91c00kMsYqPxVfytDY9sKw/edit?usp=sharing">the link</a> to my Google Sheets, and I have also included a few ways to download the data in this folder.</h3>

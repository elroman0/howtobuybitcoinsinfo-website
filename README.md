# Official [HowToBuyBitcoins.info](http://howtobuybitcoins.info/)

![HowToBuyBitcoinsInfo](https://s3.amazonaws.com/s3.luxstack.com/github/howtobuybitcoins/howtobuybitcoinsinfo.png)

---

Hey everyone,

We're working hard to roll out a new and upgraded site for [howtobuybitcoins.info](http://howtobuybitcoins.info/) with a lot of new features and realtime data.

Rest assured, you can still contribute to the services.yaml file! These changes will be merged into the new site design.

We're also including realtime feeds for exchange prices - if there's a public exchange price feed we don't have, let us know.

We're the **original**, and most **high-traffic** site for discovering how to buy bitcoins... and with the new version, [howtobuybitcoins.info](http://howtobuybitcoins.info/) will continue to be the BEST PLACE to learn how to buy bitcoin... hold onto your hats!

Jonathan Waller @ [LUXSTACK](https://luxstack.com/)  
[howtobuybitcoins.info](http://howtobuybitcoins.info/)


---


## File Format

For easily merging pull request specially *services.yaml*, Unix line endings should be used (LF).

## services.yaml

Simple edits can be done following yaml rules.  

**uniquename** - this would be the identifier entry, no spaces is allowed

**label** - title of the site
	
	label: Awesome Exchanger

**countries** - please see website for the code of country, example entry.
  
	countries: [us, uk] 

**icon** - url of the favicon.ico of site, don't include if you dont have one.
	
	icon: http://example.com/favicon.ico

**url** - url of the site, or any page of your site.

	url: http://example.com 

**content** - description of the site.

  Single line

	content: Single line
  
  Multi line - Scalar content can be written in block notation, using a literal style (indicated by “|”) where all line breaks are significant.  These should be also indented two spaces.

	content: |
	  Multiline indented two spaces
	  Second line
	  Third line
 
**coins** - accepted crypto currency

	coins: [btc]



Example Entry:

	sampleexchanger:
	  label: Sample Exchanger
	  countries: [us, uk] 
	  icon: http://sample-exchanger.com/favicon.ico
	  url: http://sample-exchanger.com
      content: |
		The most awesome exchanger in the planet
        Everyone should agree
	  coins:
	  
	  
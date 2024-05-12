
![hacker-2300772_1280](https://github.com/Th3l3mic/OSINT/assets/167564930/e5e64de3-fc87-415d-96f4-d3f3c3dadb88)

# Darkweb OSINT

* <h2>Search engines:</h2>
  - some of this search engines works both in clear, and dark net. Have different functionalities, so it's strongly recomended for use more than one search engine
* <p></p>
  Ahmia <code>https://ahmia.fi/</code>
  <p></p>
* Tor66 <code>tor66sezptuu2nta.onion/</code>
* Torch <code>torchdeedp3i2jigzjdmfpn5ttjhthh5wbmda2rr3jvqjg5p77c54dqd.onion/</code>
* Haystak <code>hss3uro2hsxfogfq.onion/</code>
* Not Evil <code>hss3uro2hsxfogfq.onion/</code>
<p></p>
<h2>Dark links:</h2>
  - list of dark links could be good starting point to recon, remember that some of onion pages collected on lists, may get shut down
  <p></p>
* Dark.fail <code>https://dark.fail/</code>
<p></p>
* Hiiden Wiki links <code>https://thehiddenwiki.org/</code>
<p></p>
<h2>Using Shodan and Censys search for gathering information</h2>
<p></p>
* There's a multiple way for gathering darkweb informaction, especially when we talk about site's and services. One of the best way is to paste onion site adres into search engines like Shodan. We could receive lot of useful information for example target location, and possible header's for deeper search.
<p></p>
<code>shodan.io</code>
<p></p>
<code>https://search.censys.io/</code>
<p></p>
<h2>Favicons</h2>
<p></p>
 - in case of darkweb site's it's also possible to search hosting servers via favicon search. First get the favicon image, than calculate the hash with online service on python script, for example use this site: <code>https://favicon-hash.kmsec.uk/</code>
 <p></p>
 Next paste query in Shodan:
 <p></p>
 <code>http.favicon.hash:PasteYourHashHere</code>
 

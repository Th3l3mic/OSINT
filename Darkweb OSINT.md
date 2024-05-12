
![hacker-2300772_1280](https://github.com/Th3l3mic/OSINT/assets/167564930/e5e64de3-fc87-415d-96f4-d3f3c3dadb88)

# Darkweb OSINT

* <h2>Search engines:</h2>
  - some of these search engines work both in clear, and dark net. Have different functionalities, so it's strongly recomended to use more than one.
* <p></p>
  Ahmia <code>https://ahmia.fi/</code>
  <p></p>
* Tor66 <code>tor66sezptuu2nta.onion/</code>
* Torch <code>torchdeedp3i2jigzjdmfpn5ttjhthh5wbmda2rr3jvqjg5p77c54dqd.onion/</code>
* Haystak <code>hss3uro2hsxfogfq.onion/</code>
* Not Evil <code>hss3uro2hsxfogfq.onion/</code>
<p></p>
<h2>Dark links:</h2>
  - list of dark links could be good starting point to recon, remember that some of onion pages collected on lists may shut down
  <p></p>
* Dark.fail <code>https://dark.fail/</code>
<p></p>
* Hiiden Wiki links <code>https://thehiddenwiki.org/</code>
<p></p>
<h2>Using Shodan and Censys search for gathering information</h2>
<p></p>
* There's a multiple way for gathering darkweb information, especially when we talk about sites and services. One of the best way is to paste onion site adres into search engines like Shodan. We could receive lot of useful information, for example target location and possible headers for deeper search.
<p></p>
<code>shodan.io</code>
<p></p>
<code>https://search.censys.io/</code>
<p></p>
<h2>Favicons</h2>
<p></p>
 - in case of darkweb site's it's also possible to search hosting servers via favicon search. First get the favicon image, then calculate the hash with online service or python script, for example use this site: <code>https://favicon-hash.kmsec.uk/</code>
 <p></p>
 Next paste query in Shodan:
 <p></p>
 <code>http.favicon.hash:PasteYourHashHere</code>

 <h2>Bitcoin chain explorer</h2>
  * In case when we want to check autheticity of a dark web market we could use bitcoinchain explorer for checking if this site is valid or not. 


<h2> Analyzing photos </h2>
<p></p>
* Use reverse search for analyzing photos that you found on darkweb site, via reverse search:
<code>https://images.google.com/</code>
<p></p>
<code>https://yandex.com/images/</code>
<p></p>
For better result's always use multiple search engines.
<p></p>
* Exif data
- use sofware or online tool for reading exif data
<p></p>
<code>https://exiftool.org/</code>

<h2>Analyzing source code</h2>
 - always check the source code of site for comments, mails, usernames and other information that could be potentially useful for your investigation

 <h2>Darkweb investigation Tools</h2>
 <p></p>
Onion Scan<code>https://github.com/s-rah/onionscan</code>
<p></p>
TorBot<code>https://github.com/DedSecInside/TorBot</code>

There's always more, but above I've presented methods that I use a lot during my "DarkWeb investigations". Big thanks for Osint DOJO channel for great resources and doing high quality content.

T.

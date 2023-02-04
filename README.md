# Webscraping Tours

A showcase of how you can scrape data from a website using SQLlite and selectorlib and automatically sending an email everytime a new event is coming up. 

Here is a version of this app where I used object-oriented programming:
https://github.com/Nandras993/Webscraping_Tours_SQL_OOP

## Legal Notes:

Please take it into consideration, that doing webscraping from publicly available website is <b>usually</b> not illegal but you can still collide with the law.

<b>[Disclaimer] I am not a lawyer, but my understanding concerning the rules of the road are as follows:</b>

1)  Wherever you live, your local laws determine which behavior is considered legal or illegal.

Applicable laws vary from country to country but these are easy to research. It does not matter at all what the law says somewhere else in the world. It only matters what the law says where you live.

2)  Most often, it's how we use our scraped data that determines what is legal or illegal.

Where I live in the United States, I can legally scrape the listings of real estate properties from Century21·com, for example. What I shouldn't do is scrape their public website data to build a competing website that I'll call BetterThanCentury21·com. For that, I'd expect to be sued and to quickly lose in court.

3)  Academic or business research data is collected by legally scraping websites, government resources, or social media sites.

In most countries or maybe even all countries, non-harmful scraping is legal. It's called research. Scraping is legal for an app developer. It's legal for a business with or without a profit motive. It's legal if I want to scrape websites just for fun.

4)  I can build my own website with the data that I've scraped.

Or I can blog about my scraped data. But I must be careful with how I plan to use my new data. It would be foolish of me to use my scraped data to start a business that will be in direct competition with the original source of the data. Even short of competing within the marketplace, there are other ways that a business might be harmed. Corporate lawyers love this stuff, so be a bit careful here.

5)  Do your research before scraping a website.

Before scraping any website, become aware of the website's history within the court system. Maybe a website's lawyers are known for taking web scrapers to court. Though it's not a widely held view, some websites might view simple website scraping as an "act of infringement" upon their "product".

6)  A website's typical response is probably not to take someone to court.

Everyone knows that people build websites hoping that the public will come browsing. Whether it's browsing with eyeballs or using a script shouldn't really matter, in many people's opinion. If a website were to take a simple case of web scraping to court to claim that there was harm involved, usually that website will be arguing a tough-to-prove case before a doubtful judge. Instead, websites would rather just block web scrapers from accessing their website.

7)  A script that scrapes website data is by definition called a "bot".

It's often relatively easy for websites to detect and block bots from accessing their website. In most countries, this is normally the first and only response that bot developers like us should expect.

8)  Some websites may try to warn or punish their registered users who scrape even a tiny amount of their data.

In those cases where you have a registered user account on their website, they might send a warning message if they catch you scraping. They might even suspend/cancel your account. For repeated infractions, a website could choose to block your IP address without notice. Every website with a registered user base will have a Terms of Service [TOS] agreement that you should study closely if you're one of those users. That will tell you more about whether scraping behavior by a registered user is considered to be a TOS violation or not.

9)  Every url request made to a web server will probably cost that server's operator either money or other resources.

When my script is actively scraping a website, real humans who are browsing that same website may experience a slower response or no response at all. It is often the case that a website will need to buy more cpu cycles, server nodes, or equipment to accommodate even short spikes to their web traffic. Many websites will have an arrangement with their hosting service where they can pay to automatically scale up performance to meet extra demand. If they don't have that arrangement, the web server could theoretically be cut off, rate-limited, or otherwise restricted until they cough up some cash.

10)  Scraping website data can either be done in a rude manner or in a polite manner.

Fortunately, there is a simple way to code our scraper bots to be polite. We always need to include a time delay between every url request. We certainly don't want to crash their website or overwork the website's server resources. But whether our bots are rude or polite will not change the fact that websites will usually just block all bots.

11)  Sustained periods of many url requests done very quickly could be considered to be a Denial of Service [DOS] attack.

Initiating a DOS attack would in many places be considered to be illegal behavior. Never do this under any circumstances. For more info on how to avoid this, refer to the previous point.

12)  In addition to building polite scraper bots, we can try one or the other of the following.

If our script is being blocked, we can attempt to disguise the fact that our script is a bot and isn't a human. This is often not very difficult to accomplish. Simply do a search for "python scrape user-agent". Alternatively, we can send an email that politely asks to prearrange permission to scrape data. But this is probably a waste of time unless you already have a special relationship with that website.
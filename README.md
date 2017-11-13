# intro
About `The ICO Street` project and updates

`The ICO Street` started off as an idea for Product Hunt Hackathon - https://www.producthunt.com/hackathon. Being co-developed by [@souravray](https://github.com/souravray) & [@jitinp](https://github.com/jitip), this is our humble attempt to contribute to the Blockchain ecosystem. 

One of the most promising concepts so far from the Blockchain ecosystem is ICO (Initial Coin Offering). ICO democratizes money and access to capital in ways unimaginable. But with this great promise also comes noise, chaos and scams. While some great projects and ideas are being built using ICO, lot of them are in it just for quick money. One look at their websites and whitepapers gives away their intention to run a scam and thereby depriving deserving companies of this golden opportunity.

With **`The ICO Street`** our mission is two fold: 
1. Bring some order to this chaos
2. Filter out the scams (a more difficult job)

The first product that we are building is the `Street` iOS app. Using `Street` you can track and monitor ICO pre and post sale, thereby enabling you to make educated decision whether to buy or sell. 

**How we intend to do it:**
1. Track ERC-20 tokens of ICOs for total volumes of Tokens being traded and their values against Ether (1 unit Ethereum)
2. Enable Instant Notifications and Alerts for ICO tokens above and below certain Threshhold 
3. Track KPIs (Key Performance Indicators) like Website Traffic, Mobile app downloads, or any other relevant metric for each ICO
4. Track Klout score and other indicators from Social Media and Social channels like Slack, Telegram, Reddit for each ICO
5. Correlate KPIs, Klout Score and other indicators with ICO Token performance on Token Exchange. Draw relevant patterns and help make investors educated decisions
6. Consume Whitepapers and their Website Content of each ICO, draw patterns and correlate with its overall performance on Token Exchange, KPIs and Klout Score

**Steps to achieve this:**
1. Scrape list of ICOs across the Web for their Currency Symbols, Github URLs, Websites, Twitter, Facebook, Slack, Telegram, Whitepapers
2. Fetch ERC-20 token address from Etherscan networks using currency symbol or website. 
3. Using the Token address, plug into Ethereum blockchain network and monitor total tokens being traded and its value against Ether
4. Provide this information to users via Mobile App as a Graphical representation
5. Enable users to set upper & lower threshhold for each ICO to receive instant notification
6. Consume KPIs & social media klout for each ICO and display it as a graph against Token performance Graph
7. Index ICO Website content and Whitepapers into Elasticsearch and segment them into different categories 

In the spirit of other projects in Blockchain space, we will make most of our contributions open source and available to everyone under MIT license. 

Do subscribe to **`Street`** app for regular updates here - http://theicostreet.com

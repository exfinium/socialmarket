# socialmarket
Market regulated social network concept where the ranking mechanism is based on giving tangible value.

## What is it?
An ordinal ranking system for internet content that takes ranking input exclusively from voluntary payment of tangible value to the collective common.
## What is it for?
More meaningful skin-in-the-game content ranking/curation.
*	It replaces zero-cost end user ranking methods (like, thumbs up/down) with tangible-value end user ranking so that the resulting rank represents the real value committed to the relative rank of each item.
*	It also replaces human and AI based content moderation or curation with the same tangible-value end user ranking, effectively relying on the collective user base to elevate the desirable and suppress the undesirable.
## How does it work?

### Conceptually:
It leverages market dynamics and spontaneous order to sort online content according to the revealed preferences of the participants in the market.  The exact character of the resulting order isn’t predictable but the more open and accessible the resulting data the more sophisticated and valuable the resulting experience is likely to be.

### Machinery:  
*	The defining function is the processing of a transfer of proprietary currency from a user to every other user and that is linked to a content ranking event, influencing the rank of a single item. The service facilitates the secure maintenance of this single ranking metric but exposes the means for users and third parties to filter and prioritise content based on keywords and other metadata both within and external to the service.
*	The item database keeps, for each content item, an item reference record and a ranking record and it processes ranking events.  Item records are small and generally contain a link to external content or very short form text as well as related metadata like authentication hashes and keywords. The ranking record contains a simple number representing the sum of ranking events for that item. Ranking events are an adjustment to the current ranking value of the item proportional to the amount paid for the transaction.
*	The currency database maintains a proprietary currency, keeping a balance record for each user and processing ranking and exchange transactions.  The currency optimised for processing extremely small transaction values at extremely low transaction processing costs.
*	The application interface exposes the data within the item and currency databases and provides methods for customised searching of them.  It also provides methods for authenticating, securing and processing ranking events and content record creation or modification.
*	The service provides a single universal rank metric that applies to all content items but exposes the means to filter and prioritise
### Practically:
*	In general usage the experience needn’t be any different than a single click of a typical “like” button.  The difference will be an awareness that that click involves a small transfer of tangible value.
*	A new user to the service will need to complete an account creation process involving creation of authentication credentials and a user profile and then transfer a minimal amount of money to set up a currency account.  The system makes no categorical distinctions at all between users and exposes all functionality to all users. Creator, browser, advertiser, influencer, is all the same to the system itself.
*	There will be a user facing application (both web and app versions) that will provide all the basic functions required to engage with the service.
*	Third party content services will be encouraged to integrate this service into their designs to take advantage of market curation.  They will no doubt vary in levels of integration and exposed user control.  A browser addon could potentially overlay system features on non-participating web pages.
*	Individuals will also be able to integrate the service into their own websites or forum posts using simple accessible tools.
### Operating costs:
*	The system provides for advertisement spending but only inside the ranking system itself, meaning advertisers will pay the people, not the platform.
*	User data in the form of habit and preference statistics is another common revenue stream but this system exposes this data to all as a part of its regular function.
*	The ability to process microtransactions presents an opportunity for very precise micro-billing and a truly representative user-pays scheme with heavy users of the system paying a proportional share of the costs.
*	Traffic and cloud costs can potentially be billed on a per byte or per watt-hour basis and charged on a per interaction basis.  In practice a user’s account could be charged immediately for each interaction with the system with a typical charge being a tiny fraction of a penny.
*	Extreme heavy use cases would be supported such as “fire hose” feeds or constantly updating or complex database queries with the relative cost being charged immediately and directly to any user that deems such activity worth the price.
*	Functional business units responsible for the various components will run on a break-even budget with rewards for improving service quality and efficiency.
*	During the initial start-up period of the service transaction costs may need to be subsidised to reasonable levels by a capital advance.
The economics: 
*	The ranking transaction is superficially a zero-sum unidirectional transaction, a payment to the common for influencing content exposure, leaving every other user slightly richer but leaving the total market no richer or poorer.  Wealth creation within the system will be apparent if people choose to transfer currency into their account and use it to promote content AND enough people find the resulting curation worth the cost of participation.

...tbc

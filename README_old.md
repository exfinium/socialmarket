# social market concept

Social market is a pure market-based curation service enabled by frictionless micropayment technology.

The primary and fundamental transaction provided by the social market service is named a pip.  A pip is a payment from an individual participant to the common in exchange for influencing the ranking of a piece of content.  It is effectively and literally paying all market participants for the right to exert a measure of influence on the ranking of the content available on that market.  Pips and the resulting ranking data are the entirety of the necessary conceptual machinery that drives this curation system.  The resulting curation is driven entirely by the distributed knowledge, will, and material value invested by participants in the market. There are myriad possible variations in the implementation of this service but the soul of this concept is entirely contained in the pip transaction and it’s implications.

This proposal will lay out one possible complete implementation based on an anti-coercion ideal and unimpeachable ethics.

[Questions](https://github.com/exfinium/socialmarket/blob/master/questions.md) | [Objections](https://github.com/exfinium/socialmarket/blob/master/objections.md) | [Hard Problems](https://github.com/exfinium/socialmarket/blob/master/hardProblems.md)

## Principles
### Meaningful communication
Humans are generally more thoughtful and intentional when the stakes are tangible. By requiring interactions in a public forum to be backed by tangible value the hope is to facilitate more meaningful communication.
### Spontaneous order
Provide a place for people to communicate and reward the communication of others and various patterns of talent and cooperation will emerge.  If that place is devoid of arbitrary external regulation it will nevertheless become regulated by the sorting of the values of the participants. This system is technically and constitutionally geared for absolutely no editorial, economic, or social intervention.
### Proximal price
Everything has a cost, a value, and a price.  Many things seem free because the actual cost is hidden elsewhere.  This system will make every effort reveal all costs proximally and specifically.  Instead of a "free" service it will be an exceptionally cheap "user pays" service. As a consequence the participants are firmly the customer and not the product.
### Secrets impede trust
Secrets are important to people for various reasons.  This project will honour participants' dignity by clearly and loudly declaring this place as devoid of any safe spaces for secrets.  It is unapologetically and completely public. Every single post and transaction will be viewable by any participant and freely transferrable to the public at large.  Degrees of anonymity remain possible but if one values it highly then this place is not an ideal choice.
### Pure universality
Every participant and every idea has equal opportunity and no person, group or idea will be granted privilege or penalty by the system itself. There will be no moderation of content by human or AI and no method of appeal to censorial authority.  The system will simply uprank the most valued and downrank the least valued content and give participants the freedom to choose how that ranking applies to their feed.
### Positive credit
The system does not allow the taking of credit - only the giving of it.  Negative feedback exists but when you pay to disapprove of a post the payment goes to the common and lifts everyone's balance.  Paying to elevate your own posts does the same.
### The common
Payments to the common increase the spending power of the system currency, effectively and literally enriching everybody. Symbolically, payments to the common are material consideration in exchange for exerting a measure of imposition on the market.  It does not grant a right to anything in return beyond nudging one metric the participants can use to influence their feed.
### Deliberately simple
There exists no system that can guarantee a desired outcome from human interactions.  This system provides only two levers of power available to all participants; credit, and words.  While additional measures may give people access to more nuanced influence, no amount of additional machinery can make the system fairer.

## Technology
### Microtransactions
To facilitate frequent proximal frictionless exchanges of value with sufficiently minimal overhead requires the implementation of a grade separated currency, similar in principle to currencies found in many persistent computer game worlds.
### Floating exchange rate
Value tokens within the system will not be pinned to any real world currency and will instead be regularly or constantly adjusted to follow the mean transaction value.  Account balances will be accounted as a share of total capitalisation of the market.
### Databases
There will be user, post, and transaction databases that should be fully searchable directly by all participants.(for a fee based on running cost) User created queries should be easy to share and run.
### API third party direct interface
It will be possible and encouraged for third parties to integrate the system into their own content platforms.  The core organisation running this system may even not directly provide a user facing content application.


## Hypothetical break even milestone.
* 1,000,000 registered users
* 1,000,000 daily posts @ ~$0.01
* 100,000,000 posts viewed daily @ ~$0.00001
* 1,000,000 post ranking transactions @ ~$0.000001
* $11,100 daily income
* $11,100 daily operating expend (including amortized capex)
* $0.0111 average daily user cost

## Transactions:

Pip (give social appreciation)
* transfer value to the common
* elevate a post's ranking

Kip (give social depreciation)
* transfer value to the common
* suppress a post's ranking

Tip (give material credit)
* transfer value to the receiver
* no effect on ranking

User account create / modify
* authentication credential
* database record 
* payment processing

User logon
* credential processing

View posts
* run query
* transmit data

Create post
* database update
* web host (maybe)

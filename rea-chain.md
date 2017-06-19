# The REA Chain #

The Resource Event Agent (REA) accounting model is a way of recording economic events that avoid the traditional problems of double accounting and also the creative accounting. 

The double accounting is the classic accounting system where every agent keeps track of his/her own outgoing and incoming economic movements, like sells and buys, and they should match with the other agents accounting of facts. For example, if i'm a company buying materials from a provider, I will account my outgoing buys and the provider will account its sells to my company. These two lists of movements (my buys and the provider's sells to me), must match exactly because they refer to the same economic events. Sometimes these two lists didn't match perfectly, mainly because they are tracked separate by different authors, contexts and time-frames. 

Also the 'creative accounting' refers to the fact that some events in that two lists are sometimes created only by one of the parties, and is missing in the other side accounting of the other party, or the details (amount, etc) didn't match, so 'inventing' events is possible.

The REA approach keeps track of single economic events between agents (parties) which move resources (or change ownership, etc). These single economic Events always has two sides: say for me is 'buy' and for you is a 'sell', but they both are the same event. That makes accountability a transparent common fact, traceable and not manipulable by a single party.

The REA model was introduced by Bill McCarthy in 1982 and has been developed and applied by many others after him. Specially Bob Haugen and Lynn Foster from mikorizal.org have used this model to develop the original NRP and the ValueNetwork software which is the source code of the new OCP (Open Collaborative Platform), a fork developed mainly by me and @XaviP (thanks to FairCoop) with a lot of help from @bhaugen and @fosterlynn, to be used by FreedomCoop, and now also used by the Bank of the Commons. All them international cooperative platforms which share the will of using the REA accounting model, among other shared nice goals and principles. The dev team is getting bigger with @pospi and the contributions from @escanda and @ivanminutillo amongst others, trying to join forces and merge different forks in the same repo.

One of the facts of the REA model is that **it really makes sense only if the database of economic events is shared amongst parties**, in a kind of shared database of events. The way it's being developed the OCP is to be able to comprehend many parties (economic agents or projects) and contexts (bigger projects or sectors of activity) so a useful common REA stream of events can be recorded in the same database. That means also to create a common set of resource types, skill types, units, exchange types, etc, which is a challenge work-in-progress being developed by the community when the needs arise.

To have a common stream of REA events in a shared database, is useful if you want to **track some Values** related the economy. Here I don't refer to numeric values but to humanistic natural life Values, like Fair trade, Organic farming, Human Rights, Non-profit, Social, etc. To really have any of these Values is needed a control system where the resources can be traced from the source materials and worker hours to the finished products for sale, exchange or gift.

Also a common stream of REA events is useful to build on top of it **a reputation system**, also called dharma or trust, which is for the entities but can be calculated related the resources used, their procedence and the human working facts. If the system can track how much ecologic or how much social is a project or product, that can be a kind of automatic reputation. Even more, to track for example how much work time invested to common good goals, tuned by the quality of results, how much resources used for that, etc, all this can create a kind of automatic personal reputation or dharma for any agent in the system.

Actually the OCP works on a Postgres database in the production server, but the conceptual design is meant to be used by many parties and sectors of activity, so the database will become huge as soon the platform is being used by many projects. For the real implementation of the Values and the success of the platforms, **we need to implement ASAP a really scalable database system**. 

The Holodata project tries to focus on that backend challenge using modern distributed databases (there's a dev plan, but I want to form a dev team, find time and fundings). The other needed thing is an integral data-structure like the one proposed in the GeneralApp, to have common data and data types we can share amongst many agents (there's an initial plan, but is needed to join a taxonomy team worldwide, by sectors, etc).

In the Holodata distributed database will be recorded the common data, structured by an integral common data types scheme. The stream of economic events can be recorded in separate projects databases and servers (or in the same common holodata database), but what makes more sense for me is to build what i'm calling **the REA Chain**.

The blockchain database systems are good for recording non mutable data, and there's a moment in the REA events shared accountability where all related parties agree on an economic fact that happened. From that point, the event can be recorded 'in stone' for the history in a kind of blockchain. The cryptocoins transfers are already recorded and readed in the existent blockchains, but all other types of resources have no such a distributed backend system. Also many of the existent blockchains lacks the identity of agents, which makes impossible to track human Values above the free market

As long as the events are totally agreeded by the related parties, they can move to a common blockchain system and be deleted from the OCP database (or any other fork database), freeing up space and placing the information in a common, transparent and resilent historical record-of-facts for anyone to analize, extract reputation systems about some Values, etc.

The kind of blockchain transactions (packed into chained blocks) i'm imagining are very simple and lightweight, just REA. That means one transaction will consist of:
- two agents (identified by a uid, token or a public key of each) one as a giver and the other as a receiver,
- a resource type (products or services of any kind)
- a quantity,
- a unit of quantity
- a date (or timestamp).

These are the minimum fields, but some optional fields can be useful, like:
- an exchange type (is a gift, or part of a barter swap, a monetary buy/sell, a rent, etc)
- a related chain transaction (like when the tx is a reciprocal transfer related another, say the payment of a resource buyed or rented) or a reference to another blockchain's transaction.
- a unique resource being transferred (not the type of resource but the exact resource or artwork, like the original piece name if is a sculpture, the serial number of a car, a produced lot number of a product, etc)
- a place or location of the happened event (if the resources are not virtual),
- another agent or project as a context for the transaction (when it is related a party that is not the giver agent or the receiver agent),
- another related resource type for which the event's resource type is part of (like a recipe, process, etc).
 
The main point is that the whole data of agents or resources is not recorded in the chain, only unique identifiers to that objects, and so the complete objects (which can be mutable) needs to be tracked in a parallel data system, also common and shared like a blockchain but allowing for bigger data and mutability. This parallel distributed database is what I call the Holodata system and the common data types structure proposed long ago.

The role of the different web servers of the different forks of OCP can be then a place to generate: 
- commitments of transactions or work,
- real transfers in each exchange, or work hours (pending to be agreed by all related parties)
- communication between parties and project teams,
- the agreement about the happened facts can happen there too (if all parties are using the same server).
- interact with the Holodata distributed backend database of common types, entities, units, regions, places, etc, by adding new needed types or parties, etc,

These servers can represent the whole set of operations in a process, detailed exchanges, etc, but once the events are old and there's real consensus between all the related parties, the information can be passed to the REA chain, and only if a user wants to represent an old sequence of economic facts, the ocp transfers, exchanges or processes can be recreated again automatically in a server (or in the browser), just to represent them in a graphical interface. This can have some local caching for speed of subsequent queries to the same old data, but the point is that the data can be deleted because is minimalisticaly tracked in the REA chain and can be regenerated if needed.

I'm proposing to join a third team to develop this part, the blockchain of REA events, but it needs to be coordinated with the two other teams, the mutable common distributed data development team (Holodata?) and the integral data structure taxonomic team (GeneralApp?). I'm not a blockchain developer but I have a clear vision about the tool we need and I can try to help coordinate a team, design interfaces or develop front-ends.

In essence, the idea of a REA chain is meant to free-up space in the main database (like the OCP server), and make a common and transparent stream of economic events worldwide (a possible source for reputation), but meanwhile we're not able to develop that blockchain structure, we can focus in the other required structures (the mutable data distributed backend db and the trees of common types, units, etc) and hold the event histories also there. Once the REA chain becomes a reality we can discharge the old events to the chain and free-up the other dbs from that records.


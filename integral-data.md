## An Integral Data Structure:

With the actual state of evolution of human kind, we need some structures, as much common and shared as possible, to mitigate the complexity and the disconnection of humans due the separatistic forces of egos and the missunderstood plurality and freedom which produces liberal individuality and capitalism.

One way to help the rise of an integral conscience, really beyond etnocentric and domain-specific points of view, is the challenge of organizing the Types of Data in the most generic and integral way possible. 

If we find a common way of structuring data, a common database (decentralized, distributed, sharded, etc) and a 'browserver' app can be developed (as explained in the Holodata project at https://fair.coop/groups/technology-infrastructure-community-group/forum/topic/holodata-the-distributed-collective-inteligence-database/ ), and it can help our human relations and economies (peer-to-peer away from corporations) and facilitate the awareness of the world-centric integral conscience.

Here is presented a first starting version of a structure, which is always a work-in-progress and everybody interested in this taxonomic or ontologic classifications is very welcome to join at OCP.

The conceptual starting point of view assumed (explained at https://github.com/IntegralDevs/integral-developing/blob/master/arts.md ) can be resumed like:
    
<i>"All Verbs are Arts, which produce Artworks (resources, effects), performed and experienced in Space by Beings."</i> 

The left-hemisphere ego-brain needs also Concepts (like Types) to manage differentiations (order).

This produce a pentatonic initial structure of five types of data:
- Beings (humans, agents, entities, etc)
- Arts: (verbs: skills, jobs, relations)
- Artworks (resources, units, records)
- Spaces (places and regions)
- Concepts (types, values, etc)

A simple django implementation of this data-model is the so called <b>GeneralApp</b>. A small part of it is being used by the OCP as a first phase of integration (only Concept.Types and Art.Jobs used by now) at https://github.com/FreedomCoop/valuenetwork 

&nbsp;

### Beings: 
Any kind of entity, starting by:
- <b>Human:</b> the entity is of human type.
  - Individual: a particular person.
  - Colective: any kind of colective entity, from a family, group or team to big organizations, companies and culture-sharing population groups.

&nbsp;

### Arts:
All the existing verbs fit in here (the actions that relate and rule the system):
- <b>Jobs</b> (Actions, Skills or anything using Time), of all sectors, which can be grouped in branches like:
  - Doing':
    - Making
    - Lifecaring
    - Communicating
    - Transporting
  - 'Not doing':
    - Attending (listening, observing, meditating, etc)
    - Resting (sleeping, etc)
- <b>Relations</b> (between entities, objects, etc), they join two sides through the relation verb, forming triplets like:
  - Being-rel-Arts (learning, teaching, etc), 
  - Being-rel-Artwork (creating, searching, offering, etc), 
  - Being-rel-Being (participating, comunicating, meeting, etc), 
  - Being-rel-Space (habitating, traveling, etc), 
  - Being-rel-Concept (believing, understanding, etc),
  - Artwork-rel-Arts (using, requiring, etc), 
  - Artwork-rel-Artwork (including, holding, reproducing, etc), 
  - Artwork-rel-Space (parking, storing, etc), 
  - Artwork-rel-Concept (representing, etc)
  - Space-rel-Arts (facilitating, etc), 
  - Space-rel-Space (forming, ubicating, etc), 
  - ...any other branch can be created if needed (Art-rel-Art, Art-rel-Concept, Concept-rel-Concept) 
  - Generic relations (relating, nesting, etc)


We also can shape some <b>adjectives</b> for arts (as optional Tags): 

-- Nutritive or Full arts (helping nature including humans) and Non-nutritive or Empty arts (not helping nature including humans), depending on the Love being felt by the doer during the creation process. Also can be Toxic arts (against nature including humans).

-- Conscious arts (full or empty) or Automatic arts (full or empty), related the consciousness of the doer agent about all this when performing a verb.

-- Skilled arts or Non-skilled arts, and the needed growing skills levels in-between, during the learning practice (initiated, low-medium-high, mastering, etc).
    
These and other tags can be concepts but they represent a relation type (eg. 'nutritive' is art-helping-nature, 'skilled' is doer-mastering-art, etc)

&nbsp;

### Artworks:
All the things done by beings.
- <b>Material:</b> all physical things modeled by known or unknown beings,
  - Raw material: earth elements and resources.
  - Tool: motorless (hand-tools, etc), machines (energy generators, energy degenerators or motorized, etc)...
  - Lifecare: housing, alimentation, medicine, clothing, cosmetics, etc.
  - Communication medium: graphic support (printed paper, etc), sculpture, etc.
- <b>Non-Material:</b> all sorts of non-physical creations.
  - Cultural creation: languages, educational or health facilitation, music or scenic works, designs, texts, formulas, etc.
  - Digital: all kinds of digital content, from code parts to images or docs.
- <b>Unit:</b> all measurement units of all cultures.
  - Physical: volume, weight, distance, speed, pressure, etc.
  - Non-physical: time, digital memory, bandwidth, etc.
- <b>Record:</b> this kind of db item stablishes unique relations (with or without rules or conditions) between other db items.
  - UnitRatio: relation or equivalences between units (public).
  - Account: public or private accounts of the entities (economic, reputation, etc).
  - Agreement: public or private memberships, contracts, appointment, commitment, etc.
  - Event: time-based records (past, present and future) with sudden or gradual start and finish timestamps, like natural events (earth seasons, cosmic events, etc) and human events (history facts, happenings, wars, revolutions, meetings, transfers, work, task, etc).
 
Units and Records are grouped apart for practical reasons, but in reality they are non-material artwork types.
 
Many non-material artworks are related to a material artwork which acts as a physical support for the non-material. For example a disc (material) which holds a music (non-material), or the paper which shows a text, etc. Also a material artwork can relate to a non-material intrinsically, like a tool (material) and the design of that tool (non-material), etc.

Effects are verbs related the artwork or being, represented in relation triplets like artwork-rel-being (eg. 'food-healing-person') or with an open side (eg. 'fire-heating-?') to mean the effect is for everyone and everything, related a space-scope.

&nbsp;

### Spaces (S):
All the geographic data.
- <b>Place:</b> geolocated addresses, earth points, etc.
- <b>Region:</b> nested areas taxonomy (planet, continent, bioregion, area, etc).

&nbsp;

### Concepts (C):
All other words non fitting previous classes.
- <b>Types:</b> types of Beings, types of Artworks and type of Spaces. Arts and Concepts are self defined (don't need types).
- <b>Values:</b> Freedom, Fairness, etc 
- ...

&nbsp;

Of course this tree is a work-in-progress, and any help is welcome.


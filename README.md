# Tourism Ontology Project

This project presents an ontology for the **tourism domain**, developed as part of the *Semantic Web* course at the **University of Jordan**.

## Objective
To create a semantic representation of key components in the tourism industry using **OWL**, enabling intelligent knowledge management and reasoning over tourism-related data.


## Ontology Structure

The ontology includes the following major **concepts**:

### Accommodation:
- Hotel
- Motel
- Homestays
- Aparthotel
- Resort
- Bed and Breakfast

### Tourist Activities:
- Hiking, Diving, Ecotourism
- Shopping, Historical Visits, Safari

### Attractions & Destinations:
- Buildings (Museums, Castles, Mosques)
- Nature, Beaches, Cities, Islands

### Transportation:
- AirTransport (Planes, Airlines)
- LandTransport (Cars, Buses, Trains)
- WaterTransport (Boats, Ships)

### Food & Beverage:
- Restaurants, Cafés, Malls

### Stakeholders:
- Tourists, Tourist Guides, Service Providers, Regulatory Bodies


## Relationships Modeled

Examples of object properties used:
- `locatedIn`: links a tourist to a specific accommodation.
- `hasAttraction`, `visitFor`, `preferredActivity`: show motivations and destinations.
- `provided_by`, `IsServedBy`: link services to providers.
- `offersActivity`, `recommend`, `books`, `place`, etc.


## Tools Used
- **Protégé** (ontology editor)
- **XML format** for serialization


## File
- tourism-ontology.owl: The complete ontology structure in OWL/XML syntax.


## Use Cases
- Can be used in intelligent tourism platforms, recommendation systems, or semantic web agents.
- Supports reasoning and querying via SPARQL over structured tourism data.




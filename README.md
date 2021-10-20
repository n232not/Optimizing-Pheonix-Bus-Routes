# Optimizing-Pheonix-Bus-Routes

A starting attempt to optimize Pheonix bus routes using Python using agent-based modelling with the Mesa library, python google maps API, and genetic algorithms

## Goals/Steps to Complete:

Edit: I think sending out a survey of where people are trying to get to could be incredibly useful for optimization, rather than just trying to assume demand based on traffic(my previous method) since the people who are using buses/public transport probably have different needs than the people who take cars. So I also need to distribute flyers at local bus stops(so I might have to limit the scope of this study to just the city of chandler) and probably wait a bit for responses. I might send out another survey over the summer after the rest of the study and code is completed to see if demand changes with seasons. ALso need to look at legality of distributing flyers. From what I've seen, Valley Metro says you can't distribute material for commercial purposes, but it doesn't say anything about research, so I might just have to look over that again

Edit 2: Valley Metro doesn't have any good contact info on website, so their policy on flyer dissemination is unclear. May need to to look at using local libraries,social services, or community centers to widen reach. Libraries are probably most feasible.

1. Use the Google Maps API (probably its distance matrix system) to create a simplified map of pheonix and mark current bus stops/routes
2. Either use ABM or establish a reward based system to identify which destinations and areas on the map will have higher traffic/need and which areas will have less
3. Use a genetic algorithm to find an optimal way to maximize reward, establishing reasonable costs for the time it takes for buses to travel, adding more buses, and adding bus stations

Oh yeah, probably also need to conduct research on similar models.

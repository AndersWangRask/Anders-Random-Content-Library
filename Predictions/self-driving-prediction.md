# Long Bet Prediction: Self-Driving Vehicles (Denmark)

Date: 2023-12-16 (Updated: 2025-12-29)

## Introduction

Predicting the trajectory of self-driving vehicles is immensely difficult—not primarily because of technical uncertainty, but because of the complex interplay between technology, regulation, and public acceptance.

In the United States alone, more than 40,000 people are killed each year in traffic while 1.5 million more are injured. Globally, approximately 1.35 million die annually. Traffic fatalities and injuries may cost countries as much as 3% of GDP. Given the nature of driving—cars being hard, heavy objects moving at speed, humans being soft and vulnerable bags of meat—fatalities and injuries will probably never reach zero.

Logic would suggest that when autonomous vehicles kill and injure at a rate lower than human drivers, society would quickly embrace them. However, evidence suggests society will demand autonomous vehicles be *much, much* safer than human drivers before accepting them. This asymmetry may be a net positive (forcing developers to achieve genuinely high safety standards) or a net negative (delaying deployment and resulting in unnecessary fatalities during the interim). Likely both.

The positive case for self-driving vehicles is straightforward: more people living longer, more productive lives, with goods and people moving more quickly, easily, and cheaply from place to place.

## Why Denmark?

These predictions focus specifically on Denmark. This makes them more concrete, more testable, and easier to express clearly.

Denmark is a technologically advanced society but is not currently at the forefront of autonomous driving. The country is known for prioritizing safety and has no domestic car manufacturers—all vehicles are imported. Laws are implemented either by the national parliament or by the EU.

Denmark is neither the easiest nor the hardest jurisdiction for autonomous vehicles. It represents a reasonable middle case for technologically advanced democracies operating within a framework of EU regulation.

## The Operational Design Domain Approach

A key concept for understanding these predictions is the Operational Design Domain (ODD)—the specific conditions under which an autonomous system is designed to operate. Rather than asking "when will cars drive themselves everywhere?", the more tractable question is "when will cars drive themselves reliably within defined operational boundaries?"

Motorways represent the most constrained and therefore easiest ODD:
- No pedestrians or cyclists
- No intersections or cross-traffic
- Predictable lane markings and road geometry
- Limited and controlled entry/exit points
- Generally good visibility and road conditions
- Lower complexity decision-making (lane keeping, following, overtaking)

This is why the 2028 prediction focuses specifically on motorways. Danish motorways can be treated as a defined ODD for which manufacturers develop and certify autonomous capability, similar to how Ford has mapped "Blue Zones" covering 95% of UK motorways for its BlueCruise system.

## The UK Precedent

The United Kingdom provides an important precedent for understanding how autonomous driving may unfold in European markets.

In April 2023, Ford's BlueCruise became the first hands-free driving system approved for use in Great Britain—the first such approval in Europe. The system allows "hands-off, eyes-on" driving on pre-mapped motorways at speeds up to 130 km/h. As of late 2025, BlueCruise covers 95% of UK motorways and is expanding to additional Ford models.

Ford has received exemptions from UNECE driver control regulations and is actively working with regulators to extend approval across EU markets. Ford's CEO has indicated that Level 3 autonomy (hands-off, eyes-off) has been achieved in internal testing, with passenger vehicle deployment expected around 2026.

This regulatory pathway—exemptions granted, safety demonstrated, approval extended—is likely the model for how autonomous driving reaches Denmark and other EU countries.

## Understanding the "May Sleep" Requirement

The 2028 prediction states that the operator "may sleep" while the car is driving on motorways. This sounds more radical than it is.

The key insight is that the car does not need to handle every possible scenario autonomously. It needs to either:

1. **Handle the situation normally**, or
2. **Fail safely**—recognize it is approaching something outside its operational envelope, slow down, pull to the hard shoulder, stop, and wake the operator

The hard shoulder exists precisely for this purpose. A licensed operator is present and capable of driving—they are simply resting. The car's job is to maintain safe operation until either the journey completes normally or an unusual situation requires human assessment.

This is analogous to aviation autopilot. Commercial aircraft autopilot does not handle every possible emergency autonomously. It maintains safe flight while a qualified pilot is present and can be alerted if the situation exceeds the autopilot's capabilities. The pilot may be resting, but they are available.

The technical requirements for this are:
- Reliable lane-keeping and adaptive cruise at motorway speeds (already demonstrated)
- Reliable detection of ODD limits (construction, severe weather, obstructions, unusual road conditions)
- Reliable execution of "slow down, pull over, stop" when ODD limits are approached
- Reliable operator wake-up mechanism with appropriate lead time

None of these represent paradigm shifts from current Level 2+ capabilities. The extension is from "disengage and demand immediate human control" to "disengage, achieve safe stop, then request human assessment." This is an engineering challenge, not a fundamental capability leap.

## Predictions

### Prediction 1: Motorway Autonomy (End of 2028)

In Denmark, before the end of 2028, it will be possible to purchase and operate a car that can and is allowed to drive fully autonomously on all Danish motorways at the legal speed limit (130 km/h).

A licensed adult operator must be present in the vehicle. They may sleep while the car is driving autonomously but must not be intoxicated. The vehicle must be capable of waking the operator and either handing over control or achieving a safe stop if conditions require it.

**Confidence**: Moderate-High. The technical capability is close to existing. The regulatory pathway is being established through UK and EU processes. Three years provides reasonable runway for both technical refinement and regulatory approval. The main risk is regulatory delay rather than technical failure.

### Prediction 2: Near-Complete Autonomous Coverage (End of 2032)

In Denmark, before the end of 2032, it will be possible to purchase and operate a car that can and is allowed to drive fully autonomously for 99% of driving situations encountered by 99% of drivers.

The car will not be capable of autonomous operation on all roads and in all conditions, but for the vast majority of people, it will cover where they actually drive the vast majority of the time.

Either a licensed adult operator must be present, or alternatively the car must be capable of safe remote monitoring and control. (Either arrangement meeting regulatory approval satisfies this prediction.)

**Confidence**: Moderate. This requires extending autonomous capability well beyond motorways into urban and rural roads with substantially more complexity. Nine years is significant runway, but the jump in difficulty from motorways to general roads is substantial.

### Prediction 3: Autonomous Freight (End of 2032)

In Denmark, before the end of 2032, it will be possible for companies to purchase and operate lorries that can and are allowed to drive autonomously on a subset of Danish roads including motorways and major routes.

Such lorries will not make final deliveries to homes or navigate complex urban environments autonomously. They will move goods between warehouses, distribution centers, factories, and similar facilities connected by approved autonomous routes.

A likely model is hybrid operation: autonomous driving on approved routes, with human operators joining the vehicle for last-mile delivery and complex navigation.

**Confidence**: Moderate-High. Freight has strong economic incentives (driver costs, hours-of-service regulations, fuel efficiency from platooning). The routes are more predictable and can be pre-mapped. Several companies are already developing and testing autonomous freight systems.

### Prediction 4: End of Human Driving Announced (End of 2038)

In Denmark, before the end of 2038, the end of human driving will be announced as law.

The announcement itself satisfies this prediction—implementation will follow later. A plausible form: from (e.g.) 2045, all new cars sold must be fully autonomous; from (e.g.) 2053, only autonomous vehicles may operate on public roads.

Exceptions may exist for construction equipment, agricultural machinery, emergency vehicles, or other special-purpose applications.

**Confidence**: Lower. This is a political prediction as much as a technical one. It requires not just capability but broad social acceptance and political will. Fifteen years is substantial time for both technology and attitudes to evolve, but predicting political outcomes is inherently uncertain.

## Discussion: Robotaxis vs. Personal Vehicles

It is worth distinguishing two parallel tracks of autonomous vehicle development:

**Robotaxis** (Waymo, Tesla, others): Fleet-operated vehicles providing ride-hailing services in defined urban areas. Progress here has been rapid—Waymo now provides hundreds of thousands of rides per week across multiple US cities and is expanding to international markets including London. These services operate without human safety drivers in geofenced areas.

**Personal autonomous vehicles**: Consumer-owned cars capable of autonomous operation. Progress here has been slower—current consumer vehicles offer driver assistance (Level 2/2+) but not true autonomy that removes the need for constant driver attention.

The predictions above focus on personal vehicles, which is the category more relevant to how most people in Denmark actually use cars. Robotaxi services may arrive in Copenhagen before personal motorway autonomy reaches Denmark, but the societal impact of personal vehicle autonomy—eliminating the need to actively drive your own car—is arguably more significant.

## Discussion: Car Ownership

A common prediction holds that when cars become fully autonomous, car ownership will disappear—everyone will simply summon autonomous taxis for every journey.

I am skeptical of this prediction, at least within the timeframe of these predictions. Car ownership is not purely economic; it involves convenience (the car is always there), personalization (your stuff, your settings), status, and cultural attachment. These factors do not disappear because the car can drive itself.

My expectation: taxi and ride-sharing services will grow significantly as autonomous options become available, but private car ownership will remain common for the next 25-30 years. The ratio may shift, but ownership will not disappear.

## What Has Changed Since 2023

This prediction was originally drafted in December 2023. As of late 2025:

**Positive developments:**
- Waymo's robotaxi service has scaled dramatically, demonstrating that full autonomy works safely at scale
- Waymo has published safety data showing 91% fewer serious-injury crashes compared to human drivers
- Ford BlueCruise has established regulatory precedent in the UK for hands-free motorway driving
- Ford reports Level 3 capability achieved in internal testing
- EU regulatory work on autonomous vehicles continues to progress

**Neutral/unchanged:**
- No major consumer vehicle offers true Level 3+ autonomy for purchase
- Denmark has not emerged as an early mover in autonomous vehicle regulation
- The fundamental technical challenges of general autonomous driving remain substantial

**Concerning developments:**
- Some autonomous vehicle programs have been scaled back or shut down (Cruise pause, various startup failures)
- Public incidents (though rare) continue to generate negative attention
- The timeline from "technically capable" to "regulatory approval" remains longer than optimists hope

On balance, I believe the predictions remain reasonable. The 2028 motorway prediction is challenging but achievable. The 2032 predictions are more uncertain. The 2038 political prediction is speculative by nature.

## Conclusion

Self-driving vehicles are coming. The question is not whether but when and how. These predictions represent my best estimate for Denmark specifically, grounded in:

- The technical trajectory of autonomous systems
- The regulatory precedents being established in the UK and EU
- The economic incentives driving development
- The realistic assessment of how long societal and regulatory adaptation takes

The benefits—lives saved, time reclaimed, mobility extended—are substantial. Whether they arrive on this timeline depends on continued technical progress, regulatory courage, and public acceptance. The predictions may prove optimistic or pessimistic, but they provide a concrete framework against which progress can be measured.

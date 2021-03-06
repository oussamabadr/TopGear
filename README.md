[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=oussamabadr_TopGear&metric=alert_status)](https://sonarcloud.io/dashboard?id=oussamabadr_TopGear) [![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=oussamabadr_TopGear&metric=code_smells)](https://sonarcloud.io/dashboard?id=oussamabadr_TopGear) [![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=oussamabadr_TopGear&metric=sqale_index)](https://sonarcloud.io/dashboard?id=oussamabadr_TopGear) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=oussamabadr_TopGear&metric=coverage)](https://sonarcloud.io/dashboard?id=oussamabadr_TopGear)


Top Gear Refactoring Kata
=========================

This is a refactoring challenge where we look at a single-method
case, which is untested, needs refactoring, and is hard to read. Oh,
and contains bugs;-)

The assignment is as follows
----------------------------

This is the code for our customer's new environmentally friendly electric car.
The car is very dependent on software for almost everything, and the part that we're
working on is the automatic gear box. The code you see is the automatic gear box, which
currently shifts up if the engine goes over 2000 rpm, and down if it goes under 500.

For our this new car, it's been determined that the choice of gear can be much
more efficient if we could just set more specific ranges of rpm for each gear.
Future versions of the car could then use actual measurements of fuel consumption
to configure those ranges on the fly!
Your assignment is to make the gearbox accept a range of rpms for each gear (and
of course use that range to shift gears!)


This repo is a clone of https://github.com/wouterla/TopGearKata.

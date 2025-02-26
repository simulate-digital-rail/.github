# Simulate Digital Rail

This group contains repositories with projects in the area of simulations of railway networks. The core project is the yaramo model, which acts as an interchange format of railway networks. 
The yaramo model can be created by source in Python or via three importers:
- [PlanPro importer](https://github.com/simulate-digital-rail/planpro-importer)
- [OpenRailwayMap importer](https://github.com/simulate-digital-rail/orm-importer)
- [CLI importer](https://github.com/simulate-digital-rail/cli-importer)

The model can be enriched by the following tools:
- [Railway Route Generator](https://github.com/simulate-digital-rail/railway-route-generator)

The model can be exported to the following formats or be used as an input for the following advanced logics:
- [PlanPro exporter](https://github.com/simulate-digital-rail/planpro-exporter)
- [RailML exporter](https://github.com/simulate-digital-rail/railml-exporter)
- [SUMO simulation model exporter](https://github.com/simulate-digital-rail/sumo-exporter)
- [Interlocking logic](https://github.com/simulate-digital-rail/interlocking)

## Examples
There are some example usages [here](https://github.com/simulate-digital-rail/demo), [here](https://github.com/simulate-digital-rail/planpro-importer/tree/main/example), [here](https://github.com/simulate-digital-rail/railway-route-generator/tree/main/test) and [here](https://github.com/simulate-digital-rail/sumo-exporter/tree/main/examples).

## Versions
The current version of the environment is the yaramo 1 version. Version 2 of the environment is under development. See the following table for the status and links:

| Project | yaramo 1 | yaramo 2 |
| ------- | -------- | -------- |
| [yaramo](https://github.com/simulate-digital-rail/yaramo) | [~= 1.0](https://github.com/simulate-digital-rail/yaramo/tree/v1.0) | [~= 2.0](https://github.com/simulate-digital-rail/yaramo/tree/yaramo2) WIP |
| [planpro-importer](https://github.com/simulate-digital-rail/planpro-importer) | [~= 2.0](https://github.com/simulate-digital-rail/planpro-importer/tree/v2.0) | [~= 3.0](https://github.com/simulate-digital-rail/planpro-importer/tree/yaramo2)
| [cli-importer](https://github.com/simulate-digital-rail/cli-importer) | [~= 2.0](https://github.com/simulate-digital-rail/cli-importer/tree/v2.0) | Not yet implemented |
| [orm-importer](https://github.com/simulate-digital-rail/orm-importer) | [~= 2.0](https://github.com/simulate-digital-rail/orm-importer/tree/v2.0) | Not yet implemented |
| [railway-route-generator](https://github.com/simulate-digital-rail/railway-route-generator) | [~= 4.0](https://github.com/simulate-digital-rail/railway-route-generator/tree/v4.0) | Not yet implemented |
| [planpro-exporter](https://github.com/simulate-digital-rail/planpro-exporter) | [~= 2.0](https://github.com/simulate-digital-rail/planpro-exporter/tree/v2.0) | Not yet implemented |
| [sumo-exporter](https://github.com/simulate-digital-rail/sumo-exporter) | [~= 3.0](https://github.com/simulate-digital-rail/sumo-exporter/tree/v3.0) | Not yet implemented |
| [railml-exporter](https://github.com/simulate-digital-rail/railml-exporter) | [~= 1.0](https://github.com/simulate-digital-rail/railml-exporter/tree/v1.0) | Not yet implemented |
| [interlocking](https://github.com/simulate-digital-rail/interlocking) | [~= 4.0](https://github.com/simulate-digital-rail/interlocking/tree/v4.0) | Not yet implemented |
| [interlocking-logic-monitor](https://github.com/simulate-digital-rail/interlocking-logic-monitor) | [~= 2.0](https://github.com/simulate-digital-rail/interlocking-logic-monitor/tree/v2.0) | Not yet implemented |
| [demo](https://github.com/simulate-digital-rail/demo) | [~= 2.0](https://github.com/simulate-digital-rail/demo/tree/v2.0) | Not yet implemented |
| [sumo-railway-test-controller](https://github.com/simulate-digital-rail/sumo-railway-test-controller) | Not yet supported | Maybe future support |

## Publications
Read this publication for more details about the yaramo model and environment:

> Arne Boockmeyer, Julian Baumann, Benedikt Schenkel, Clemens Tiedt, Dirk Friedenberger, Lukas Pirl, and Andreas Polze.
> Processing digital railway planning documents for early-stage simulations of railway networks.
> April 2024.
> Paper presented at the Transport Research Arena 2024.


Besides this, there are some more publications in this area. Check this website for more details: [OSM-Publications](https://osm.hpi.de/publications/).

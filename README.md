# Awesome-Digital-Twin-Platform

# Top Digital Twin Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Enterprise Digital Twins, IoT Twin Frameworks, Simulation, Asset Modeling & Cross-Industry Twin Platforms*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Twin Platforms**. These systems create virtual representations of physical assets, processes, or environments—fed by IoT, engineering models, and simulation—so organizations can monitor, predict, and optimize operations.

**Examples** include Azure Digital Twins, Siemens Xcelerator, PTC ThingWorx, AVEVA PI System, Bentley iTwin, Ansys Twin Builder, Dassault 3DEXPERIENCE, Unity Industry, C3 AI, and Altair One (the category leaders).

**Open-source emphasis**: Open digital twin frameworks are mature in the IoT layer. **Eclipse Ditto**, **Asset Administration Shell (AAS)**, **FIWARE**, and domain stacks (IFC, OpenDSS) enable self-hosted twins. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Azure Digital Twins](https://azure.microsoft.com/en-us/products/digital-twins)**  
  Cloud platform for modeling connected environments with DTDL, live graphs, and integration across Azure IoT and analytics.

- **[Siemens Xcelerator, PTC ThingWorx, AVEVA PI System](https://www.siemens.com/xcelerator)**  
  Industrial digital twin and industrial IoT platforms spanning design, operations, and real-time data historians.

- **[Bentley iTwin, Ansys Twin Builder, Dassault 3DEXPERIENCE](https://www.bentley.com/software/itwin-platform/)**  
  Engineering-centric twin platforms for infrastructure, simulation, and product lifecycle digital twins.

- **[Unity Industry, NVIDIA Omniverse-adjacent, C3 AI, Altair One](https://unity.com/solutions/industry)**  
  Real-time 3D, AI, and simulation platforms used to build and run high-fidelity digital twins.

- **[Other commercial digital twin platforms](https://azure.microsoft.com/en-us/products/digital-twins)**  
  Additional cross-industry twin and predictive operations solutions.

## Open-Source GitHub Projects

- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  
  Leading open-source digital twin framework (Eclipse IoT)—API-centric twins for devices and assets, with strong adoption in industrial IoT.

- **[Eclipse BaSyx / Asset Administration Shell](https://github.com/eclipse-basyx)**  
  Open implementation of Industry 4.0 Asset Administration Shell (AAS)—standardized digital representations of industrial assets.

- **[FIWARE](https://github.com/FIWARE)**  
  Open smart solutions platform (NGSI-LD)—context brokers and data models widely used for city and industrial digital twins.

- **[Web of Things (WoT) / Eclipse Thingweb](https://github.com/eclipse-thingweb)**  
  Open standards and tooling for describing and interacting with Things—complements twin APIs.

- **[IfcOpenShell & OpenBIM stacks](https://github.com/IfcOpenShell/IfcOpenShell)**  
  Open IFC tooling for building and infrastructure geometry twins (see also domain-specific twin READMEs).

- **[OpenDSS / GridLAB-D](https://github.com/gridlab-d/gridlab-d)**  
  Open power-system simulation used as analytical twins for distribution and energy assets.

- **[ROS 2 / Open-RMF](https://github.com/ros2)**  
  Open robotics frameworks that often serve as the live twin layer for mobile assets and facilities.

- **[Thing Model & DTDL open tooling](https://github.com/search?q=DTDL+OR+digital+twin+definition+language+open+source)**  
  Community parsers, validators, and converters for open twin definition languages.

### Additional Strong Open-Source Options

- **IoT twin core**: Eclipse Ditto for device/asset shadow and API.
- **Industrial standard**: BaSyx AAS for Industrie 4.0-style asset twins.
- **Context fabric**: FIWARE for multi-source real-world context.
- **Composable stacks**: Devices → MQTT/OPC-UA → Ditto/BaSyx → time-series DB → Grafana/simulation.
- Commercial platforms still lead in multi-physics simulation, enterprise scale, and turnkey industry solutions.

**Frameworks for building custom systems**:  
**Eclipse Ditto** + **BaSyx AAS** + **FIWARE** cover the open twin application layer.  
Domain engines (IfcOpenShell, OpenDSS, ROS 2) supply geometry and physics.  
Commercial platforms (Azure Digital Twins, Siemens, PTC, Bentley, Ansys, etc.) integrate design, simulation, and operations at scale.  
Fully open digital twin platforms are production-viable for IoT-centric use cases; high-fidelity simulation twins often mix open and commercial tools.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Digital twins may control or influence physical systems. Apply strong cybersecurity, change control, and safety review before closing the loop. Models are approximations—validate against reality and licensed engineering practice.
- Open-source frameworks offer transparency and standards alignment but require integration and operations. Commercial platforms shift product depth and support to the vendor. Prefer open models (DTDL, AAS, NGSI-LD, IFC) to reduce lock-in.

---

**Made for IoT architects, industrial engineers, and builders of living virtual systems.**  
Let's expand open digital twin frameworks while recognizing the simulation and enterprise depth that leading commercial platforms deliver.

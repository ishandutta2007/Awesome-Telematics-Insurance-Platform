# Awesome-Telematics-Insurance-Platform

## Top Telematics Insurance Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Usage-Based Insurance (UBI), Pay-As-You-Drive (PAYD), Pay-How-You-Drive (PHYD), Driving Risk Analytics & Connected Insurance*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telematics Insurance**. These platforms collect and analyze vehicle and driver data from smartphones, OBD devices, connected cars, telematics units, GPS, accelerometers, and other sensors to support usage-based insurance, driver risk scoring, crash detection, claims intelligence, personalized pricing, driver coaching, and connected-insurance products.

**Examples** include Cambridge Mobile Telematics, Octo Telematics, Arity, TrueMotion, Samsara Insurance, Zendrive, DriveQuant, IMS (Intelligent Mechatronic Systems), Mojio, and Greater Than — among the notable commercial platforms in the category.

**Open-source emphasis**: Fully featured open-source equivalents to enterprise telematics-insurance platforms are still relatively uncommon. Therefore, this section is heavily expanded with open-source telematics applications, UBI/PHYD scoring projects, GPS and sensor-processing libraries, OBD-II/CAN tools, fleet-management platforms, routing infrastructure, and machine-learning components that can be combined into a self-hosted telematics-insurance stack.

A particularly relevant example is **insurance-telematics**, an MIT-licensed project that converts GPS/accelerometer trip data into GLM-ready driving-risk features using Hidden Markov Models.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Building a Custom Open-Source Telematics Insurance Platform](#building-a-custom-open-source-telematics-insurance-platform)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Category / Focus | Key Capabilities | Pricing (Starting Tier / Rates) | Free Tier & Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Cambridge Mobile Telematics (CMT)](https://www.cmtelematics.com/)** | Smartphone & Tag Telematics | DriveWell platform, crash detection, driver risk scoring, claim alerting | Starts from ~$1.50–$3.00/driver/month (enterprise volume tier) | 30-day proof-of-concept (PoC) carrier pilot + interactive sandbox demo |
| **[Octo Telematics](https://www.octotelematics.com/)** | Connected Mobility & Insurance | Digital Driver platform, claims intelligence, UBI risk scoring, crash validation | Starts from ~$20–$35/vehicle/month (telematics device + cloud subscription bundle) | 30-day "Digital Driver™ Try Before You Buy" pilot for policyholder risk pre-scoring |
| **[Arity](https://arity.com/)** | Mobility Intelligence & Scoring | Arity IQ at-quote driver risk score, driving engine SDK, crash detection | Starts from ~$0.10–$0.25 per score lookup / API transaction (volume dependent) | 30-day sandbox API integration access for certified carrier partners |
| **[TrueMotion](https://www.truemotion.com/)** | Mobile Telematics & UBI | Distracted driving analytics, trip scoring, crash response *(Acquired by CMT)* | Integrated into CMT DriveWell (formerly started at ~$2.00–$4.00/user/month) | 30-day enterprise evaluation pilot through CMT DriveWell platform |
| **[Samsara](https://www.samsara.com/)** | Fleet & Video Telematics | Real-time GPS, AI dash cams, safety risk scores, fleet insurance integrations | Starts at $27/vehicle/month for core telematics ($40–$60/mo with AI dash cams; hardware $99–$548/unit; 3-yr term) | 30-day risk-free hardware trial program (hardware returnable within 30 days) |
| **[Zendrive](https://www.zendrive.com/)** | Smartphone Telematics SDK | Mobile sensor risk scoring, collision detection, aggressive driving alerts | Starts at $4.00/driver/month for enterprise fleets / UBI programs | 30-day pilot testing program and developer sandbox access |
| **[DriveQuant](https://www.drivequant.com/)** | Smartphone Telematics & White-Label Apps | DriveKit SDK, driver coaching, eco-driving, smartphone crash detection | Starts at €0.50–€1.50/active driver/month (starter tier package for pilot fleets) | 100% Free DriveKit Demo App (iOS/Android) for live testing + 30-day sandbox API trial upon request |
| **[IMS (Intelligent Mechatronic Systems)](https://www.intellimec.com/)** | Connected Car & UBI Platform | DriveSync platform, OneApp mobile SDK, OBD/OEM data normalization, claims scoring | Starts from ~$15–$30/vehicle/month for data ingestion & risk scoring | Enterprise pilot package offering up to 5 self-install OBD test dongles and 30-day portal access |
| **[Mojio](https://www.moj.io/)** | Connected Car & Fleet Tracking | Force Fleet Tracking, OBD-II data platform, vehicle health, driver behavior | Starts at $10/vehicle/month for Force Fleet Tracking (hardware separate) | Free developer sandbox access with virtual vehicle simulator, mobile SDKs, and REST API access |
| **[Greater Than](https://www.greater-than.eu/)** | AI Driver Risk & Eco Scoring | Econaisance AI, crash probability modeling, climate impact analytics | Starts at €1.00–€2.50/active driver/month for AI scoring API | 30-day historical data pilot analysis & guided AI score simulator demo |
| **[Damoov](https://www.damoov.com/)** | Telematics SDK & DataHub | Smartphone telematics SDK, Zenroad app, auto trip tracking, driving scorecards | Starter plan at $250/month (up to 100 drivers; $1–$2/extra driver/mo); Growth at $1,000/month (400 drivers) | 90-day free developer sandbox (no credit card required) + Free open-source Zenroad reference app + Free tier for academic/research use |
| **[Nauto](https://www.nauto.com/)** | AI Fleet Safety & Video Telematics | Real-time distracted driving alerts, AI dual-facing dash cams, collision prevention | Starts at $25/unit/month plus $375 one-time hardware fee per vehicle (1-year minimum contract) | 30-day pilot evaluation program for qualified enterprise fleets |
| **[Verisk Telematics](https://www.verisk.com/)** | InsurTech Data Exchange | Telematics Data Prefill, driver risk scoring, OEM connected car data network | Starts from ~$0.50–$2.00 per inquiry / prefill transaction for licensed insurers | Carrier sandbox environment & retrospective portfolio backtesting pilot |
| **[LexisNexis Risk Solutions](https://risk.lexisnexis.com/)** | Telematics Risk Analytics | Telematics OnDemand, DriveMetrics scoring, OEM data exchange, claims automation | Starts from ~$0.75–$2.50 per report / policyholder verification | Carrier-assisted sandbox access & 30-day historical validation pilot study |
| **[HUK-COBURG Telematik Plus](https://www.huk.de/)** | Consumer UBI Program | Windshield sensor + "HUK Mein Auto" app, driving score calculation, cash discounts | €0 / year extra cost (Guarantees 5% initial discount and up to 30% annual policy discount) | 100% Free permanent program for policyholders, includes complimentary physical telematics sensor |
| **[Vulog](https://www.vulog.com/)** | Shared Mobility & Fleet Telematics | AiMA platform, connected fleet management, carsharing telematics, risk analytics | Starts from €15–€35/vehicle/month for connected vehicle fleet management | 30-day structured sandbox demo environment & guided solution simulation |
| **[Geotab](https://www.geotab.com/)** | Enterprise Fleet Telematics | MyGeotab platform, GO9 devices, driver safety scorecards, insurance marketplace | Starts at $20–$40/vehicle/month via authorized resellers (hardware ~$80–$150/unit) | 30-day pilot trial program with evaluation demo hardware units |
| **[Otonomo (Ridecell)](https://www.ridecell.com/)** | Connected Vehicle Data Platform | OEM vehicle data aggregation, fleet automation, driving behavior APIs | Starts from $10–$25/vehicle/month for connected data and fleet workflow automation | 30-day developer sandbox environment & enterprise PoC integration |
| **[Wejo](https://www.wejo.com/)** | Connected Car Data Exchange *(Historical)* | High-volume connected vehicle data feeds, traffic intelligence, collision data | Inactive / Defunct (Assets liquidated post-May 2023 administration) | Inactive (Historical service formerly offered limited sandbox hackathon keys) |

## Open-Source GitHub Projects

### UBI / Insurance Risk Scoring

- **[insurance-telematics](https://github.com/burning-cost/insurance-telematics)**  
  Open-source MIT-licensed project that converts raw GPS and accelerometer trip data into GLM-ready insurance risk features using Hidden Markov Models. It specifically targets UBI/PAYD/PHYD use cases and emphasizes explainable, auditable risk scoring.

- **[Fleet Management System — Automotive Telematics](https://github.com/sachnaror/fleet-management-system)**  
  Open-source fleet-telematics platform built with FastAPI, SQLAlchemy, OBD-II, CAN bus, GPS, and a live dashboard. It includes driver-behavior monitoring, harsh-braking/speeding detection, trip analytics, and an explicit insurance-telematics use case.

- **[Fleet Management System — Automotive Telematics](https://github.com/santoshiimind/fleet-management-system)**  
  Open-source Python-based telematics system supporting GPS tracking, OBD-II diagnostics, CAN-bus data, driver behavior monitoring, alerts, and safety scoring.

### Mobile Telematics / Smartphone UBI

- **[Zenroad iOS Telematics App](https://github.com/Mobile-Telematics/TelematicsApp-iOS)**  
  Open-source iOS telematics application designed for UBI, safe-driving, shared mobility, tracking, and driver-coaching applications. It includes trip tracking, driving analytics, leaderboards, rewards, and optional OBD connectivity.

- **[Zenroad Android Telematics App](https://github.com/Mobile-Telematics/TelematicsApp-Android)**  
  Open-source Android telematics application suitable for UBI, safe-driving, fleet, tracking, and mobility applications. It provides a mobile telematics engine, trip details, driving scorecards, and optional OBD integration.

- **[OwnTracks](https://github.com/owntracks/recorder)**  
  Open-source location-tracking ecosystem useful for collecting smartphone location data that can form part of a mobile telematics pipeline.

- **[GPSLogger](https://github.com/mendhak/gpslogger)**  
  Open-source Android GPS logging application useful for collecting location and trip data for custom telematics applications.

### Vehicle / OBD-II Telematics

- **[python-OBD](https://github.com/brendan-w/python-OBD)**  
  Python library for communicating with OBD-II vehicle interfaces and retrieving vehicle telemetry and diagnostic information.

- **[OpenXC](https://github.com/openxc/openxc)**  
  Open-source vehicle-data platform designed to make automotive CAN-bus information accessible to software applications.

- **[CANtact](https://github.com/linklayer/cantact)**  
  Open-source CAN-bus hardware/software ecosystem useful for collecting and analyzing vehicle network data.

- **[python-can](https://github.com/hardbyte/python-can)**  
  Open-source Python library for Controller Area Network communication, useful for vehicle telemetry and CAN-bus data ingestion.

- **[SavvyCAN](https://github.com/collin80/SavvyCAN)**  
  Open-source CAN-bus reverse-engineering and vehicle-network analysis tool useful for connected-car data experimentation.

- **[BUSMASTER](https://github.com/rbei-etas/busmaster)**  
  Open-source Windows-based CAN-bus development and analysis software useful for vehicle-network data acquisition and testing.

### Fleet Telematics & GPS Tracking

- **[Traccar](https://github.com/traccar/traccar)**  
  Open-source GPS tracking platform supporting real-time vehicle tracking, geofencing, alerts, reports, and a wide variety of telematics devices.

- **[OpenGTS](https://sourceforge.net/projects/opengts/)**  
  Open-source GPS tracking system for vehicle and fleet tracking applications.

- **[OwnTracks Recorder](https://github.com/owntracks/recorder)**  
  Open-source backend for receiving and storing location data from mobile devices.

- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  
  Open-source IoT platform providing device management, telemetry ingestion, rule processing, dashboards, and real-time monitoring.

- **[Eclipse Hono](https://github.com/eclipse-hono/hono)**  
  Open-source IoT connectivity platform suitable for connecting telematics devices and vehicles to cloud infrastructure.

- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  
  Open-source digital-twin framework useful for representing connected vehicles and maintaining real-time vehicle state.

### Driving Behavior & Sensor Processing

- **[Open mHealth](https://github.com/openmhealth)**  
  Open-source ecosystem for standardized health and sensor data representations that can provide useful patterns for mobile-sensor processing and interoperability.

- **[SensorLogger](https://github.com/tszheichoi/awesome-sensor-logger)**  
  Mobile sensor-data collection tooling useful for experimentation with accelerometer, gyroscope, GPS, and other smartphone signals.

- **[ActivityRecognitionClient](https://developers.google.com/location-context/activity-recognition)**  
  Mobile activity-recognition infrastructure that can be incorporated into driving-state and trip-detection systems.

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**  
  Open-source machine-learning toolkit useful for driver-risk classification, segmentation, anomaly detection, and telematics modeling.

- **[XGBoost](https://github.com/dmlc/xgboost)**  
  Open-source gradient-boosting framework useful for insurance risk modeling, claim-frequency prediction, and driving-risk classification.

- **[LightGBM](https://github.com/microsoft/LightGBM)**  
  Open-source gradient-boosting framework suitable for large-scale telematics feature sets and insurance risk models.

- **[PyTorch](https://github.com/pytorch/pytorch)**  
  Open-source machine-learning framework useful for deep-learning models over GPS trajectories, accelerometer signals, video, and multimodal telematics data.

### Mapping & Route Processing

- **[OpenStreetMap](https://github.com/openstreetmap/openstreetmap-website)**  
  Open geographic-data ecosystem providing road-network data for trip analysis, routing, geofencing, and map-based telematics applications.

- **[OSRM](https://github.com/Project-OSRM/osrm-backend)**  
  Open-source high-performance routing engine based on OpenStreetMap data, useful for map matching and route analysis.

- **[GraphHopper](https://github.com/graphhopper/graphhopper)**  
  Open-source routing engine useful for route calculation, map matching, distance matrices, and geospatial telematics applications.

- **[Valhalla](https://github.com/valhalla/valhalla)**  
  Open-source routing engine designed for scalable multimodal routing and location-based services.

- **[PostGIS](https://github.com/postgis/postgis)**  
  Open-source PostgreSQL extension for storing, indexing, and analyzing GPS trajectories, geofences, routes, and other spatial insurance data.

### Data Streaming & Telematics Infrastructure

- **[Apache Kafka](https://github.com/apache/kafka)**  
  Open-source event-streaming platform suitable for ingesting high-volume vehicle telemetry and trip events.

- **[MQTT Eclipse Mosquitto](https://github.com/eclipse-mosquitto/mosquitto)**  
  Open-source MQTT broker suitable for lightweight vehicle and IoT telemetry ingestion.

- **[Eclipse Hono](https://github.com/eclipse-hono/hono)**  
  Open-source IoT connectivity layer for securely connecting large numbers of telematics devices.

- **[Node-RED](https://github.com/node-red/node-red)**  
  Open-source flow-based integration tool useful for connecting telematics devices, APIs, databases, alerts, and insurance workflows.

- **[Apache Flink](https://github.com/apache/flink)**  
  Open-source stream-processing engine suitable for real-time processing of high-volume vehicle and trip telemetry.

- **[Apache Spark](https://github.com/apache/spark)**  
  Open-source distributed analytics platform useful for large-scale historical telematics processing and feature engineering.

### Additional Strong Open-Source Options

- **Mobile UBI** — Zenroad iOS, Zenroad Android, OwnTracks, and GPSLogger.
- **Vehicle telemetry** — python-OBD, OpenXC, python-can, CANtact, SavvyCAN, and BUSMASTER.
- **Fleet tracking** — Traccar, OpenGTS, OwnTracks, ThingsBoard, and Eclipse Hono.
- **Driving-risk modeling** — insurance-telematics, scikit-learn, XGBoost, LightGBM, and PyTorch.
- **GPS processing** — OpenStreetMap, OSRM, GraphHopper, Valhalla, and PostGIS.
- **IoT ingestion** — MQTT Mosquitto, Eclipse Hono, Eclipse Ditto, ThingsBoard, and Node-RED.
- **Streaming analytics** — Apache Kafka, Apache Flink, and Apache Spark.
- **Vehicle-network analysis** — OpenXC, python-can, CANtact, SavvyCAN, and BUSMASTER.
- **Insurance feature engineering** — HMMs, GLMs, gradient boosting, trajectory features, harsh-braking detection, speeding detection, acceleration/deceleration profiles, mileage, time-of-day, and road-context features.

**Frameworks for building custom systems**: Combine **Zenroad + Traccar + python-OBD/python-can + MQTT + Kafka + PostGIS + OSRM/GraphHopper + insurance-telematics + XGBoost/LightGBM + Grafana** to create a self-hosted telematics-insurance platform covering mobile data collection, vehicle telemetry, trip processing, risk scoring, geospatial analytics, and insurer dashboards.

## Building a Custom Open-Source Telematics Insurance Platform

A practical open-source telematics-insurance architecture can be assembled from several layers:

1. **Data collection** — smartphone sensors, Zenroad, OBD-II dongles, CAN bus, OEM APIs, and telematics devices.
2. **Device connectivity** — MQTT, Eclipse Hono, Traccar, or custom APIs.
3. **Vehicle telemetry** — python-OBD, python-can, OpenXC, and CAN tooling.
4. **GPS processing** — GPS coordinates, speed, heading, map matching, and route reconstruction.
5. **Trip detection** — Identify trip start/end, parked periods, mileage, and driving sessions.
6. **Driving behavior extraction** — Speeding, harsh braking, acceleration, cornering, phone distraction, night driving, and trip context.
7. **Geospatial enrichment** — OpenStreetMap, OSRM, GraphHopper, Valhalla, and PostGIS.
8. **Feature engineering** — Aggregate raw sensor streams into driver- and trip-level risk features.
9. **Risk scoring** — HMMs, GLMs, gradient boosting, neural networks, or actuarial models.
10. **UBI pricing** — Map telematics-derived risk indicators to pricing or discount models.
11. **Crash detection** — Accelerometer, gyroscope, GPS, OBD/CAN, and mobile-sensor fusion.
12. **Claims intelligence** — Connect crash events and trip history to claims systems.
13. **Driver engagement** — Scorecards, coaching, gamification, alerts, and feedback.
14. **Analytics** — Grafana, Superset, Metabase, or custom insurer dashboards.
15. **Data governance** — Encryption, consent management, retention controls, audit trails, and privacy-preserving analytics.

### Example Open-Source Telematics Insurance Architecture

```text
                       ┌─────────────────────────┐
                       │       Policyholders      │
                       │  Smartphone / Connected  │
                       │       Vehicles / OBD     │
                       └────────────┬────────────┘
                                    │
             ┌──────────────────────┼──────────────────────┐
             │                      │                      │
      ┌──────▼──────┐       ┌──────▼──────┐       ┌──────▼──────┐
      │  Smartphone │       │   OBD / CAN  │       │ OEM / Fleet │
      │  Zenroad    │       │ python-OBD   │       │  Telematics │
      │  GPS/IMU    │       │ python-can   │       │    APIs     │
      └──────┬──────┘       └──────┬──────┘       └──────┬──────┘
             │                     │                     │
             └─────────────────────┼─────────────────────┘
                                   │
                       ┌───────────▼───────────┐
                       │   Telematics Gateway  │
                       │ MQTT / Hono / Traccar │
                       └───────────┬───────────┘
                                   │
                       ┌───────────▼───────────┐
                       │    Event Streaming    │
                       │ Kafka / Flink / MQTT  │
                       └───────────┬───────────┘
                                   │
              ┌────────────────────┼────────────────────┐
              │                    │                    │
       ┌──────▼──────┐     ┌──────▼──────┐     ┌──────▼──────┐
       │ Trip Engine │     │ GPS / Map   │     │ Sensor /    │
       │ Trip Detect │     │ Matching    │     │ Behavior    │
       │ Mileage     │     │ OSM/OSRM    │     │ Features    │
       └──────┬──────┘     └──────┬──────┘     └──────┬──────┘
              │                    │                    │
              └────────────────────┼────────────────────┘
                                   │
                       ┌───────────▼───────────┐
                       │ Feature Store / DB    │
                       │ PostgreSQL + PostGIS  │
                       └───────────┬───────────┘
                                   │
                       ┌───────────▼───────────┐
                       │   Risk Scoring Layer  │
                       │ HMM / GLM / XGBoost   │
                       │ LightGBM / PyTorch    │
                       └───────────┬───────────┘
                                   │
                    ┌──────────────┼──────────────┐
                    │              │              │
             ┌──────▼─────┐ ┌──────▼─────┐ ┌─────▼──────┐
             │ UBI Pricing│ │ Crash /    │ │ Driver     │
             │ / Discount │ │ Claims     │ │ Coaching   │
             │ Models     │ │ Analytics  │ │ / Rewards  │
             └──────┬─────┘ └──────┬─────┘ └─────┬──────┘
                    │              │              │
                    └──────────────┼──────────────┘
                                   │
                       ┌───────────▼───────────┐
                       │   Insurer Analytics   │
                       │ Grafana / Superset    │
                       │ Pricing / Claims / BI │
                       └───────────────────────┘

The open-source ecosystem is particularly strong in mobile sensing, GPS tracking, OBD-II/CAN access, fleet telematics, geospatial processing, machine learning, and streaming infrastructure. It is much weaker in complete insurer-grade UBI platforms with production-ready policy integration, actuarial pricing workflows, regulatory tooling, consent management, claims integration, and large-scale connected-vehicle data partnerships.

The most promising open-source path is therefore usually to combine specialized components into a unified telematics-insurance platform rather than expect one project to replace Cambridge Mobile Telematics, Octo, Arity, or DriveQuant end-to-end.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, official/GitHub link, 1–2 sentence description, and whether it's SaaS or open-source.

For open-source entries, verify the repository's current license and maintenance status.

Prefer projects with documented APIs, reproducible deployments, active development, and clear licensing.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Some projects listed under Open-Source are complete telematics applications, while others are mobile SDKs, GPS trackers, OBD/CAN libraries, routing engines, machine-learning frameworks, or infrastructure components.

Open-source components generally require substantial integration before they can provide the actuarial, regulatory, privacy, claims, and insurance-platform functionality of commercial telematics providers.

Usage-based insurance models must comply with applicable insurance, privacy, data-protection, telecommunications, and automotive regulations.

Telematics data can be highly sensitive. Production deployments should implement appropriate consent management, encryption, access controls, retention policies, anonymization/pseudonymization, and audit logging.

Always verify the current license, project activity, security posture, and production readiness before deployment.

Risk models should be validated for statistical robustness, fairness, explainability, calibration, and jurisdiction-specific insurance requirements.

Made for insurers, actuaries, mobility companies, automotive OEMs, fleet operators, connected-car developers, data scientists, and insurance technologists.
Let's make telematics insurance more open, programmable, explainable, and data-driven.

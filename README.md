# Awesome-Telematics-Insurance-Platform

Markdown
# Top Telematics Insurance Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Usage-Based Insurance (UBI), Pay-As-You-Drive (PAYD), Pay-How-You-Drive (PHYD), Driving Risk Analytics & Connected Insurance*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telematics Insurance**. These platforms collect and analyze vehicle and driver data from smartphones, OBD devices, connected cars, telematics units, GPS, accelerometers, and other sensors to support usage-based insurance, driver risk scoring, crash detection, claims intelligence, personalized pricing, driver coaching, and connected-insurance products.

**Examples** include Cambridge Mobile Telematics, Octo Telematics, Arity, TrueMotion, Samsara Insurance, Zendrive, DriveQuant, IMS (Intelligent Mechatronic Systems), Mojio, and Greater Than — among the notable commercial platforms in the category.

**Open-source emphasis**: Fully featured open-source equivalents to enterprise telematics-insurance platforms are still relatively uncommon. Therefore, this section is heavily expanded with open-source telematics applications, UBI/PHYD scoring projects, GPS and sensor-processing libraries, OBD-II/CAN tools, fleet-management platforms, routing infrastructure, and machine-learning components that can be combined into a self-hosted telematics-insurance stack.

A particularly relevant example is **insurance-telematics**, an MIT-licensed project that converts GPS/accelerometer trip data into GLM-ready driving-risk features using Hidden Markov Models. :contentReference[oaicite:0]{index=0}

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Building a Custom Open-Source Telematics Insurance Platform](#building-a-custom-open-source-telematics-insurance-platform)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cambridge Mobile Telematics](https://www.cmtelematics.com/)**  
  Smartphone and connected-vehicle telematics platform focused on driving risk, crash detection, driver engagement, and usage-based insurance.

- **[Octo Telematics](https://www.octotelematics.com/)**  
  Connected-mobility and insurance-telematics platform providing driving-data collection, behavioral analytics, risk scoring, claims intelligence, and UBI capabilities.

- **[Arity](https://arity.com/)**  
  Allstate-owned mobility-data and insurance analytics company providing driving insights, risk analytics, telematics data, and insurance solutions.

- **[TrueMotion](https://www.truemotion.com/)**  
  Telematics and driving-data technology focused on mobile-based driving behavior, risk scoring, distracted-driving detection, and usage-based insurance.

- **[Samsara](https://www.samsara.com/)**  
  Connected-operations and telematics platform providing vehicle tracking, driver behavior analytics, safety scoring, video telematics, and insurance-oriented fleet risk capabilities.

- **[Zendrive](https://www.zendrive.com/)**  
  Smartphone-based mobility and telematics platform providing driving behavior, risk analytics, crash detection, and insurance-oriented driving insights.

- **[DriveQuant](https://www.drivequant.com/)**  
  Smartphone telematics platform for insurers and mobility companies that collects driving data and converts it into driving-risk indicators, crash detection, driver coaching, and connected-insurance insights. :contentReference[oaicite:1]{index=1}

- **[IMS — Intelligent Mechatronic Systems](https://www.intellimec.com/)**  
  Telematics technology provider focused on connected-vehicle data, usage-based insurance, fleet applications, and driving behavior analytics.

- **[Mojio](https://www.moj.io/)**  
  Connected-car and telematics platform providing vehicle data, GPS tracking, diagnostics, driver insights, and APIs for mobility and insurance applications.

- **[Greater Than](https://www.greater-than.eu/)**  
  AI-powered driving-risk and fuel-efficiency analytics platform using driving and vehicle data for insurance, mobility, fleet, and sustainability applications.

### Additional Notable SaaS / Hosted Options

- **[Damoov](https://www.damoov.com/)**  
  Telematics technology provider offering smartphone-based telematics, driving analytics, fleet tracking, and mobility APIs.

- **[Nauto](https://www.nauto.com/)**  
  AI-powered vehicle and driver safety platform using telematics, computer vision, and behavioral analytics to identify driving risk.

- **[Cambridge Mobile Telematics DriveWell](https://www.cmtelematics.com/)**  
  Telematics ecosystem combining smartphone sensors, connected vehicles, crash detection, driver scoring, and engagement.

- **[Verisk Telematics](https://www.verisk.com/)**  
  Insurance-data and analytics ecosystem with telematics and driving-risk capabilities for insurers.

- **[LexisNexis Risk Solutions Telematics](https://risk.lexisnexis.com/)**  
  Insurance analytics ecosystem providing driving-data, risk, identity, and underwriting intelligence.

- **[HUK-COBURG Telematik Plus](https://www.huk.de/)**  
  Insurance telematics program using connected driving information to support behavior-based insurance.

- **[Vulog](https://www.vulog.com/)**  
  Connected mobility platform supporting vehicle telematics, fleet operations, shared mobility, and connected-vehicle data.

- **[Geotab](https://www.geotab.com/)**  
  Large-scale connected-vehicle and fleet telematics platform providing vehicle data, driver behavior, GPS, safety, and analytics capabilities that can support insurance programs.

- **[Samsara Connected Operations](https://www.samsara.com/)**  
  Connected-vehicle ecosystem combining telematics, cameras, sensors, driver safety, fleet management, and operational analytics.

- **[Otonomo](https://www.ridecell.com/)**  
  Connected-vehicle data ecosystem providing APIs and data infrastructure for mobility and automotive applications.

- **[Wejo](https://www.wejo.com/)**  
  Connected-vehicle data platform focused on processing and commercializing vehicle-generated data for mobility and automotive use cases.

## Open-Source GitHub Projects

### UBI / Insurance Risk Scoring

- **[insurance-telematics](https://github.com/burning-cost/insurance-telematics)**  
  Open-source MIT-licensed project that converts raw GPS and accelerometer trip data into GLM-ready insurance risk features using Hidden Markov Models. It specifically targets UBI/PAYD/PHYD use cases and emphasizes explainable, auditable risk scoring. :contentReference[oaicite:2]{index=2}

- **[Fleet Management System — Automotive Telematics](https://github.com/sachnaror/fleet-management-system)**  
  Open-source fleet-telematics platform built with FastAPI, SQLAlchemy, OBD-II, CAN bus, GPS, and a live dashboard. It includes driver-behavior monitoring, harsh-braking/speeding detection, trip analytics, and an explicit insurance-telematics use case. :contentReference[oaicite:3]{index=3}

- **[Fleet Management System — Automotive Telematics](https://github.com/santoshiimind/fleet-management-system)**  
  Open-source Python-based telematics system supporting GPS tracking, OBD-II diagnostics, CAN-bus data, driver behavior monitoring, alerts, and safety scoring. :contentReference[oaicite:4]{index=4}

### Mobile Telematics / Smartphone UBI

- **[Zenroad iOS Telematics App](https://github.com/Mobile-Telematics/TelematicsApp-iOS)**  
  Open-source iOS telematics application designed for UBI, safe-driving, shared mobility, tracking, and driver-coaching applications. It includes trip tracking, driving analytics, leaderboards, rewards, and optional OBD connectivity. :contentReference[oaicite:5]{index=5}

- **[Zenroad Android Telematics App](https://github.com/Mobile-Telematics/TelematicsApp-Android)**  
  Open-source Android telematics application suitable for UBI, safe-driving, fleet, tracking, and mobility applications. It provides a mobile telematics engine, trip details, driving scorecards, and optional OBD integration. :contentReference[oaicite:6]{index=6}

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

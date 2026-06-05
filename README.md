# Aruba (aruba)

APIs for HPE Aruba Networking cloud networking, security, and infrastructure solutions including Central, AOS-CX, ClearPass, EdgeConnect SD-WAN, Fabric Composer, and User Experience Insight.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aruba/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aruba/refs/heads/main/apis.yml)

## Tags

- Cloud
- Infrastructure
- Network Management
- Networking
- SD-WAN
- Security
- Switches
- Wireless

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Aruba Central API

RESTful API for managing Aruba Central cloud networking platform, providing unified network management, AI-based analytics, and IoT device security for wired, wireless, and SD-WAN networks. APIs follow the Swagger 2.0 (OpenAPI 2.0) specification.

- **Human URL:** [https://developer.arubanetworks.com/central/](https://developer.arubanetworks.com/central/)
- **Base URL:** `https://apigw-prod2.central.arubanetworks.com`

#### Tags

- Analytics
- Cloud Management
- Monitoring
- Network Automation

#### Properties

- [Documentation](https://developer.arubanetworks.com/central/docs)
- [OpenAPI](openapi/aruba-central-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://developer.arubanetworks.com/central/reference) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.arubanetworks.com/central/docs/api-oauth-access-token)
- [Getting Started](https://developer.arubanetworks.com/central/docs/rest-api-getting-started)
- [SDK](https://github.com/aruba/pycentral)

### Aruba ClearPass API

REST API for ClearPass Policy Manager providing role- and device-based secure network access control for IoT, BYOD, corporate devices, as well as employees, contractors, and guests across any multivendor wired, wireless, and VPN infrastructure.

- **Human URL:** [https://developer.arubanetworks.com/cppm/](https://developer.arubanetworks.com/cppm/)
- **Base URL:** `https://clearpass.example.com/api`

#### Tags

- Authentication
- Authorization
- Network Access Control
- Policy Management

#### Properties

- [Documentation](https://developer.arubanetworks.com/cppm/docs)
- [API Reference](https://developer.arubanetworks.com/cppm/reference)
- [Getting Started](https://developer.arubanetworks.com/cppm/docs/getting-started-with-the-clearpass-policy-manager-api)
- [SDK](https://github.com/aruba/pyclearpass)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aruba AOS-CX REST API

REST API for AOS-CX switches providing full programmability of switches running the AOS-CX operating system. Supports HTTPS POST, GET, PUT, PATCH, and DELETE methods and includes a built-in Swagger UI for API reference and testing.

- **Human URL:** [https://developer.arubanetworks.com/aoscx/](https://developer.arubanetworks.com/aoscx/)

#### Tags

- Infrastructure
- Network Automation
- Programmability
- Switches

#### Properties

- [Documentation](https://developer.arubanetworks.com/aoscx/docs/introduction)
- [API Reference](https://developer.arubanetworks.com/aoscx/docs/additional-resources-1)
- [SDK](https://github.com/aruba/pyaoscx)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aruba EdgeConnect SD-WAN API

REST API for HPE Aruba Networking EdgeConnect SD-WAN providing programmatic access to Orchestrator and EdgeConnect appliance management, monitoring, and configuration. APIs are available at both the Orchestrator level and the Appliance level.

- **Human URL:** [https://developer.arubanetworks.com/edgeconnect/](https://developer.arubanetworks.com/edgeconnect/)

#### Tags

- Edge Networking
- Orchestrator
- SD-WAN
- WAN Optimization

#### Properties

- [Documentation](https://developer.arubanetworks.com/edgeconnect/docs/intro)
- [Getting Started](https://developer.arubanetworks.com/edgeconnect/docs/whats-new)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aruba Fabric Composer API

REST API for HPE Aruba Networking Fabric Composer, an intelligent software-defined orchestration solution that simplifies and accelerates leaf-spine network provisioning and day-to-day operations across rack-scale compute and storage infrastructure.

- **Human URL:** [https://developer.arubanetworks.com/afc/](https://developer.arubanetworks.com/afc/)

#### Tags

- Data Center
- Fabric
- Leaf-Spine
- Orchestration

#### Properties

- [Documentation](https://developer.arubanetworks.com/afc/docs/about)
- [Getting Started](https://developer.arubanetworks.com/afc/docs/getting-started-with-the-afc-api)
- [API Reference](https://developer.arubanetworks.com/aruba-fabric-composer/reference/getping)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aruba User Experience Insight API

API for HPE Aruba Networking User Experience Insight (UXI) providing programmatic access to onboarding tasks such as creating, modifying, or removing groups and assigning sensors, agents, networks, and service tests to groups.

- **Human URL:** [https://developer.arubanetworks.com/uxi/](https://developer.arubanetworks.com/uxi/)

#### Tags

- Monitoring
- Network Testing
- Sensors
- User Experience

#### Properties

- [Documentation](https://developer.arubanetworks.com/uxi/docs/user-experience-insight-overview)
- [Getting Started](https://developer.arubanetworks.com/uxi/docs/getting-started-with-onboarding-api)
- [Authentication](https://developer.arubanetworks.com/uxi/docs/generating-managing-access-token)
- [SDK](https://developer.arubanetworks.com/uxi/docs/installing-python-package)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aruba AirWave API

API for AirWave network management platform.

- **Human URL:** [https://www.arubanetworks.com/products/network-management-operations/airwave/](https://www.arubanetworks.com/products/network-management-operations/airwave/)
- **Base URL:** `https://airwave.example.com/api`

#### Tags

- Monitoring
- Network Management
- Reporting

#### Properties

- [Documentation](https://support.hpe.com/techhub/eginfolib/airwave/)
- [Postman Collection](collections/aruba-central-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aruba-central-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/aruba-a-hewlett-packard-enterprise-company)
- [Developer Portal](https://developer.arubanetworks.com)
- [Hub](https://devhub.arubanetworks.com)
- [GitHub Organization](https://github.com/aruba)
- [Blog](https://blogs.arubanetworks.com/)
- [Support](https://www.arubanetworks.com/support-services/)
- [Terms of Service](https://www.arubanetworks.com/company/legal/)
- [Privacy Policy](https://www.arubanetworks.com/company/legal/privacy-policy/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://developer.arubanetworks.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com

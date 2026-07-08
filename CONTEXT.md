# grants-config-bootstrap

Bootstrap tooling for setting up grants configuration repositories and related package resources.

## Language

**Bootstrap**
The setup process that creates or prepares grants configuration resources for local development or publication.
_Avoid_: Migration, Deployment, Runtime startup

**Configuration repository**
A repository that stores grant configuration files and release metadata.
_Avoid_: Application service, Backend, UI

**Package**
The npm-distributed tooling under `npm/` used by the bootstrap process.
_Avoid_: App, Service, Script folder

**Grant configuration**
Versioned configuration that describes a grant journey, integration, or release payload.
_Avoid_: Form code, Runtime state, Test fixture

**Release metadata**
Information used to identify, version, or publish configuration.
_Avoid_: Build output, Runtime config, User data

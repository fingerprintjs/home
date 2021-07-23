# Repositories and packages naming conventions

*All new public repositories and packages should follow naming conventions, we don't want to rename existing projects. Provided examples are for visualizing all currently available repositories with the proposed naming conventions.*

## Repositories

*The main idea in the proposed naming convention is to provide easy readability and information to the developers. Moreover, it will help us make the organization consistent. In most cases, the developer is interested in the repositories belonging to a specific product, therefore, the repository name starts with the product name. Then developer is looking for the specific project for his/her needs for the specific platform. Therefore `<project-name>-<language/platform>` suffix.*

---

*In general, `<placeholders>` should be in kebab case only, example: `fingerprintjs-agent`*

### Is the repository related to the company's product?

#### Format: `<product>-<project-name>-<language/platform>`

- `<product>` - mandatory, related product
  - *Examples: `fingerprintjs`, `fingerprintjs-pro`, `botd`*
- `<project-name>` - mandatory, descriptive name of the project
  - *Examples: `server-api-sdk`, `agent`, `client`, `integrations`*
- `<language/platform>` - optional, use when makes sense or it's plausible there will be available the same functionality for different language/platform in the future. Mostly apply to agents, wrappers, or SDKs.
  - *Examples: `javascript`, `node`, `react`, `python`*

#### Examples

- `fingerprintjs-agent` or `fingerprintjs-client`
- `botd-agent` or `botd-client`
- `botd-integrations`
- `fingerprint-android-client` or `fingerprintjs-android-client`
---

### Is the repository related to the content, blog post, article, or video? Is it just an example without any supporting content?

#### Format: `blog-<name-of-blog-or example>-<type>`

- `blog` - optional, mandatory if repository supports article and is not explanatory enough without supporting content
- `<name-of-blog-or-example>` - mandatory, should be descriptive or aligned with the blogpost name, if related to product, should start with product name
  - Examples: `adblocker-fingerprinting`, `audio-fingerprinting`, `fingerprintjs-react`
- `<type>` - mandatory, describes type of the supporting content
  - *Examples:  `demo`, `example`*

#### Examples

- `blog-adblocker-fingerprinting-demo`
- `blog-fingerprintjs-php-example`
- `blog-fingerprintjs-paywall-example`
- `blog-audio-fingerprinting-demo`
- `blog-fingerprintjs-multiple-signups-example` - used only in video but we don't to introduce a new cattegory for video
- `fingerprintjs-react-example`
---

### Does not fit into any category above?

#### Format: `<name-of-the-project>`

- `<name-of-the-project>` - should be descriptive

#### Examples

- `fingerprintjs.com`
- `nice-pg-sql-toolkit`
- `external-protocol-flooding`

---

## Packages

- The name of the package should reflect the `<product>-<project-name>` with the respect to the package registry guidelines
- The name of the package should follow package registry conventions, e.g. on npm @fingerprintjs/fingerprintjs-agent or Nuget: FingeprintJS.Botd.Client

### Examples

- `@fingerprintjs/fingerprintjs-agent` or `@fingerprintjs/fingerprintjs-client`
- `@fingerprintjs/fingerprintjs-pro-agent` or `@fingerprintjs/fingerprintjs-pro-client`
- `@fpjs-incubator/botd-agent` might be renamed in the future to `@fingerprintjs/botd-agent`

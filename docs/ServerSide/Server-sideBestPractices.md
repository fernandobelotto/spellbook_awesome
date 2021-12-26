# Server-side Best Practices

* SaaS
  * [The Twelve-Factor App](https://12factor.net/)
* Restful API
  * Heroku's [HTTP API Design Guide](https://geemus.gitbooks.io/http-api-design/content/en/), \
    Microsoft's [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design), [REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md), \
    [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api), \
    [Principles of good RESTful API Design](https://codeplanet.io/principles-good-restful-api-design/)
  * [REST API Error Codes 101](http://blog.restcase.com/rest-api-error-codes-101/)
  * [Introducing JSON](http://json.org/)
* Microservices
  * [A pattern language for microservices](http://microservices.io/patterns/index.html)
    * [Microservice Architecture](http://microservices.io/patterns/microservices.html), [Monolithic Architecture](http://microservices.io/patterns/monolithic.html)
    * Decompose by [business capability](http://microservices.io/patterns/decomposition/decompose-by-business-capability.html), [subdomain](http://microservices.io/patterns/decomposition/decompose-by-subdomain.html)
    * [Service instance per container](http://microservices.io/patterns/deployment/service-per-container.html), [Service deployment platform](http://microservices.io/patterns/deployment/service-deployment-platform.html)
    * [Externalized configuration](http://microservices.io/patterns/externalized-configuration.html), [Microservice chassis](http://microservices.io/patterns/microservice-chassis.html)
    * Service discovery ([Server-side](http://microservices.io/patterns/server-side-discovery.html), [Client-side](http://microservices.io/patterns/client-side-discovery.html)), [Service registry](http://microservices.io/patterns/service-registry.html), [Remote Procedure Invocation](http://microservices.io/patterns/communication-style/rpi.html)
    * [Database per service](http://microservices.io/patterns/data/database-per-service.html), [Shared database](http://microservices.io/patterns/data/shared-database.html)
  * [Microservices: From Design to Deployment](https://www.nginx.com/blog/introduction-to-microservices/)
  * [Microservices Resource Guide](https://martinfowler.com/microservices/)
  * API Gateway
    * [Pattern: API Gateway / Backend for Front-End](http://microservices.io/patterns/apigateway.html)
    * [Why an API Gateway?](https://www.nginx.com/blog/microservices-api-gateways-part-1-why-an-api-gateway/)
    * [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247) / [From REST to GraphQL](https://0x2a.sh/from-rest-to-graphql-b4e95e94c26b) / [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b)
    * [Serverless and GraphQL: A Perfect Match for the New Cloud Paradigm](https://thenewstack.io/serverless-graphql-perfect-match-new-cloud-paradigm/)
  * Serverless
    * [Pattern: Serverless deployment](http://microservices.io/patterns/deployment/serverless-deployment.html)
    * [Microservices without the Servers](https://aws.amazon.com/blogs/compute/microservices-without-the-servers/)
    * [The Next Layer of Abstraction in Cloud Computing is Serverless](https://read.acloud.guru/iaas-paas-serverless-the-next-big-deal-in-cloud-computing-34b8198c98a2)
    * [The essential guide to serverless technologies and architectures](https://techbeacon.com/essential-guide-serverless-technologies-architectures), \
      [An essential guide to the serverless ecosystem](https://techbeacon.com/essential-guide-serverless-ecosystem)
    * [Serverless Architecture: Five Design Patterns](https://thenewstack.io/serverless-architecture-five-design-patterns/), \
      [Serverless Code Patterns](https://serverless.com/blog/serverless-architecture-code-patterns/)
* Cloud / Distributed
  * Architecture
    * [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
    * Azure's Cloud Fundamentals - [Architecture styles](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/), [Pillars of software quality](https://docs.microsoft.com/en-us/azure/architecture/guide/pillars), [Design principles](https://docs.microsoft.com/en-us/azure/architecture/guide/design-principles/index)
  * Static
    * [Static Content Hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting), [Valet Key](https://docs.microsoft.com/en-us/azure/architecture/patterns/valet-key), [Content Delivery Network](https://docs.microsoft.com/en-us/azure/architecture/best-practices/cdn)
  * Queue / Jobs
    * [Queue-Based Load Leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling), [Competing Consumers](https://docs.microsoft.com/en-us/azure/architecture/patterns/competing-consumers), [Priority Queue](https://docs.microsoft.com/en-us/azure/architecture/patterns/priority-queue)
    * [Background jobs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/background-jobs)
  * Decompose
    * [Federated Identity](https://docs.microsoft.com/en-us/azure/architecture/patterns/federated-identity)
    * [Pipes and Filters](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters)
    * [Compute Resource Consolidation](https://docs.microsoft.com/en-us/azure/architecture/patterns/compute-resource-consolidation)
  * Configuration
    * [External Configuration Store](https://docs.microsoft.com/en-us/azure/architecture/patterns/external-configuration-store), [Runtime Reconfiguration](https://docs.microsoft.com/en-us/azure/architecture/patterns/runtime-reconfiguration)
  * Storage / Querying
    * [Cache-Aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside), [Caching](https://docs.microsoft.com/en-us/azure/architecture/best-practices/caching)
    * [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs), [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
    * [Index Table](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-table), [Materialized View](https://docs.microsoft.com/en-us/azure/architecture/patterns/materialized-view)
    * [Data partitioning](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning), [Sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)
  * [Resiliency](https://docs.microsoft.com/en-us/azure/architecture/resiliency/) / [Availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/availability)
    * [Retry](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry), [Circuit Breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker), [Transient fault handling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/transient-faults)
    * [Compensating Transaction](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction)
    * [Health Endpoint Monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring), [Leader Election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election), [Scheduler Agent Supervisor](https://docs.microsoft.com/en-us/azure/architecture/patterns/scheduler-agent-supervisor)
    * [The Reactive Manifesto](http://www.reactivemanifesto.org/)
  * Multitenant
    * [Manage Identity in Multitenant Applications](https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/)
* Old-fashioned Web Hosting / Non-distributed
  * [Ultimate Guide to Web Hosting](http://www.whoishostingthis.com/resources/web-hosting/) / [Web Hosting Beginner Guide](http://www.webhostingsecretrevealed.net/web-hosting-beginner-guide/)
* Authentication / Authorization
  * [Cookies vs Tokens: The Definitive Guide](https://auth0.com/blog/cookies-vs-tokens-definitive-guide/), \
    [The Ins and Outs of Token Based Authentication](https://scotch.io/tutorials/the-ins-and-outs-of-token-based-authentication)
  * [Introduction to JSON Web Tokens](https://jwt.io/introduction/)
  * [An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2), [Understanding OAuth2](http://www.bubblecode.net/en/2016/01/22/understanding-oauth2/)
    * [The OAuth Bible](http://oauthbible.com/)
  * [Tokens used by Auth0](https://auth0.com/docs/tokens)
    * [Understanding Refresh Tokens](https://auth0.com/learn/refresh-tokens/)
  * [How To Safely Store A Password](https://codahale.com/how-to-safely-store-a-password/), \
    [You Wouldn't Base64 a Password - Cryptography Decoded](https://paragonie.com/blog/2015/08/you-wouldnt-base64-a-password-cryptography-decoded), \
    [How to securely hash passwords?](https://security.stackexchange.com/a/31846)
  * [Weak Signature Algorithm](https://developer.mozilla.org/en-US/docs/Web/Security/Weak_Signature_Algorithm)
* Security
  * [Security Guide for Developers](https://github.com/FallibleInc/security-guide-for-developers)
    * [Understanding CSRF](https://github.com/pillarjs/understanding-csrf), [CSRF Demystified](http://www.gnucitizen.org/blog/csrf-demystified/)
    * [Cross-site Scripting (XSS) Attack](https://www.acunetix.com/websitesecurity/cross-site-scripting/)
  * [OWASP Top Ten Cheat Sheet](https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet)
  * [WebAppSec/Secure Coding Guidelines](https://wiki.mozilla.org/WebAppSec/Secure_Coding_Guidelines)
  * [Node.js Security Checklist](https://blog.risingstack.com/node-js-security-checklist/)
  * Tools - see _[Tooling > Testing](#testing) > Analysis_
* Logging / Monitoring
  * [Logging The Ultimate Guide](https://www.loggly.com/ultimate-guide/category/node/)
  * [The Definitive Guide for Monitoring Node.js Applications](https://blog.risingstack.com/monitoring-nodejs-applications-nodejs-at-scale/)
  * [Monitoring and diagnostics](https://docs.microsoft.com/en-us/azure/architecture/best-practices/monitoring)
  * Tools - see _[Tooling > Workflow](#workflow) > Monitoring_
* DevOps
  * [Deployments Best Practices](http://guides.beanstalkapp.com/deployments/best-practices.html)
  * [Start your DevOps journey](https://www.atlassian.com/devops/start-your-journey)
  * [The Practical DevOps Playbook](https://www.shippable.com/devops-playbook.html)
  * Tools - see _[Tooling > Workflow](#workflow) > Deployment > DevOps_


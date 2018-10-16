# LPM
LPM is a Laravel based Project Manager for developers, up to small teams. (Possibly more of a Team Management?)

The main purpose of this software is to help automate the setup process for starting a project, and bringing team members on board with things like auto generating repos, setting up company standards, documentation generation, and personal developer environment setup guides.

Typically these setup times can cause downtime of several hours to accomplish all these goals, LPM's goal is to bring that time down to 30 minutes or less. This includes time for the development teams to verify they're all properly connected, and conclude all teams can proceed.

Company standards are outlined to ensure during the CI process programming committed is to the companies speicifcation to insure standardization. Several unit testing suites are supported including TravisCI. 

Other automations include Laravel Forge integration for automatic subdomain / domain creations, and server creation.

Boilerplates can also be defined, and set in place when creating a project to automate easy things like Socialite integration, Cashier, and Nova integration. These can be custom defined for company specific boilerplating.

The goal is to bring standardization, productivity, and create better products using the same tools major development teams deploy but for the average programmer/small team.

## Development Timeline

### Alpha (Console Only Edition)

##### Objectives
  - Ability to create and manage Customers with integration into payment, and development services.
    - Stripe/Freshbooks?
    - GitLab/Bitbucket?
    - Boilerplate?
    - Docker Images?
  - CI integration (Travis CI?)

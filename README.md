[![Aardwolf-Social/build](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/aardwolf-build.yml/badge.svg)](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/aardwolf-build.yml)
[![Aardwolf-Social/test](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/aardwolf-test.yml/badge.svg)](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/aardwolf-test.yml)
![GitHub issues](https://img.shields.io/github/issues/Aardwolf-Social/aardwolf)
[![rust-clippy analyze](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/rust-clippy.yml/badge.svg)](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/rust-clippy.yml)
[![Docker Image CI](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/docker.yml/badge.svg)](https://github.com/Aardwolf-Social/aardwolf/actions/workflows/docker.yml)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

# Aardwolf Social

<p align="center">
  <img alt="Aardwolf Social: Powering connected social communities with open software" src="/doc/images/aardwolf-banner_solid-bg.png" />
</p>

### About
Unlike mainstream social media sites that funnel the world into a single (advertising-filled) shared experience, we recognize that individuals with different identities and interests.  Aardwolf is a free, and open-source alternative to Facebook which respects user privacy.  Aardwolf Social servers (also called instances) are able to be customized to fit your community's needs, while still being able to communicate to one another.

### Project Tour
* .github/ -- CI/CD Files related to GitHub
* aardwolf-actix/ -- The Actix backend rust application code
* aardwolf-models/ -- Web app models, and database setup files
* aardwolf-templates/ -- Legacy Frontend files
* aardwolf-test-helpers/ -- Development functional test code
* aardwolf-types/ -- Additional web app components
* aardwolf-yew-frontend/ -- The Yew frontend application code
* config/ -- Aardwolf Social app configuration files
* doc/ -- Documentation
* docker/ -- Docker files
* po/ -- Legacy directory for i18n translations
* src/ -- The source directory for the main app (pulls in other parts)
* tests/ -- Where the code validation, and coverage tests should live
* build.rs -- Rust code that directs Cargo build
* Cargo.lock -- A complete manifest of all rust crates used, including dependencies
* Cargo.toml -- A manifest of crates required to build Aardwolf
* CODE_OF_CONDUCT.md -- Our Code of Conduct rules
* db-init.sh -- This should be part of the setup/install scripts
* diesel.toml -- Tells diesel where to find the SQL migrations
* LICENSE -- The license we use for this software
* README.md -- The file you are presently reading
* ROADMAP.md -- Our development roadmap
* rust-toolchain.toml -- This tells the development environment which version of rust to use.
* SECURITY.md -- Future info for security updates
* translations -> aardwolf-templates/translations

## Homepage Screenshot
This is a screenshot of the static HTML demo.  While not a final version it does showcase the design intentions.

<p align="center">
  <img alt="Aardwolf Social: Powering connected social communities with open software" src="/doc/images/homepage-demo.png" />
</p>

###  Code of Conduct
As a COMMUNITY it is very important to us that we maintain a positive and supportive environment for everyone who wants to participate. When you join us we ask that you follow our [code of conduct](/CODE_OF_CONDUCT.md) in all interactions both on and offline.

###  Contributing
Here are the areas we could use help with!

* Rust Developers, folk that want to learn are welcome! - [Rust](https://www.rust-lang.org) 
* Frontend Developers, HTML/CSS folks that want to help with the UI/UX part of the project.
* Documentation help.  Proofreading, organization, update wiki, etc.
* Docker containers/VM's.  Some progress has been made building Docker images (for developement)

Once your ready to dive in please check out our [contributor's guidelines](/CONTRIBUTING.md), and our [roadmap](ROADMAP.md).  

#### List of Repositories
Currently Aardwolf-Social is broken down into several repositories 
- Aardwolf-Social "Main", the one you are presently on.
- [Aardwolf Social Interface](https://github.com/Aardwolf-Social/aardwolf-interface), a repo to independently work on, and test Frontend development.
- [Aardwolf Social Website](https://github.com/Aardwolf-Social/aardwolf-website), is where the Jekyll site is deployed from.

### Contact
If you have ANY questions please feel free to reach out to us!
* Chat Room: Follow the link to choose your connection method :) [#aardwolf-discussion:matrix.org](https://matrix.to/#/#aardwolf-discussion:matrix.org)
* Mastodon: [@banjofox2@hackers.town](https://hackers.town/@banjofox2).

### License
All Aardwolf Social software is licensed under the GNU Affero General Public License 
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

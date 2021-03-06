
Overview
========

> A community makes progress based on how fast it can be taught

Christoph will be building out devcomp.io into a **hackable open dev system** between
now (May 2014) and the end of 2014 while *recoding the process in weekly video conference
calls* and other learning materials. [learn.devcomp.io](http://learn.devcomp.io)

devcomp.io is a continously evolving test to see how a wide community can work together on a complex
open source system using best practices and latest tooling by following the leadership
of a small group of developers operating under the
[Programmer Anarchy](https://www.youtube.com/watch?v=uk-CF7klLdA) model.

We are seeking to collectively harmonize our toolchains into one stack we are all happy
with and can extend to our heart's content. We are seeking to work together in
real-time so our creations may rise as fast as we can imagine them.

You are welcome to participate and contribute your unique point of view.

> When you use devcomp.io and keep up with the latest changes and docs and start collaborating
> with others using devcomp.io and there is a lot of us we will create something very amazing very quickly.


Two streams of work
===================

  1. **Refining of Primitive Components (Primitives)** - 
    The set of principles and components that will act as the fabric of all derived systems.
    * Facilitated by Christoph to ensure the interests of devcomp.io and community are met.
    * **Looking for leadership**

  2. **Weaving of Primitive Components (Weaving)** - 
    The set of conventions and abstractions that will act to shape the first hackable dev system and support it's community.
    * Lead by Christoph by building devcomp.io and upstream primitive libraries.
    * **Looking for contributors**


Projects Christoph is planning on integrating
=============================================

  * https://github.com/montagejs/jasminum
  * https://github.com/c9/vfs
  * https://github.com/creationix/js-git/
  * https://github.com/montagejs/mop
  * http://ci.openstack.org/zuul/
  * https://github.com/visionmedia/debug
  * http://casperjs.org/
  * https://developers.google.com/analytics/devguides/platform/
  * https://github.com/epeli/angry-caching-proxy
  * https://github.com/afbobak/nopar/
  * http://www.jstree.com/
  * https://github.com/jordansissel/fpm
  * https://github.com/mitchellh/packer
  * https://github.com/MacGapProject/MacGap1
  * http://f.github.io/omelette/
  * https://github.com/akenn/AWESOM-0
  * https://github.com/balderdashy/sails
  * http://d3js.org/
  * http://dimplejs.org/
  * https://github.com/runtimejs/runtime



Looking for contributors to integrate
=====================================

If you are interested in contributing in any way, announce your intent in a weekly meeting so we can discuss.
Christoph can mock out a service as a starting point and discuss further details during the meetings.
This will teach everyone how to build services of all kinds.

  * https://github.com/kentonv/sandstorm ( **Runtime Isolation** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to configure/control containers.
      * Create a dev UI that uses API to full extent.
    
    Once these tasks are done this service can be integrated to start to provide isolated
    runtime contexts for untrusted third party code.

  * https://www.gitlab.com/gitlab-ce/ ( **Collaboration** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to configure repositories and set access rules.
    
    Once these tasks are done this service can be integrated to hold all the projects
    you are working on in one place with a UI that can be extended by other services.

  * https://juju.ubuntu.com/ ( **Deployment** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to configure and manage deployments.
    
    Once these tasks are done this service can be integrated to automatically deploy
    subsets of services and packages into various environments.

  * https://www.openstack.org/ ( **Deployment** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to configure and manage deployments.
    
    Once these tasks are done this service can be integrated to automatically deploy
    subsets of services and packages into OpenStack environments.

    This [overview video](https://www.youtube.com/watch?v=c1GFoY4btpo) mentions that the new breed of apps running
    on OpenStack are *intelligent webapps*. devcomp.io is a hackable dev service to build intelligent webapps.

    The key is to use a comprehensive development system where complex relationships may be modeled (using meta data and simulation) with
    extensive tooling and finally persisted to runtime configuration structures that are optimized for distribution.
    The runtime structures must only encode information relevant to the runtime context and thus most data
    associtaed with a component may be dropped.

  * http://www.mozilla.org/firefox ( **Development** )
      * Create a service that can be used for local development.
      * Create an API that can be used to configure and launch profiles.
    
    Once these tasks are done this service can be used to provide an integrated
    browser for development.

  * https://developer.mozilla.org/en-US/Add-ons/SDK ( **Deployment** )
      * Create a service that can be used for local development.
      * Create a service that can be used for bundling of extensions.
      * Create an API that can be used to create, build, bundle and launch extensions.
    
    Once these tasks are done this service can be used to provide an integrated
    solution for delivering and running privileged code on in user's browsers.

  * Secure EcmaScript ( **Runtime Isolation** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to load code, run it and get security reports back.
      * Create a dev UI that uses API to full extent.
    
    Once these tasks are done this service can be used to provide an integrated
    solution for vetting third party code before loading it into unsecured runtimes.

  * https://github.com/digitalbazaar/forge ( **Communication** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to perform all kinds of common cryptography operations.
      * Create a dev UI that uses API to full extent.
    
    Once these tasks are done this service can be used to provide an integrated
    solution for end-to-end encryption on the server, in apps and in the browser.

  * http://etherpad.org/ ( **Collaboration** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to create, configure and manage pages and page sets.
      * Create a dev UI that uses API to full extent to create ad-hock collab workspaces.
    
    Once these tasks are done this service can be used to provide an integrated
    solution for realtime collaboration on any textual document or source file.

  * http://www.w3.org/respec/ ( **Documentation** )
      * Create a service that can be deployed with pio.
      * Create an API that can be used to create, manage and update specs.
      * Create a dev UI that uses API to full extent to create specifications.
      * Create an abstract JSON schema to declare all aspects of a spec in JSON.
      * Create a service that can read source code and annotations and overlay it with extra manual declarations to create a spec.
    Once these tasks are done this service can be used to provide an integrated
    solution for realtime documentation of API and other specifications.


Specifications to watch and play with
=====================================

  * http://www.w3.org/TR/2014/WD-service-workers-20140508/
    * http://jakearchibald.com/2014/service-worker-first-draft/

  * http://ortc.org/wp-content/uploads/2014/04/ortc1.html

  * http://waterken.sourceforge.net/web-key/
    * http://lists.w3.org/Archives/Public/www-tag/2014May/0037.html


Issues needing help
===================

  * https://github.com/pinf-io/pio.cli/issues/1


General TODO
============

  * Lock down server. As a start see: https://www.digitalocean.com/community/articles/initial-server-setup-with-ubuntu-14-04


Random Links
============

### DevOps

  * http://newrelic.com/devops/toolset - A Short List of DevOps Tools

### DevLogic

  * Mark Miller
    * [Computer Security as the Future of Law](https://docs.google.com/file/d/0Bw0VXJKBgYPMS0J2VGIyWWlocms/edit) (presentation video)
    * [Smart Contracts, Prediction, Singularities, and more](http://www.michaelcovel.com/2014/06/16/ep-248-mark-miller-interview-with-michael-covel-on-trend-following-radio-jun-17-2014/) (podcast)


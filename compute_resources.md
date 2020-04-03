# Compute resources

[ELIXIR Europe](https://elixir-europe.org/) and [Galaxy](https://galaxyproject.org/) have kindly agreed to contribute with computing resources. If you can do so as well, please add your resources and your information here.

## European Galaxy server (https://usegalaxy.eu)

The European Galaxy server is offering all its compute resource for all researchers. You have access to more than 2400 tools from different scientific domains (genomics, proteomics, metabolomics, cheminformatics ...), more than 3,000 CPU cores, 50TB of memory and GPUs. The majority of resources are contributed by the de.NBI cloud. If more resources are needed we can shortly access the [pulsar-network](https://pulsar-network.readthedocs.io) and distribute jobs across Europe.

Galaxy can be accessed and controlled via a rich API. For example via Python using a library called [bioblend](https://bioblend.readthedocs.io/en/latest/).

With https://live.usegalaxy.eu the Galaxy project is also offering Juypter Notebooks or RStudio instances for everyone that needs external compute resources. Those environments can access the storage resources from Galaxy and therefor permanent storage that can easily linked to Notebooks.

If you have any questions or problems, please contact `galaxy@informatik.uni-freiburg.de`.

## Arvados instance (https://biohackathon.curii.com)

Arvados is an open source platform for managing biomedical data and
running Common Workflow Language (CWL) workflows on that data.  It has
both web-based and command line user interfaces available.  Thanks to
generous support from AWS, Curii has set up an instance of the Arvados
platform to support the virtual Biohackathon.

https://biohackathon.curii.com

Requires Google account to log in.  After you have created an account,
ask @Peter Amstutz or @Michael Crusoe on the biohackathon Slack to activate
your account.

### What can you do with it?

* Manage data
 * Upload/download files from browser, command line, or SDK
 * Identify collections of files by name, uuid, or content address (hash)
 * Set and query structured metadata on collections of files
 * Share projects with other users and groups
* Run CWL workflows
 * Scale-out across compute nodes, run workflows from multiple users
* A foundation to build other applications
 * Use the APIs for data storage and access, permissions, running workflows, etc
 * We may be able to spin up servers for teams building web apps, just ask!

### Learn more

During the biohackathon

* We will do an Arvados training (TBD)
* We will share the slides used for the training
* We will be on the biohackathon Slack at #tech-helpdesk and Gitter at
  https://gitter.im/arvados/community to answer questions

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
both web-based and command line user interfaces available.  Curii has
set up an instance of the Arvados platform to support the virtual
Biohackathon.

https://biohackathon.curii.com

Requires Google account to log in.  After you have created an account,
ask @Peter Amstutz or @Michael Crusoe on the biohackathon Slack
(#tech-helpdesk or #workflows) to activate your account.

## ELIXIR Compute Platform Resources

ELIXIR Nodes run [computing services](https://elixir-europe.org/services/tag/compute) that can be accessed by research projects. Many additional computing resources have been made available to support COVID-19 research projects including: 
  * Access to Docker Orchestrators including Mesos and OpenStack access, Kubernetes/OKD and potentially GPUs where needed. For access request & other queries please join  `#elixir-resources`slack [channel](https://join.slack.com/share/I0113JB2P9Q/tHQPzqdxPXJjPpAcRrNJxwt5/enQtMTAzNzYyMzA5MTMzMC1jYmI1MTkzNGQ2ZTZiMTExZjhmYTQzNGMyNDllOWYwOTAyZDllNmEyNTkwNGM1NTE5NTllNDVkMzljMmY4ZWM1)
  * [de.NBI cloud, ELIXIR-Germany](https://www.denbi.de/news/866-de-nbi-cloud-resources-available-to-fight-covid-19) provides priority access for projects relating to COVID-19
  * CSC (ELIXIR-Finland) has [prioritised access](https://www.csc.fi/-/resursseja-covid-19-pandemian-vastaiseen-tutkimukseen) to its [cloud services](https://research.csc.fi/computing) for COVID-19 research 
  * [e-INFRA CZ](https://e-infra.cz) (ELIXIR-Czech) offer relaxed access conditions to supercomputer resources, storage services and distributed compute resources
  * A specific Galaxy COVID-19 instance for genomic analysis is available through [Laniakea](https://laniakea-elixir-it.github.io/2020/03/27/covid19-docker-flavor.html), ELIXIR Italy’s on-demand platform 
  * EMBL-EBI located in the UK is contributing [EMBASSY Cloud resources](https://www.embassycloud.org) as detailed on the European Open Science Cloud, [EOSC Marketplace](https://marketplace.eosc-portal.eu/services/embassy-cloud)
  * SIB (ELIXIR-Swiss) is providing a ready-to-use slurm workload manager with a scientific software stack via the [ExPASy SIB Portal](https://www.expasy.org/)
  * ELIXIR-Swiss and ELIXIR-Finland have provided a common Virtual Machine (VM) that contains key resources in a single directory for the Gene Expression hackathon group but should be extensible to e.g. collaborative teams and wider hackathon type events. This helps lower technical barriers and get more people involved more quickly.
  * [IFB (ELIXIR France)](https://www.france-bioinformatique.fr/en/action-covid-19) is providing a [federated set of high performance compute and cloud resources](https://www.france-bioinformatique.fr/en/infrastructure-0) including national and regional servers


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

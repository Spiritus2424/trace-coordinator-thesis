# Résumé d'article



## Article 1: Kernel-level tracing for detecting stegomalware and covert channels in Linux environments

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_M7206888c178a2c96ed6M660c10178163190

Résumé: Utiliser les traces pour détecter des communications entre processus qui résoulverait à une faille de sécurité

## Article 2: Critical Path Analysis through Hierarchical Distributed Virtualized Environments Using Host Kernel Tracing

Lien: https://www.engineeringvillage.com/app/doc/?docid=inspec_19d99efb181d01b1ee9M7f9f1017816355

Résumé: Générer un graph d'execution en utilisant des traces kernel d'une machine Hote. Cela permet de retrouver le chemin critique, ainsi d'identifier ce qui ralentit le système.

## Article 3: Misertrace: Kernel-level request tracing for microservice visibility

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_M59a0c57d182eb2635a1M756e1017816355

Résumé: Un Framework (MiSeRTrace) qui permet de tracer des microservices (end-to-end) en utilisant uniquement des traces kernel.

## Article 4: Wait Analysis of Distributed Systems Using Kernel Tracing

Lien: https://www.engineeringvillage.com/app/doc/?docid=inspec_Me85477f156320dbaddM4cf910178163171

Résumé: Profiler des systèmes hétérogènes et distribué en récoltant des evenements de traces kernels (operating system events, namely scheduling, interrupts and network events)

## Article 5: How Much Integrated Development Environments (IDEs) Improve Productivity? 

Lien: http://www.jsoftware.us/vol8/jsw0810-05.pdf

Résumé: Amélioration de la productivité des developpeurs qui utilise des IDEs comme Visual Studio. L'article présente une amélioration de la productivité dans certains aspects, mais à cause de la complexité de l'outil cela a pour effet de ralentir le stade de productivité rechercher.

## Article 6: Visual Studio Code in Introductory Computer Science Course: An Experience Report

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_13e73ad218748bc5874M5f8710178165143

Résumé: L'article présente l'efficacité d'introduire VsCode dans une classe pour des programmeurs débutants et qui peut être reproduit en dehors d'une classe python.

## Article 7: Decoupling language and editor - The impact of the language server protocol on textual domain-specific languages

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_18c912fe16a6fa6f421M65ac10178163167

Résumé: Comparer l'avantage du Language Server Protocol (LSP) et du Domain Specific Language (DSL). L'étude montre que le LSP facilite l'intégration entre les différents IDE.


## Article 8: The IDE portability problem and its solution in Monto

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_Mbaee6421593c48ae91M4e9c10178163171

Résumé: Cette article présente une architecture qui met de l'avant le découplage entre les languages de programmation et les IDEs. Résultats concluant avec un temps de réponse très acceptable même avec le overhead.

## Article 9: A Concurrency-Agnostic Protocol for Multi-Paradigm Concurrent Debugging Tools

Lien: https://www.engineeringvillage.com/app/doc/?docid=cpx_M20b2080d161b3998b4dM67d81017816339

Résumé: This paper proposes a concurrency-agnostic debugger protocol that decouples the debugger from the concurrency models employed by the target application. As a result, the underlying language runtime can define custom breakpoints, stepping operations, and execution events for each concurrency model it supports, and a debugger can expose them without having to be specifically adapted.

## Article 10: Protocol-Based Interactive Debugging for Domain-Specific Languages

Lien: https://hal.science/hal-04124727/

Résumé: L'article propose une architecture pour:
- offrir un deboguage interactive peu importe le DSL, sans prendre en compte le domaine de DSL et comment le DSL runtime est implémenté.
- Connaitre l'effort pour prendre un DSL existant et l'adapter au protocol
- Savoir si l'approche peut definir et utiliser des domain-specific existant
- Savoir si l'approche permet être intégré avec un effor minimal avec des IDEs qui implémente DAP

## Article 11: Scalable, Distributed AI Frameworks: Leveraging Cloud Computing for Enhanced Deep Learning Performance and Efficiency

Lien: https://arxiv.org/pdf/2304.13738.pdf

Résumé: Présente différent framework et architecture distribué pour le AI. Des benchmarks et des problèmes etc


## Article 12: Toward Sustainable HPC: Carbon Footprint Estimation and Environmental Implications of HPC Systems

Lien: https://arxiv.org/pdf/2306.13177.pdf

Résumé: Évalue l'empreinte carbone des systèmes HPC (en production et en stage de développement).


## Article 13: Analyzing Resource Utilization in an HPC System: A Case Study of NERSC’s Perlmutter

Lien: https://link.springer.com/chapter/10.1007/978-3-031-32041-5_16

Résumé: Prends connaissance des ressources consommer des noeuds dans un système HPC. Après un mois d'utilisation, il remarque que les CPUs et les GPUs ne sont pas totalement utilisé. Surtout pour les lots de travail qui implique des GPUs.


## Article 14: Distributed Cloud Monitoring Using Docker as Next Generation Container Virtualization Technology

Lien: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7443771

Résumé: Explique l'avantage d'utiliser des conteneurs au lieu de VM dans les systèmes


## Article 15: Implementation of ATLAS Distributed Computing monitoring dashboards using InfluxDB and Grafana

Lien: https://www.epj-conferences.org/articles/epjconf/pdf/2020/21/epjconf_chep2020_03031.pdf

Résumé:

## Article 16: Towards a Framework for Monitoring and Analyzing High Performance Computing Environments Using Kubernetes and Prometheus

Lien: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9060302

Résumé: L'infrastructure proposé assitera dans l'orchestration et déploiement des services, à automatiser des téléversement de données d'analyses, corréler multiple données provenant de différent source et mettre des limites pour des aleters pour des problèmes principales.  
<!-- English version -->
This comprehensive infrastructure will assist in
centrally orchestrating services and deployments, automatically
analyzing streaming data, correlating multiple-sourced data,
and thresholding alerts to identify core issues from a single
view. The comprehensive framework proposed in this paper
provides orchestration and management of the complex deployments of cluster and services by using Kubernetes platform and provides easy monitoring of Kubernetes nodes and
services via Prometheus operators. Moreover, the framework
also enables the real-time monitoring and visualizations by
utilizing Grafana tools.

## Article 17: Big data analytics on Apache Spark

Lien: https://link.springer.com/article/10.1007/s41060-016-0027-9

Résumé: Présente les composantes principales de spark ainsi de l'architecture pour comment spark fait pour analyser du big data  


## Article 18: ANALYSE DÉTAILLÉE DE TRACE EN DÉPIT D'ÉVÉNEMENTS MANQUANTS

Lien: https://publications.polymtl.ca/3248/

Résumé: Étudier le problème des événements perdus dans une trace lors de son analyse, et d’apporter des solutions permettant d’indiquer les incohérences et d’y remédier. Pour cela, nous avons utilisé des machines à états finis, puisque ce formalisme de représentation permet de modéliser le système étudié, en définissant la façon dont les événements génèrent des changements d’états. Le tout implémenter dans Tracecompass.

## Article 19: Programming on Parallel Machines

Lien: https://web.cs.ucdavis.edu/~matloff/matloff/public_html/158/PLN/ParProcBook.pdf

Résumé: 

## Article 20: Distributed Computation of the Critical Path from Execution Traces

Lien: dans le dossier

Résumé: Propose une nouvelle architecture pour calculer le chemin critique de manière distribuer. Consiste à distribuer les différents calcules et ensuite les aggrégers sur un noeud pour faire les derniers calcules.

## Artcile 21: Trace Visualization with Java Pathfinder using Theia Trace Viewer

Lien: https://www.diva-portal.org/smash/get/diva2:1711513/FULLTEXT01.pdf

Résumé: Migrate Tracecompass Java Pathfinder into Theia Trace Viewer Extension

## Article 22: Open Tracing Tools: Overview and Critical Comparison

Lien: https://arxiv.org/pdf/2207.06875.pdf

Résumé: Open Tracing Tools: Overview and Critical Comparison


## Article 23: MÉTHODES EFFICACES DE PARALLÉLISATION DE L'ANALYSE DE TRACES NOYAU

Lien: https://publications.polymtl.ca/1899/

Résumé: 


## Article 24: Programming on Parallel Machines

Lien: https://web.cs.ucdavis.edu/~matloff/matloff/public_html/158/PLN/ParProcBook.pdf

Résumé: 


## Article 25: How to Build a Scalable Prometheus Architecture

Lien: https://logz.io/blog/prometheus-architecture-at-scale/


Résumé: 


## Article 26: Monitoring architecture solutions for large organizations

Lien: https://assets.nagios.com/downloads/general/docs/Monitoring_Architecture_Solutions_For_Large_Organizations.pdf

Résumé: 

## Article 27: The lttng tracer : A low impact performance and behavior monitor for gnu/linux  p. 209–224.


Lien: https://www.researchgate.net/publication/228692715_The_LTTng_tracer_A_low_impact_performance_and_behavior_monitor_for_GNULinux

Résumé: 

## Article 28: HPCTOOLKIT: tools for performance analysis of optimized parallel programs

Lien: https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.1553


## Article 29: perf: Linux profiling with performance counters

Lien: https://perf.wiki.kernel.org/


## Article 30: Combining Instrumentation and Sampling for Trace-Based Application Performance Analysis

Lien: https://link.springer.com/chapter/10.1007/978-3-319-16012-2_6

## Article 31: Linux Programmer's Manual, 2016

Lien: http://man7.org/linux/man-pages/man2/perf_event_open.2.html

## Article 32: OProfile

Lien: http://oprofile.sourceforge.net/about/


## Article 33: Scalable Tools for Non-Intrusive Performance Debugging of Parallel Linux Workloads

Lien: https://tu-dresden.de/zih/forschung/ressourcen/dateien/projekte/perf/perf_paper_2014.pdf?lang=en


## Article 34: R-SHT: A state history tree with R-Tree properties for analysis and visualization of highly parallel system traces

Lien: https://www.sciencedirect.com/science/article/abs/pii/S0164121217302108?via%3Dihub

Résumé:


## Article 35: Distributed Architecture for an Integrated Development Environment, Large Trace Analysis, and Visualization

Lien: https://www.mdpi.com/1424-8220/21/16/5560
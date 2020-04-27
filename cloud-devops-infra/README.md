# Cloud, DevOps, Infra

- [System / Infra](#system--infra)
- [Compute & Storage](#compute--storage)
- [Grid computing / Super computing](#grid-computing--super-computing)
- [Cloud services](#cloud-services)
- [Tools](#tools)
- [CPU](#cpu)
- [FPGA](#fpga)
- [GPU](#gpu)
- [TPU](#tpu)
- [IPU](#ipu)
- [Performance](#performance)
- [Misc](#misc)
- [Contributing](#contributing)

## System / Infra

  - [serveo.net](http://serveo.net) - Serveo is an SSH server just for remote port forwarding. When a user connects to Serveo, they get a public URL that anybody can use to connect to their localhost server. See link for other SSH and related alternatives, useful to be able to serve resources across devices i.e. access GPU or other hardware accelerators from another device remotely. | [How to forward my local port to public using Serveo?](https://medium.com/@osanda.deshan/how-to-forward-my-local-port-to-public-using-serveo-4979f352a3bf) | [Serveo on GitHub](https://github.com/milio48/serveo)
  - [Inlets](https://github.com/alexellis/inlets) by [Alex Ellis](https://github.com/alexellis) | [Get started](https://github.com/alexellis/inlets#get-started) | [Video](https://www.youtube.com/watch?v=jrAqqe8N3q4&feature=youtu.be)
  - [KnockKnock by @huggingface](https://github.com/huggingface/knockknock) | [tweet](https://twitter.com/kartik_godawat/status/1187224635051409408)

## Compute & Storage
  
  - [Cray Computers](https://www.cray.com/ai) | [Artificial Intelligence](https://www.cray.com/solutions/artificial-intelligence) | [Accel AI](https://www.cray.com/solutions/artificial-intelligence/cray-accel-ai) | [Cryp-em](https://www.cray.com/solutions/cryo-em) | [Autonomous Vehicles](https://www.cray.com/solutions/autonomous-vehicles) | [Geospatial AI](https://www.cray.com/solutions/geospatial-ai)
  - [GraphCore's IPU](README.md#ipu)
  - [Lambda Labs](https://lambdalabs.com/)
  - NGD Systems: [Technology](https://www.ngdsystems.com/technology) [deadlink] | [Solutions](https://www.ngdsystems.com/solutions) - High Compute Storage, Scalable Computational Storage [deadlink] | [NGD Systems: Ensuring AI Advancement with Intelligent Storage](https://www.insightssuccess.com/ngd-systems-ensuring-ai-advancement-with-intelligent-storage/)

## Grid computing / Super computing

- Grid Engine: [wikipedia](https://en.wikipedia.org/wiki/Univa_Grid_Engine) | [Univa website](http://www.univa.com/products/) | [Datasheet](http://www.univa.com/resources/files/univa-unisight-datasheet.pdf)
- [BOINC](https://boinc.berkeley.edu/) - High-Throughput Computing with BOINC | [Tech Docs](https://boinc.berkeley.edu/trac/wiki/ProjectMain) | [Download BOINC](https://boinc.berkeley.edu/download.php) | [GitHub](https://github.com/BOINC/boinc)
- [Cray Computers](https://www.cray.com/solutions/supercomputing-as-a-service) - Supercomputing as a Service

## Cloud services

  - [vast.ai](about-vast.ai.md) - GPU Sharing Economy. One simple interface to find the best cloud GPU rentals. Reduce cloud compute costs by 3X to 5X
  - [paperspace](https://www.paperspace.com/) - The first cloud built for the future. Powering next-generation applications and cloud ML/AI pipelines. Paperspace is built to scale with your team - pay as you go option for individuals.
  - [NextJournal](https://nextjournal.com/) - The notebook for
reproducible research
  - [valohai](https://www.valohai.com/) | [docs](https://docs.valohai.com/) | [blogs](https://blog.valohai.com) | [GitHub](https://github.com/valohai) | [Videos](https://www.youtube.com/channel/UCiR8Fpv6jRNphaZ99PnIuFg) | [Showcase](https://valohai.com/showcase/) | [Slack](http://community-slack.valohai.com/) | [@valohaiai](https://twitter.com/@valohaiai) - Valohai is a machine learning platform. It runs your experiments in the cloud, tracks your experiment history and streamlines data science workflows. DEEP LEARNING MANAGEMENT PLATFORM. Machine Orchestration, Version Control and Pipeline Management for Deep Learning.
  - [Lambda Cloud GPU Instances](https://lambdalabs.com/service/gpu-cloud) - GPU Instances for Deep Learning & Machine Learning
  - [NavOps](http://www.univa.com/products/navops.php) - Cloud Migration for HPC | [Datasheet](http://www.univa.com/resources/files/univa-navops-launch-datasheet.pdf)
  - [Verne Global: HPC Cloud](https://verneglobal.com/solutions/hpc-cloud) | [NVIDIA DGX Ready](https://verneglobal.com/dgxready)
  - [Weights and Biases](https://wandb.com) | [Learn more about WandB](../data/about-Weights-and-Biases.md)

## Tools

  - [snakemake](https://snakemake.readthedocs.io/en/stable/) - The Snakemake workflow management system is a tool to create reproducible and scalable data analyses. [Slides](https://slides.com/johanneskoester/snakemake-talk-40min#) | [PyPi](https://pypi.org/project/snakemake/)
  - [plz](http://github.com/prodo-ai/plz) - Plz (pronounced "please") runs your jobs storing code, input, outputs and results so that they can be queried programmatically.
  - [valohai](https://www.valohai.com/) | [docs](https://docs.valohai.com/) | [blogs](https://blog.valohai.com) | [GitHub](https://github.com/valohai) | [Videos](https://www.youtube.com/channel/UCiR8Fpv6jRNphaZ99PnIuFg) | [Showcase](https://valohai.com/showcase/) | [Slack](http://community-slack.valohai.com/) - Valohai is a machine learning platform. It runs your experiments in the cloud, tracks your experiment history and streamlines data science workflows. DEEP LEARNING MANAGEMENT PLATFORM. Machine Orchestration, Version Control and Pipeline Management for Deep Learning.
  - [Seldon](https://www.seldon.io/open-source/) - Model deployment platform, on kubernetes clusters. | [docs](https://docs.seldon.io/projects/seldon-core/en/latest/) | [github](https://github.com/SeldonIO/seldon-core/blob/master/readme.md) | [use-cases](https://www.seldon.io/use-cases/) | [blogs](https://www.seldon.io/blog/) | [videos](https://www.youtube.com/channel/UCZq33lhQWAsd-8NDqOdjN_g/videos?view_as=subscriber) | [Seldon's opensource library for MachineLearning model inspection and interpretation](https://github.com/SeldonIO/alibi)
  - [kedro](https://github.com/quantumblacklabs/kedro) | [other kedro projects](https://github.com/quantumblacklabs) | [docs](https://kedro.readthedocs.io/en/latest/) | [Kedro-Viz](https://github.com/quantumblacklabs/kedro-viz) | [kedro-examples](https://github.com/quantumblacklabs/kedro-examples) | [Blogs](https://duckduckgo.com/?q=medium.com+kedro&ia=web) | [Video](https://www.youtube.com/watch?v=KEdmJ2ADy_M) | [gitter.im/py-sprints/kedro](https://gitter.im/py-sprints/kedro) | [pypi](https://pypi.org/project/kedro/) - Kedro is a workflow development tool that helps you build data pipelines that are robust, scalable, deployable, reproducible and versioned.
  - [Lambda Stack](https://lambdalabs.com/lambda-stack-deep-learning-software) - One-line installation of TensorFlow, Keras, Caffe, Caffe, CUDA, cuDNN, and NVIDIA Drivers for Ubuntu 16.04 and 18.04.
  - [Apache Airflow](https://airflow.apache.org/) - Airflow is a platform to programmatically author, schedule and monitor workflows. Use airflow to author workflows as directed acyclic graphs (DAGs) of tasks. The airflow scheduler executes your tasks on an array of workers while following the specified dependencies.
  - [Nextflow](https://www.nextflow.io/) - Data-driven computational pipelines. Nextflow enables scalable and reproducible scientific workflows using software containers. It allows the adaptation of pipelines written in the most common scripting languages.
  - [StackHPC suites of repositories: AI, ML, DL, Cloud, HPC](https://github.com/stackhpc) | [StackHPC](http://stackhpc.com/)
  - [cortex](https://www.cortex.dev/) - Machine learning deployment platform: Deploy machine learning models to production
  - [#Uber introduces #Fiber, an #AI development and distributed training platform for methods including reinforcement learning and population-based learning.](https://www.linkedin.com/posts/inna-vogel-nlp_introduction-to-fiber-activity-6649564159828606976-Jmi6) 
  - [H2O Framework for Machine Learning](https://www.linkedin.com/posts/data-science-central_h2o-framework-for-machine-learning-activity-6635175109445382144-ISgt)
  - [ML Framework: Introducing Ludwig, a Code-Free Deep Learning Toolbox](https://eng.uber.com/introducing-ludwig/)
  - [ML Pipelines](https://www.linkedin.com/posts/artificialintelligenceconsultant_activity-6639429321943539712-vRug)
  - [ML Framework by Abhishek Thakur](https://www.linkedin.com/posts/abhi1thakur_machinelearning-python-datascience-activity-6644289209181978625-wZtJ)
    - [Episode 1 Intro and building a machine learning framework](https://lnkd.in/e5Syy5N)
    - [Episode 2 A Cross Validation Framework](https://lnkd.in/eDjFTGW)
    - [Episode 3 Handling Categorical Features in Machine Learning Problems](https://lnkd.in/e9Qc5fe)
    - [Episode 4 Simple and Basic Binary Classification Metrics](https://lnkd.in/eGZtcPW)
  - [See also: Data > Programs and Tools](../data/programs-and-tools.md#programs-and-tools)

## CPU

  - Probing the CPU (Linux/MacOS)
      - [libcpuid](http://libcpuid.sourceforge.net/index.html)
      + Zero overhead performance capturing: use `/proc/interrupts` and `/proc/softirqs`
      + Non-zero overhead, less accurate: use the PMU (capture on- and off-core events)
  - Probing the CPU (Windows)
      - [perfview](https://github.com/Microsoft/perfview) - general profiling on Windows
      - [perfview for .net](https://www.infoq.com/presentations/perfview-net) - excellent overview by Sasha Goldshtein
  - Intel
    - [Intel® Developer Zone](https://software.intel.com/en-us/home)
    - [Intel® AI Developer Home Page](https://software.intel.com/en-us/ai)
    - [Intel® AI Developer Webinar Series](https://software.seek.intel.com/AIWebinarSeries?registration_source=IDZ) | [All webinars listing](https://intelvs.on24.com/vshow/IntelWebinarEvents/#content/2033414)
    - The PlaidML Tensor Compiler - [webinar](https://event.on24.com/eventRegistration/console/EventConsoleApollo.jsp?&eventid=2026509&sessionid=1&username=&partnerref=&format=fhaudio&mobile=false&flashsupportedmobiledevice=false&helpcenter=false&key=B27628973F7FA8B9758983E373E36ED1&text_language_id=en&playerwidth=1000&playerheight=700&overwritelobby=y&eventuserid=246511746&contenttype=A&mediametricsessionid=207230377&mediametricid=2857349&usercd=246511746&mode=launch)
    - nGraph - Unlocking next-generation performance with deep learning compilers: [webinar](https://intelvs.on24.com/vshow/IntelWebinarEvents/#content/2033414) | [slides](https://event.on24.com/event/20/33/41/2/rt/1/documents/resourceList1565185524584/s_ngraphwebinar1565185512750.pdf) | [homepage](https://www.ngraph.ai/) | [github](https://github.com/NervanaSystems/ngraph)
    - Also see [Intel](../courses.md#intel) in [Courses](../courses.md#courses)
 
 _Thanks to the great minds on the [mechanical sympathy](https://groups.google.com/forum/#!forum/mechanical-sympathy) mailing list for their responses to my queries on CPU probing._

## FPGA

  - [Using FPGAs for Datacenter Acceleration](https://event.on24.com/eventRegistration/EventLobbyServlet?target=lobby20.jsp&eventid=2033432&sessionid=1&eventuserid=246511756&key=8678836B54A84876D7338D7BF7F87B88) | [Windows AI](https://docs.microsoft.com/en-us/windows/ai/) | [Intel® Distribution of OpenVINO™ Toolkit: Develop Multiplatform Computer Vision Solutions](https://software.intel.com/en-us/openvino-toolkit)
  - Also see [FPGA](../courses.md#fpga) in [Courses](../courses.md#courses)

## GPU

  - [Know your GPU](https://gist.github.com/neomatrix369/256913dcf77cdbb5855dd2d7f5d81b84)
  - [GPU Server 1 of 2](./gpus/GPU-Server-side-1-of-2.jpg) | [GPU Server 2 of 2](./gpus/GPU-Server-side-2-of-2.jpg) | [Applications of GPU servers](./gpus/Applications-of-GPU-Server.jpg) - [checkout the manufacturers](http://manli.com/en/)
  - [Embedded Vision Solutions for NVIDIA Jetson Series](https://www.avermedia.com/professional/category/nvidia_jetson_solutions) | [Embedded Vision Family Brochure](http://storage.avermedia.com/web_release_www/Solutions/Embedded_Vision_Solutions_brochure_20190429.pdf)
  - Avermedia Box PC & Carrier (works with NVIDIA Jetson): [1](./gpus/Avermedia-Box-PC-and-Carrier-1-of-2-works-with-NVidia-Jetson.jpg) | [2](./gpus/Avermedia-Box-PC-and-Carrier-2-of-2-works-with-NVidia-Jetson.jpg)
  - [Accelerating Wide & Deep Recommender Inference on GPUs](https://www.linkedin.com/posts/miguelusque_accelerating-wide-deep-recommender-inference-activity-6614061742936870913-oG2v)
  - [Create GPU Arrays and Move to DL Frameworks with DLPack](https://www.linkedin.com/posts/activity-6625024900585316352-PucI)
  - [GPU Accelerated data viz tools](https://www.linkedin.com/posts/murraydata_data-todashboard-activity-6623659330199781376-YIUQ)
  - [This tool is nice to monitor not only RAPIDS but also deep learning workloads](https://www.linkedin.com/posts/miguelusque_gpu-dashboards-in-jupyter-lab-activity-6611570222585401344-n1Qe)
  - See [NVIDIA's RAPIDS](./gpus/rapids.md)

## TPU

  - [How to harness the Powers of the Cloud TPU](https://medium.com/bitgrit-data-science-publication/how-to-harness-the-powers-of-the-cloud-tpu-3939dc363d9f)
  - [How-tos](https://cloud.google.com/tpu/docs/how-to)
  - [All tutorials](https://cloud.google.com/tpu/docs/tutorials)
  - Command-line interface
      - https://cloud.google.com/sdk/gcloud/reference/compute/tpus/
      - https://cloud.google.com/tpu/docs/setup-gcp-account
  - [Cloud TPU tools](https://cloud.google.com/tpu/docs/cloud-tpu-tools)
  - [Performance Guide](https://cloud.google.com/tpu/docs/performance-guide)
  - [TPU Estimator API](https://cloud.google.com/tpu/docs/using-estimator-api)
  - [Using BFloat](https://cloud.google.com/tpu/docs/bfloat16)
  - [Advanced Guide to Inception V3 on Cloud TPU](https://cloud.google.com/tpu/docs/inception-v3-advanced)
  - Examples
    - [Using TPUs docs](https://www.tensorflow.org/guide/using_tpu)
    - [Hello, TPU in Colab notebook](https://colab.research.google.com/drive/1MefSa2P6UP-gO2S0-dCjIjbvRxOnewZK#scrollTo=llcFb_P_BNPM)
    - [Useful TPU and Model example](https://colab.research.google.com/drive/1F8txK1JLXKtAkcvSRQz2o7NSTNoksuU2#scrollTo=mQnZM5JYlRvs)
    - [Measure Performance on TPU, in a notebook](https://colab.research.google.com/drive/11VnRHgG_067fwPGhMwBz0SmplLsf9X5h)
    - [Financial Time series notebook](https://cloud.google.com/solutions/machine-learning-with-financial-time-series-data)
    - [Web traffic prediction](https://adaptpartners.com/technical-seo/website-traffic-prediction-with-google-colaboratory-and-facebook-prophet/)
    - [GAN example, TPU version](https://colab.research.google.com/drive/1EkZPH6UE_I1a2TQfDDpjjqA7Na0_qd6v)

## IPU

  - [GraphCore](http://graphcore.ai) | Videos: [Simon Knowles - More complex models and more powerful machines](https://www.youtube.com/watch?v=dLvkF_TmyAc&feature=youtu.be) | [Graphcore tech Concept](https://youtu.be/cSXbhEsUUGo?t=916) | [A new kind of hardware designed for machine intelligence - GraphCore Presentations](http://www.bristol.bcs.org.uk/2017/graphcore.pdf) | [V‍ID‌EO‌‍: SCA‌LING‌‍ THRO‌UG‍HP‌‍U‌T P‍R‌O‍C‍ESSO‌‍RS FO‌‍R‍ MAC‌HINE INTELLIG‌ENC‌‍E](https://www.graphcore.ai/posts/video-scaling-throughput-processors-for-machine-intelligence)
  - [What makes the IPU's architecture so efficient](https://www.linkedin.com/posts/graphcore_if-youd-like-to-know-what-makes-the-ipus-activity-6617716840384778240-PUS0)
  - [How do we implement large-scale #NLP models on IPU](https://www.linkedin.com/posts/graphcore_arianna-saracino-product-support-engineer-activity-6615949485463920640-7Pwa)
  - [Graphcore are making Poplar Software Documentation publicly available](https://www.graphcore.ai/posts/graphcore-makes-poplar-sdk-docs-publicly-available?utm_content=121700693&utm_medium=social&utm_source=linkedin&hss_channel=lcp-10812092)
   - [Watch the Graphcore quick guide to the #IPU](https://www.graphcore.ai/products/ipu?utm_campaign=Machine%20Intelligence%20Positioning&utm_content=120000808&utm_medium=social&utm_source=linkedin&hss_channel=lcp-10812092) [LinkedIn Post](https://www.linkedin.com/posts/graphcore_ipu-ai-semiconductors-activity-6640930639287730176-bRvL)

## Performance

  - [MLPerf](https://mlperf.org/) - Fair and useful benchmarks for measuring training and inference performance of ML hardware, software, and services.
  - [MLPerf introduces machine learning inference benchmark suite...](https://venturebeat.com/2019/06/24/mlperf-introduces-machine-learning-inference-benchmark-suite/)
  - [ONE DEEP LEARNING BENCHMARK TO RULE THEM ALL](https://www.nextplatform.com/2018/08/30/one-deep-learning-benchmark-to-rule-them-all/)
  - [mlbench: Distributed Machine Learning Benchmark](https://mlbench.github.io/) - A public and reproducible collection of reference implementations and benchmark suite for distributed machine learning algorithms, frameworks and systems.
  - [EEMBC MLMark Benchmark](https://www.eembc.org/mlmark/) - The EEMBC MLMark benchmark is a machine-learning (ML) benchmark designed to measure the performance and accuracy of embedded inference. 
  - [DeepOBS: A Deep Learning Optimizer Benchmark Suite](https://arxiv.org/abs/1903.05499)
  - [PMLB](https://biodatamining.biomedcentral.com/articles/10.1186/s13040-017-0154-4) - a large benchmark suite for machine learning evaluation and comparison
  - [Deep Learning Benchmarking Suite](https://github.com/HewlettPackard/dlcookbook-dlbs) | [HPE Deep Learning Cookbook](https://www.hpe.com/software/dl-cookbook)

## Misc

- [👉 Docker CLI & Dockerfile Cheat Sheet 👈](https://www.linkedin.com/posts/asif-bhat_docker-quick-reference-activity-6622407319550562304-xxdj)

# Contributing

Contributions are very welcome, please share back with the wider community (and get credited for it)!

Please have a look at the [CONTRIBUTING](../CONTRIBUTING.md) guidelines, also have a read about our [licensing](../LICENSE.md) policy.

---

Back to [main page (table of contents)](../README.md)
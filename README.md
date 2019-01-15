# awesome-discoveries
> This is a curated list of inspiring and eclectic - mostly ordered - discoveries I made during my readings, experiments and job decisions making being the CTO for a world leading drone company.

## Content

* [Architecture and Infrastructure](#architecture-and-infrastructure)
* [Algorithms](#algorithms)
* [Data science](#data-science)
* [Artificial Intelligence](#artificial-intelligence)
* [Development](#development)
* [Development languages specific](#development-languages-specific)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Bash](#bash)
* [Various tools](#various-tools)
* [Inspiration and sources](#inspiration-and-sources)
* [Growing a startup](#growing-a-startup)
* [License](#license)

## Architecture and Infrastructure

- [CAP Theorem](https://www.itechart.com/blog/all-you-didnt-know-about-cap-theorem/) - The CAP theorem extensive description - and its drawbacks. The CAP (Consistency, Availability, Partition-Tolerance) theorem helps selecting the best suited database solution for a particular problem. In this article, you will also discover its limits.
- Serverless paradigm
  - [Epsagon](https://epsagon.com/) - Observability is as of today the bigest challenge in serverless infrastructure - even with latest AWS enhancements on Cloudwatch, at least allowing textual search across your logs. Epsagon provides an observability SaaS board which creates - among other features - an execution map of all your connected services on a per API call basis. Tremendously useful.
  - [Seed](https://seed.run/) - A solution that industrializes in a few clicks your serverless deployments. Frow manual command line deployment to production ready deployment board in minutes, literally.
  - [The serverless stack](https://serverless-stack.com/) - The guys behind [Seed](https://seed.run/) wrote an amazing book which push you straight to your first true serverless deployment proving how fast a team can soon focus on building value instead of spending time to set an infrastructure.
- AWS
  - [AWS Blog](https://aws.amazon.com/blogs/aws/) - If you want to be amazed by the innovation pace of AWS, be sure to subscribe to their blog, in addition to the day to day announcements you also get hands on blog post and a lot of inspiration.
- Cloud native
  - [Cloud Native Computing Foundation](https://www.cncf.io/) - The entry point to an open source journey in the cloud computing
- Tools for local development
  - [minio.io](https://www.minio.io/features.html) - A distributed object storage server that mimic the "de facto standard API for object storage", named AWS S3.
- API design
  - [REST is the new SOAP](https://medium.freecodecamp.org/rest-is-the-new-soap-97ff6c09896d) - An article with a counter-current point of view that emphasizes every negative aspects of `REST`.

## Algorithms
- [Fountain Codes](https://divan.github.io/posts/fountaincodes/) - Transfer information over noisy channels. Example given with [txqr](https://github.com/divan/txqr) a project that uses Animated GQ to transfer data over mobiles.

## Data science

- Dataviz:
  - [Edward Tufte’s The Visual Display of Quantitative Information](https://amzn.to/2ROaWUl) - The text book to read when you are entering the world of data visualization.
  - [Importance of Skepticism in Data Science](https://jhu-advdatasci.github.io/2018/lectures/12-being-skeptical.html) - This long code detailed lecture aims at illustrating the bias that you might follow when you are interpreting data you have manipulated. _(`R`)_
  - [3rd Wave Data Visualization](https://towardsdatascience.com/3rd-wave-data-visualization-824c5dc84967) - Elijah Meeks author of [semiotic](https://github.com/emeeks/semiotic) - A react + d3.js library, a famous combo I experienced with success and pleasure - points to problems into the current landscape of data vizualization.
- Data management:
  - [DVC](https://dvc.org/doc/dvc-philosophy/core-features) - A neat structured approach to the data science workflow management aiming to become a standard as git has become in the development workflow.

## Artificial Intelligence

- Source for inspiration, technology watch:
  - [stateoftheart.ai](https://www.stateoftheart.ai) - Not entirely up to date on a few topic I'm aware of, but it deserves a look for everyone interested to get up to speed in a particular topic they are looking into. A well ordered index for state of the art results in machine learning.
  - [MIT Technology Review](https://www.technologyreview.com/) - An endless stream of popular science, in particular in machine learning.
  - [arXiv](http://arxiv.org/) - The 1.5 Million e-prints open access to paper that democratized Machine Learning over the globe. 99% of papers we were using are coming from that place. It is even inspiring to look for information from that source.
  - [aiindex2018](http://cdn.aiindex.org/2018/AI%20Index%202018%20Annual%20Report.pdf?utm_campaign=Artificial%2BIntelligence%2BWeekly&utm_medium=email&utm_source=Artificial_Intelligence_Weekly_92) - The one place to go if you need insights into Artificial Intelligence in numbers: from the number of papers published by category to state of the art performances and human-level performance milestones going through VC funding landscape.
  - [Flops, brought to you by AI](https://bigthink.com/technology-innovation/artificial-intelligence-failures?rebelltitem=3#rebelltitem3) - A short list of top flop in AI in one way or another related to physical world.

- Embedding:
  - [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/abs/1503.03832) - A solution which transforms an image into a compact Euclidean space allowing to enhance Face Recognition. [implementation](https://github.com/davidsandberg/facenet) _(`Embedding`, `image2vec`, `Tensorflow`)_
  - [Grasp2Vec: Learning Object Representations from Self-Supervised Grasping](https://arxiv.org/abs/1811.06964) - Embedding used in reinforcement learning to represent reality through physcial world robot grasping. [Google article](https://ai.googleblog.com/2018/12/grasp2vec-learning-object.html) _(`Embedding`, `image2vec`, `RL`)_

- Compression
  - [Learned Video Compression](https://arxiv.org/pdf/1811.06981.pdf) - A traditional codec architecture where elements are replaced by Machine Learning ones. Results: the new codec outperforms all existing video codecs.

- Natural Language Processing and voice recognition
  - Assisted writings
    - ["I want to live"](https://youtu.be/BhKw71AeOg4) - A 60 second clip entirely scripted from an AI studying 15 years of worth of award-winning ads.
    - [Bertie the Forbes' CMS](https://digiday.com/media/forbes-built-a-robot-to-pre-write-articles-for-its-contributors/) - Forbes [announced](https://www.forbes.com/sites/forbesproductgroup/2018/07/11/entering-the-next-century-with-a-new-forbes-experience/#5e9b28803bf4) its new AI powered CMS (Content Management System) where AI helps and support content creator from image selection to draft article writings.
  - [Accurate Online Speaker Diarization with supervised learning](https://ai.googleblog.com/2018/11/accurate-online-speaker-diarization.html) - Detect interlaced speakers in a speech. But beware, code is not the original and you cannot access data. _(`PyTorch`, `Embedding`)_

- Medicine
  - [Brain2Speech](https://www.sciencemag.org/news/2019/01/artificial-intelligence-turns-brain-activity-speech) - Experiment using AI to get our voice out of our head automatically. The promise to an accessible world for disable people.
  - [Learning to Design RNA](https://arxiv.org/pdf/1812.11951.pdf) - Reinforcement Learning used to design RNA sequence to test _(`RL`)_
  - [Face2Gene](https://www.nature.com/articles/d41586-019-00027-x#ref-CR1) - From Professional crowdsourcing to real life medicine aid use case, the face2gene application that spot genetic disorders is a promise for future medicine.

- Data Generation
  - Face Generation
    - [Inside the world of AI that forges beautiful art and terrifying deepfakes](https://www.technologyreview.com/s/612501/inside-the-world-of-ai-that-forges-beautiful-art-and-terrifying-deepfakes/) - A 2018 overview of GAN and latests progress in the field of generative networks. _(`GAN`)_
    - [AI software can dream up an entire digital world from a simple sketch](https://www.technologyreview.com/s/612503/ai-software-can-dream-up-an-entire-digital-world-from-a-simple-sketch/) - A photorealistic 3D engine renderer made out of GAN. _(`GAN`)_
  - Object generation
    - [Visual Object Networks: Image Generation with Disentangled 3D Representation](http://papers.nips.cc/paper/7297-visual-object-networks-image-generation-with-disentangled-3d-representations.pdf) - How a set of specialized networks learn to generate 3D objects. _(`GAN`, `3D`)_

- Setting a machine learning project:
  - [How to build a machine learning team when you are not google or facebook](https://www.wandb.com/blog/how-to-build-a-machine-learning-team-when-you-are-not-google-or-facebook) - Pragmatism has always been at the heart of our strategy regarding our machine learning projects. This article formalize best practice that a good manager will discover himself executing a machine learning project. One thing for sure, as of today, "it’s more efficient to teach a engineers machine learning than to teach machine learning practitioners how to be good engineers." And, with the right project and the rock solid computer scientist you can kickstart a machine learning in a small team.
  - [IBM Machine Learning Maturity Model](https://arxiv.org/pdf/1811.04871.pdf) - Presents a set of best practices to implement when a company wants to deploy machine learning at scale and in a friendly fashion with enterprise landscape. Many of them might be complicated to achieve, anyhow, it will highlight any shortcomings in your projects or potential area of focus.

- Games:
  - [Starcraft AI competition](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/2018/aiide/) - The state of the Starcraft competition. Samsung 1st, Facebook 2nd.

- Experiments & Art:
  - Music:
    - [Semi-Conductor](https://experiments.withgoogle.com/semi-conductor) - A Google AI experiment that allow one to conduct an orchestra from the browser
  - Painting:
    - [amalGAN](http://areben.com/project/amalgan/) - [Alexander Reben](http://areben.com/cv/) used brain waves, GAN network and side supportive networks to generate a set of visually unusual paintings that are physically reproduced in a Chinese town: a human-machhine global collaboration.
  - Spotting AI-generated faces.
    - [nikola MIT experiment](http://nikola.mit.edu/experiment) - An online test that asks you to spot Generated faces with [NVIDIA's Progressive GAN](https://research.nvidia.com/publication/2017-10_Progressive-Growing-of). I wasn't 100% correct. 😅
    - [How to recognize fake AI-generated images] (https://medium.com/@kcimc/how-to-recognize-fake-ai-generated-images-4d1f6f9a2842) - An extensive look into AI-generated images that will train yourself to spot fake images.

- Data
  - [Adding Diversity to Images with Open Images Extended](https://ai.googleblog.com/2018/12/adding-diversity-to-images-with-open.html) _(`diversity`)_
  - [Open Images Dataset V4](https://storage.googleapis.com/openimages/web/index.html)
  - [Kaggle Datasets](https://www.kaggle.com/datasets)
  - [BigQuery Datasets](https://cloud.google.com/bigquery/public-data/)
  - [AWS OpenData](https://aws.amazon.com/opendata/)

- Performance and hardware
  - [A full hardware guide to Deep Learning](http://timdettmers.com/2018/12/16/deep-learning-hardware-guide/) - If you want to build your own local hardware for training, this is a must read.
  - [Best Deals in Deep Learning Cloud Providers](https://towardsdatascience.com/maximize-your-gpu-dollars-a9133f4e546a) - Where does it more effective to train your models. AWS is the most expensive.

- Ethics
  - [Researchh priorities for robust and beneficial Artificial Intelligence](https://futureoflife.org/ai-open-letter/) - The first round of people who expressed worries in the current research state of AI. It should be directed toward beneficial outcomes: "our AI systems must do what we want them to do".
  - [China’s top AI scientist drives development of ethical guidelines](https://www.scmp.com/news/china/science/article/2181573/chinas-top-ai-scientist-drives-development-ethical-guidelines) - Yes it is time for the world to align itself on where it wants to go

## Development

- Programming paradigms
  - [Goodbye, Object Oriented Programming](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53) - That lecture helps to jolt away preconceived ideas that have been learned over the years OR simply point usual mistakes. Take a look. _(`OO`)_
- Code quality
  - [Code climat](https://codeclimate.com/quality/) - A lot of tools in the industry, give a try to this one.

## Development languages specific

### `vscode`

[`vscode`](https://code.visualstudio.com/) replaces the long 1st in my heart [`Sublime`](https://www.sublimetext.com/): it has proven to turn myself into a better "prototyper", data extractor and developer in the past year. It is reliable, able to handle large files, has a small memory footprint and perfectly extendable.

### `Python`

- Performances
  - [From Python to Numpy](http://www.labri.fr/perso/nrougier/from-python-to-numpy/) - An online book that teaches how to migrate from standard `Python` to `Numpy` through vectorization.
  - [Seven Strategies for Optimizing Numerical Code](https://speakerdeck.com/jakevdp/seven-strategies-for-optimizing-numerical-code) - An overview of 7 technics to enhance `Python` performances.
  - [Python Data Visualization landscape](https://www.anaconda.com/blog/developer-blog/python-data-visualization-2018-why-so-many-libraries) - An heavy loaded landscape of Datavizualisation tools in python ready for convergence.

### `Ruby`

- Command line:

### `Bash`

- Command line:
  - [bash-boilerplate](https://github.com/alphabetum/bash-boilerplate) - Name speaks for itself. Even today, bash might be the best answer to a simple clear problem that needs a repetitive way to being reproduced. This repository kickstarts it even further.
  - [bash-oo-framework](https://github.com/niieani/bash-oo-framework) - If `bash-boilerplate` is not enough you should find everything you need here.

## Various tools

- Command line enhancements
  - [graphcurl](https://github.com/hasura/graphqurl) - Turn your command line into a `curl` like tool for GraphQL, keeping the exploration taste of [graphiql](https://github.com/graphql/graphiql)
  - [jq](https://stedolan.github.io/jq/) - Must have tool for any modern devOps or serious people working with a `Terminal` 😄 _(`json`)_
  - [rb](https://github.com/thisredone/rb) - Extends your command line workflow with a fully loaded inline ruby interpreter. Just in case you are alergic to `awk` and `sed` _(`Ruby`)_
  - [terminalizer](https://github.com/faressoft/terminalizer) - A way to record your `Terminal` and create gif images.
  - [tldr](https://github.com/tldr-pages/tldr) - Ever wante to get just what you need instead of verbose man pages?
  - [q](https://github.com/harelba/q) - Run SQL queries directly on CSV files.
  - [up](https://github.com/akavel/up) - Write pipe processing with instant live preview of command results.
- Docker
  - [dive](https://github.com/wagoodman/dive) - Have you ever wanted to look into your `Dockerimage` result layers. Here you are!
- Markdown
  - [`gh-md-toc`](https://github.com/ekalinin/github-markdown-toc.go) - Generate table of content from a `.md` file.
- Security
  - [gitleaks](https://github.com/zricethezav/gitleaks) - Waiting for github next move in the security landscape, here is a way for you to scan code source for unencrypted secrets. 👮‍♂️

## Inspiration and sources

- For this document structure:
  - https://github.com/whitone/awesome-discoveries/
  - https://github.com/sindresorhus/awesome
  - https://github.com/joho/awesome-code-review
- Companies:
  - Providing data science and AI "as a service":
    - [namr](https://namr.com/) - Their mission is to create value from open data.
    - [deepomatic](https://www.deepomatic.com/) - Concept is providing AI implementation acceleration service for fortune 500.
    - [mobeye](https://www.mobeye-app.com/en/home) - How to crowdsource data annotation through a mobile application that let's people earn money
  - Providing github like services dedicated to ML:
    - [Comet.ml](https://comet.ml)
- Source of further reading:
  - News letters:
    - [Data Elixir](https://dataelixir.com/) - My most productive and de facto favorite newsletter regarding Artificial Intelligence and Data science in general
    - [Changelog](https://changelog.com/weekly) - Staying up to date with the developer community and finding fun stuffs
  - [MIT Techreview](https://technologyreview.com) - The only one to which I have been willing to pay a subscription so far

## Growing a startup

- [Can you bootstrap a startup on the side?](https://justinjackson.ca/bootstrap-side-project) - Build you own path based on your experience, will and target
- [This is hard](https://justinjackson.ca/hard) - Never forget that stopping your project is the main reason for failure
- Management
  - Working remotely
    - [All-remote workforce](https://www.businessinsider.fr/us/gitlab-zapier-remote-emsisoft-invision-workforce-2019-1) - A series of pros and cons from all-remote companies like Zapier and GitLab. Some ideas to gather, some lessons to learn or confirm you're not alone. Some are applicable to global companies. World is changing, cost of living is increasing in a lot of places, talents are all around the world. One thing for sure, you will see more and more all-remote rather than the contrary.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
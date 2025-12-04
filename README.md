# Awesome ML For Scientists [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Resources for research teams running machine learning experiments without enterprise budgets or ML engineering backgrounds.

This list is for **domain scientists** like marine biologists, climate researchers, ecologists, and others—who need to run ML experiments. It focuses on accessible compute, reproducible workflows, and resources that are for researchers and scientists, not scaling companies.

---

## Contents

- [GPU Access](#gpu-access)
  - [Free Tiers & Academic Programs](#free-tiers--academic-programs)
- [Reproducibility & Hardware Transparency](#reproducibility--hardware-transparency)
- [ML for Non-Engineers](#ml-for-non-engineers)
  - [Courses & Tutorials](#courses--tutorials)
  - [Beginner-Friendly Tools](#beginner-friendly-tools)
  - [Books for Scientists](#books-for-scientists)
- [Domain-Specific Resources](#domain-specific-resources)
  - [Marine Biology & Ecology](#marine-biology--ecology)
  - [Climate & Environmental Science](#climate--environmental-science)
  - [Medical & Biological Imaging](#medical--biological-imaging)
- [Experiment Tracking & Data Management](#experiment-tracking--data-management)

---

## GPU Access

### Free Tiers & Academic Programs

Providers that understand academic needs.

- [Pandoro](https://github.com/breadboardfoundry/pandoro) - Fixed monthly pricing with complete hardware transparency. Designed for research teams needing reproducible compute environments. Consumer GPUs with disclosed specifications.
- [National Research Platform](https://nationalresearchplatform.org/) - NSF-funded distributed computing for US researchers.
- [XSEDE/ACCESS](https://access-ci.org/) - Free HPC allocations for US-based research projects.
- [EUROHPC](https://eurohpc-ju.europa.eu/) - European high-performance computing resources for researchers.

---

## Reproducibility & Hardware Transparency

Tools and practices for ensuring your ML results can be reproduced.

### Why Hardware Transparency Matters

Most cloud providers don't disclose exact hardware specifications. This creates problems for scientific reproducibility—you can't cite "some GPU on AWS" in a methods section. Look for providers that tell you exactly what hardware you're using.

### Reproducibility Guides

- [The Turing Way](https://the-turing-way.netlify.app/) - Comprehensive guide to reproducible research. Start here.
- [Reproducible Research in Computational Science](https://doi.org/10.1126/science.1213847) - Foundational paper on computational reproducibility.
- [Ten Simple Rules for Reproducible Computational Research](https://doi.org/10.1371/journal.pcbi.1003285) - Practical checklist.

---

## ML for Non-Engineers

Resources that don't assume you have a CS degree.

### Courses & Tutorials

- [Fast.ai](https://www.fast.ai/) - "Practical Deep Learning for Coders." Top-down approach designed for practitioners. Highly recommended starting point.
- [Coursera Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction) - Andrew Ng's updated course. More theoretical but well-explained.
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) - Free, practical introduction.
- [Hugging Face Course](https://huggingface.co/course) - NLP and transformers for beginners.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) - From experiments to deployment. Good for understanding the full picture.

### Beginner-Friendly Tools

Frameworks that minimize boilerplate and configuration.

- [FastAI](https://docs.fast.ai/) - High-level library that handles common patterns. Great for image classification.
- [Keras](https://keras.io/) - Simple API for neural networks. Good documentation.
- [Hugging Face Transformers](https://huggingface.co/docs/transformers) - Pre-trained models with simple APIs. Good for NLP and vision.
- [scikit-learn](https://scikit-learn.org/) - Classical ML with consistent API. Start here for non-deep-learning.
- [PyTorch Lightning](https://lightning.ai/docs/pytorch/stable/) - Reduces PyTorch boilerplate while keeping flexibility.

### Books for Scientists

- [Deep Learning for Coders with fastai and PyTorch](https://course.fast.ai/Resources/book.html) - Practical approach for non-CS backgrounds (Howard & Gugger).
- [Hands-On Machine Learning with scikit-learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/) - Comprehensive practical guide (Géron).
- [Python for Data Analysis](https://wesmckinney.com/book/) - Foundation in Pandas and data manipulation (McKinney).

---

## Domain-Specific Resources

### Marine Biology & Ecology

- [VIAME](https://www.viametoolkit.org/) - Video and Image Analytics for Marine Environments. Object detection for underwater footage.
- [DeepMatcher](https://github.com/Laska-jl/DeepMatcher.jl) - Photo-ID matching for wildlife research.
- [Wildlife Insights](https://www.wildlifeinsights.org/) - AI-powered platform for camera trap analysis.
- [MegaDetector](https://github.com/microsoft/CameraTraps/blob/main/megadetector.md) - Microsoft's pre-trained model for camera trap images. Detects animals, people, vehicles.
- [FathomNet](https://fathomnet.org/) - Image database for ocean exploration with ML tools.
- [Zooniverse ML](https://www.zooniverse.org/lab) - Citizen science platform with ML integration for image classification.

### Climate & Environmental Science

- [ClimateBench](https://github.com/duncanwp/ClimateBench) - Benchmarks for ML in climate science.
- [WeatherBench](https://github.com/pangeo-data/WeatherBench) - Benchmark dataset for data-driven weather prediction.
- [Pangeo](https://pangeo.io/) - Community for big data geoscience. Tools and examples for climate ML.
- [TorchGeo](https://torchgeo.readthedocs.io/) - PyTorch library for geospatial data.
- [Radiant MLHub](https://mlhub.earth/) - Open repository for geospatial training data.

### Medical & Biological Imaging

- [MONAI](https://monai.io/) - PyTorch framework for healthcare imaging. Well-documented.
- [StarDist](https://github.com/stardist/stardist) - Cell/nuclei detection in microscopy images.
- [CellPose](https://www.cellpose.org/) - Generalist cell segmentation. Works out of the box.
- [napari](https://napari.org/) - Multi-dimensional image viewer with ML plugin ecosystem.
- [QuPath](https://qupath.github.io/) - Open source pathology image analysis.

---

## Experiment Tracking & Data Management

### Organizing Your Work

- [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) - Standardized project structure. Widely adopted.
- [Research Compendium](https://research-compendium.science/) - Guidelines for bundling code, data, and documentation.

### Notebooks & Documentation

- [Jupyter](https://jupyter.org/) - Interactive notebooks. Standard for exploration.
- [JupyterBook](https://jupyterbook.org/) - Turn notebooks into publishable documentation.
- [Quarto](https://quarto.org/) - Scientific publishing system. Notebooks to papers.
- [Marimo](https://marimo.io/) - Reactive Python notebooks with better reproducibility than Jupyter.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

We especially welcome:
- Resources for domain scientists in fields not yet covered
- Free or low-cost tools accessible to grant-funded researchers
- Guides and tutorials written for non-CS audiences

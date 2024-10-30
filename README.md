# Hi there!
```💌 : daniel [dot] rivers [at] uni-potsdam [dot] de```

I'm Morgan Rivers, a student located in Berlin, Germany. Right now I am a master's student in climate and sustainability studies at Potsdam Universität. I'm also interested in philosophy, intentional communities, science and technology, and global catastrophic risks. 

In addition to the repositories below, you can check out my [website](https://morganrivers.com/) and [Google Scholar profile](https://scholar.google.com/citations?user=nXYa_QEAAAAJ) for publications and preprints.

You can find code repositories which support my research, and my standalone software projects (mostly focused on accomplishing various tasks in linux), and the papers that I'm currently working on below:

### Research Code Repositories

I believe in open source software and open science. All of my major software projects I've developed past 2019 are available below.

- **ALLFED Integrated Model**  
  An integrated food supply model for global trade and resilient food adaptations in nuclear winter. It has been used to advise various governmental and non-governmental organizations on preparations and cost-effectiveness estimates, as well as guiding research and prioritization at [ALLFED](https://allfed.info). See the latest preprint [here](https://allfed.info/images/pdfs/Preprint%20V2.0%20Integrated%20assessment%20ALLFED.docx.pdf).  
  [View on GitHub](https://github.com/allfed/allfed-integrated-model)

- **GeomagneticModel**  
  I developed a model which incorporates thermal models of HVT tie bar hot spots, historical geoelectric field estimates, and a global conductivity model to estimate the risk of long-term power outage due to transformer overheating failure. Assuming a uniform 33% HVT spare capacity, our analysis indicates that a 1 in 10,000 year storm would result in approximately 1% of the population in Europe and North America experiencing a long-term (months to years) electricity loss. The model is unusually broad and end-to-end, encompassing a wide geographic scope and long time horizons. I hope that it inspires similar work on other global catastrophic risks. You can view the preprint for the paper [here](https://arxiv.org/abs/2403.18070).  
  [View on GitHub](https://github.com/allfed/GeomagneticModel)

- **mink**  
  A major reformatting and open-sourcing of IFPRI's [mink](https://www.ifpri.org/publication/mink-details-global-gridded-crop-modeling-system) crop model courtesy of Ricky Robertson. I added a python analysis, got it running multi-threaded, made a singularity container for it, and added lots of comments and some documentation. However, the code is sufficiently legacy that I do recommend interested parties generally start with a more modern crop model, such as [WOFOST](https://www.wur.nl/en/research-results/research-institutes/environmental-research/facilities-tools/software-models-and-databases/wofost.htm).  
  [View on GitHub](https://github.com/allfed/mink)

- **LosingIndustryCropYields**  
  A general linear statistical model of crop yields to evaluate the effect of loss of industrial capacity, including chemical nitrogen production, tractors, and powered irrigation on global crop yields. This is the only repository on the list in which I was not the primary author, which in this case is Jessica Morsdorf, as it was used for her master's thesis. However, I contributed the data processing and heavily advised the process, as she had not set up a code repository before. The published paper is [here](https://pubmed.ncbi.nlm.nih.gov/38223898/). The full text is available on the [ALLFED](https://allfed.info) website.  
  [View on GitHub](https://github.com/allfed/LosingIndustryCropYields)

- **ImportReliantIrrigation**  
  A secondary repository used to generate data for `LosingIndustryCropYields`. Used to calculate the total global area that is dependent on electricity or diesel power. I have not been able to find any other estimates for this, so I hope this repository is useful to other researchers.
  [[View on GitHub]](https://github.com/allfed/ImportReliantIrrigation)

### Linux Software Projects

- **ClockifyAutomation**  
  Automate time invoicing using Google Calendar, ActivityWatch, and the Clockify API. This is my largest Unix productivity tool, as it automatically tracks and categorizes my billable contractor hours based on watching my window titles on my laptop, and the categorizations I choose for each window title. Forget about manually entering time ever again!  
  [View on GitHub](https://github.com/morganrivers/ClockifyAutomation)

- **noise_masking**  
  Have you ever thought about the fact that the frequency band of speech is fairly narrow, all things considered, and a Gaussian white noise spectrum that is quiet in the majority of audible frequency space would block speech quite well? I have! This script records audio, generates a spectrogram, fetches audio statistics, and plays back audio with adjusted volume in real-time based on the system volume. It's great for blocking voices at coffee shops and communal spaces, but it doesn't have to be very loud as it focuses the audio only on the frequency range that is the loudest in the environment. It works great in combination with noise-cancelling headphones. I cannot figure out why this is not a standard feature in noise canceling headphones! Hopefully they add it eventually.  
  [View on GitHub](https://github.com/morganrivers/noise_masking)

- **problem_set_ocr**  
  A neat little repository which automates my physics homework submissions. Uses GPT-4-vision optical character recognition to scan handwritten problem sets to valid LaTeX in seconds. You can use it for any handwritten documents which you wish to format in LaTeX.  
  [View on GitHub](https://github.com/morganrivers/problem_set_ocr)

- **timezone_and_flux_from_ip**  
  Updates the system timezone and the color temperature of the display based on the geolocation of the current IP address. The script is designed to be used with NetworkManager's dispatcher to be executed whenever a network connection goes up.  
  [View on GitHub](https://github.com/morganrivers/timezone_and_flux_from_ip)

- **simple_todolist**  
  The simplest ToDo list program you can imagine, that's why it's so great.
  [View on GitHub](https://github.com/morganrivers/simple_todolist)

- **bash_history_improved**  
  This is my configuration so that bash history actually works! Infinite number of line storage, test to see everything is set up correctly, does not occasionally delete back to 500 lines. [NOTE: I now use fish which (mostly) resolves all of those issues, so this repo may be a bit out of date]  
  [View on GitHub](https://github.com/morganrivers/bash_history_improved)

- **how_to_ssh_key**  
  Tutorial for adding SSH keys on GitHub and command line.  
  [View on GitHub](https://github.com/morganrivers/how_to_ssh_key)

- **standard_protocol_to_use_git**  
  This tutorial will walk you through a standard Git workflow, which includes creating a new branch, checking its status, adding changes, committing them, and finally, pushing them to the remote repository. The workflow also includes how to prepare for a pull request. This is basic knowledge that seems to currently not be widespread and tutorials don't really seem to focus on the key basics. Professional software engineers really need to learn this kind of thing if they haven't already, so I made a little tutorial.  
  [View on GitHub](https://github.com/morganrivers/standard_protocol_to_use_git)

### Papers I'm currently working on
- **Draft paper on Whale Translation**
  Communicating with whales would be really interesting, and potentially very important for the whales to communicate their needs. We might learn something from Whalekind too. I've got an idea to try to decode whale language using pretrained large language models, which I wrote up in this short document.
[View on GitHub](https://github.com/morganrivers/whale_translation/blob/previews/master/paper.pdf)
- **Draft paper on AI Consciousness**
  It seems like everyone is confused about consciousness, and AI consciousness has become ever more relevant with the recent AI advancements. This paper is an attempt to add some rigour into the question of AI consciousness by running [the ACT test](https://ceur-ws.org/Vol-2287/short2.pdf) from [Susan Schneider](https://en.wikipedia.org/wiki/Susan_Schneider) against current LLM architectures, and introduces a training methodology by which such architectures might be expected to improve their performance on this test.  
[View on GitHub](https://github.com/morganrivers/consciousness_paper/blob/previews/master/paper.pdf)


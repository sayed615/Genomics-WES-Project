# Genomics-WES-Project
## Day One: Introduction to Genetics, Genomics, and Precision Medicine

Welcome to Week One of our  series! Today’s focus is on establishing a solid foundation in genetics, genomics, and precision medicine—and understanding how sequencing data is generated and analyzed.

## Resources for Day One

Below are the key resources you need to review today:

### 1. Genetics, Genomics, and Precision Medicine
- **Resource:** [Genomics and Precision Medicine (YouTube)](https://www.youtube.com/watch?v=edXEzu9cGgg&t=1845s&pp=ygUfZ2Vub21pY3MgYW5kIHByZWNpc2lvbiBtZWRpY2luZQ%3D%3D)
- **Description:** This video introduces the basic concepts of genetics, genomics, and how precision medicine leverages genomic data to tailor medical treatment.

### 2. Illumina Introduction to Sequencing Data Analysis
- **Resource:** [Illumina Introduction to Sequencing Data Analysis (YouTube)](https://www.youtube.com/watch?v=XdoAnsDPMfA&pp=ygUgd2hvbGUgZXhvbWUgc2VxdWVuY2luZyBleHBsYWluZWQ%3D)
- **Description:** Learn about Illumina’s sequencing technology and an overview of the sequencing data analysis process.

### 3. Bioinformatics Workflow of Whole Exome Sequencing
- **Resource:** [GDC DNA Seq Variant Calling Pipeline Documentation](https://docs.gdc.cancer.gov/Data/Bioinformatics_Pipelines/DNA_Seq_Variant_Calling_Pipeline/)
- **Description:** Explore a detailed bioinformatics workflow—from raw data through variant calling—for whole exome sequencing.

### 4. What is the Difference Between Genetics and Genomics?
- **Resource:** [Difference Between Genetics and Genomics (YouTube)](https://youtu.be/9p2q867t7Ow?si=mTme8SboDU0_w4p5)
- **Description:** This video clarifies the differences between genetics and genomics, which is crucial for understanding personalized medicine.

## Day 2: Today is a bit technical

**Task 0: Learn how to use Git and GitHub**
- **Instructions:**
1. Follow this tutorial on YT (https://youtu.be/tRZGeaHPoaw?si=vDTa13s5iRsiFpp6),
(https://youtu.be/b9fL9y_71d4?si=xwuyrjBrnE-I9rvK)
2. Post one question or insight in GitHub Discussions from what you learned on the first day on this repo** (https://github.com/ttobio/Genomics-WES-Project.git)

### Additional Resources - u01  
Here are some additional resources that helped me understand the concepts better:  
- [Markdown Guide](https://www.markdownguide.org/) - A comprehensive guide on Markdown syntax.  
- [GitHub Docs](https://docs.github.com/en) - Official GitHub documentation.  
- [Video Tutorial on GitHub & Markdown](https://youtu.be/fDkR0TDR9dI?si=vILUoDYfh2m4U4Cm) - A helpful video explaining GitHub and Markdown concepts.

### Additional Resource - u02
## Git & GitHub Tutorial

[![Git & GitHub Tutorial](https://img.youtube.com/vi/Q6G-J54vgKc/0.jpg)](https://youtu.be/Q6G-J54vgKc?si=5tfCH_6tXJwteamL)

A simple and excellent video to learn Git and GitHub step by step (arabic source).

**Task 1: Install Docker on WSL**
- **Objective:** Set up Docker on your Windows Subsystem for Linux.
- **Instructions:**  
  1. Follow this tutorial on YT (https://youtu.be/5RQbdMn04Oc?si=S1xmGl2okvKhWyJm) to install and configure Docker.
  2. Verify your installation by running `docker --version` in your terminal.

**Task 2: Install Bioinformatics Tools**
- **Tools:**  
  - **FastQC:** For quality control of sequencing data.
  - **BWA:** For aligning sequencing reads to a reference genome.
- **Instructions:**  
  1. Fastqc should be installed on your system but if not using conda `conda install bioconda::fastqc`
  2. Install BWA `conda install bioconda::bwa`
  2. Ensure that both tools run properly from the command line (e.g., try `fastqc --help` and `bwa`).

## Discussion and Feedback

- **Discussion:** Post any questions or installation issues in our GitHub Issues page.
- **Reflection:** Write a short reflection (2-3 sentences) about what you learned today and any challenges you encountered. Share this in the discussion forum.

## Day 3: Get a rest

**Task 1: Your first pull request**
- **Instructions**
1. Clone this repository on you local machine `git clone https://github.com/ttobio/Genomics-WES-Project.git`
2. Create a new file in the assignments folder with your user id --> example u00.txt
3. Add and commit your changes and pull a request
- *You can type whatever you want in this file, just don't add confdential info*
- *This should be easy and it is covered in the YT videos provided*

**Task 2: Get to know markdown files**
- **Instructions**
1. [Get familiar with the markdown files](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. Apply this knowledge to the readme file (This file): maybe add resource that helped you and isn't here

- **Reflection:** Write a short reflection (2-3 sentences) about what you learned today and any challenges you encountered. Share this in the discussion forum.

## Additional Resources  - u04
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
- [Set up Git on macOS](https://www.atlassian.com/git/tutorials/install-git#mac-os-x)  
- [Basic Terminal Commands for macOS](https://www.macworld.com/article/671468/how-to-use-the-terminal-on-mac.html)

## Day 4: Know more about Docker and SHELL

**Task 1: Get used to Docker**
- **Instructions**
1. [Docker 101](https://youtu.be/eGz9DS-aIeY?si=KYJRg5YzS0JVQKpW)
2. [More of Docker](https://youtu.be/RqTEHSBrYFw?si=CSK5VMEb79hTFRzq)
3. Prepare a 3 minutes talk about Docker and how it will us in this project for next friday

**Task 2: Install GATK using Docker**
- **Instructions**
1. [Use this link to download GATK using Docker](https://hub.docker.com/r/broadinstitute/gatk/)
2. [More of GATK documentation](https://github.com/broadinstitute/gatk)
3. Verify the download and tell us about any tricky problems you faced on the discussion panel

**Task 3: Know more about shell**
- **Instructions**
1. [The Shell playlist](https://youtube.com/playlist?list=PLA86D04D6E0BFD2E0&si=bLIDog2l41W0w0Zv)


- **Reflection:** Write a short reflection (2-3 sentences) about what you learned today and any challenges you encountered. Share this in the discussion forum.

## Day 5: File formats
- **Instructions**
#### - Here are some YT videos that will help you understand the file formats we are going to work with 
1. [FASTA & FASTQ](https://youtu.be/xYEre9DtIqA?si=MsgBaiiCILqNry5-)
2. [VCF & gVCF](https://youtu.be/cBDZSGf9HRE?si=Oi5WkQCZrxhDuw40)
3. [SAM/BAM](https://youtu.be/vh6l9aPFUgU?si=F_T-ltv6TPh00Lc9)
4. [GFF3 & GTF](https://youtu.be/vh6l9aPFUgU?si=F_T-ltv6TPh00Lc9)


- **Reflection:** Post some interesting facts about the file formats that you learned today on the discussion panel

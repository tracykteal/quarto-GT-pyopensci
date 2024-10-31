# Quarto and Great Tables workshop

Materials for pyOpenSci Fall Festival workshop

## Info

🗓️ Date:November 1, 2024  
🕗 Time: 08:00 - 1:00 US/Pacific  
🏨 Location: online

## Abstract

If you want to use data to make decisions, answer scientific questions, inform people on issues or participate in data-driven journalism, just conducting the data analysis is not enough. Effective communication requires weaving together narrative text and code to produce elegantly formatted output that people can easily read and understand. In this workshop, you’ll learn how to use Quarto for reports and presentations and Great Tables for elegantly formatted tables to convey information that’s great for the readers, and easy for you to create too. Quarto is an open source tool based on Pandoc that allows you to create and publish reproducible, production-quality articles, presentations, dashboards, websites, blogs, and books in HTML, PDF, MS Word, ePub, and more, right from your Jupyter notebooks.

With Great Tables you can make wonderful-looking tables in Python. Great Tables is an open source Python package that lets you mix and match things like a header and footer, attach a stub (which contains row labels), arrange spanner labels over top of the column labels, and much more. Not only that, but you can format the cell values in a variety of awesome ways.

See [https://tracykteal.github.io/quarto-GT-pyopensci/](https://tracykteal.github.io/quarto-GT-pyopensci/) for more info and workshop materials.
The materials for the Quarto component of this workshop are a fork from Mine Çetinkaya-Rundel's [Quarto SciPy 2024 workshop](https://bit.ly/quarto-scipy24)

## Instructors

Rich Iannone is a software engineer that focuses on writing software packages focused on data analysis and data visualization workflows. Through this, he really wants to help people accomplish things that were difficult before. He’s been at Posit Software for six years. During that time, among other projects, he has especially enjoyed working to make tables beautiful as a primary developer on gt for R and Great Tables for Python. Before that, he did many science-y things before switching into full-time open source development. 

Tracy Teal is passionate about open source data science tools, and open source sustainability, developing and supporting leaders and teams in science and technology. Currently the open source program director at Nixtla, she has been an open source program director, an executive director of non-profits in the data science and research space, and a researcher, educator and open source developer in bioinformatics. She is a tab-complete advocate, and believes in the power of accessible tools, available resources and inclusive training to bring people to data so they can answer the questions that are important to them. 

## Schedule

| Time (MDT)    | Topic |
| -------- | ------- |
| 8:00am  | Welcome    |
| 8:15am | What is Quarto? |
| 8:45am    | Quarto documents |
| 9:15am    | VSCode and Quarto |
| 9:30am    | Break |
| 9:45am    | Great Tables |
| 12:00am   | Break |
| 12:15pm   | Wrap up | 

## Setup

We'll be using VSCode in this workshop and working on [Codespaces](https://github.com/features/codespaces). 

### Log in to Codespaces 
* Log in to [Codespaces](https://github.com/features/codespaces)
* Start with a Blank template

### Install the Quarto CLI
* Install the Quarto CLI. ([Quarto instructions for Linux installation](https://quarto.org/docs/download/tarball.html) which we need to do on Codespaces. If you're working locally you can download the CLI and install it.)

At the terminal type:  
`wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.5.57/quarto-1.5.57-linux-amd64.tar.gz`  
`mkdir ~/opt`  
`tar -C ~/opt -xvzf quarto-1.5.57-linux-amd64.tar.gz`  
`ln -s ~/opt/quarto-1.5.57/bin/quarto ~/.local/bin/quarto`  
`quarto -v` 

### Install some VSCode extensions
* Search for the Quarto extension and install that extension
* Search for the Preview extension and install that extension


# mcxs-report-template

This is a template repository for the Research Report for **Macroeconometrics**. You can use it to generate a website with your report such as the one at <https://donotdespair.github.io/mcxs-report-template/>

## Using the template

In order to use this template:

1.  login to your [GitHub](https://github.com/login) account.
2.  Search for `mcxs-report-template` and click the **Use this template** button.
3.  Give a name to your repository and make it public.
4.  Clone the repo to your computer using [GitHub Desktop](https://desktop.github.com/).
5.  Go to **RStudio** and click **File -\> New Project... -\> Existing Folder** and select the folder to which you cloned the repository. It's much easier if you consistently keep working on your report using this R project.
6.  Start working on your project. Good luck!

Once you have your own repository created from this template, follow the steps to create your website:

1.  Go to the **GitHub** page of your repository.
2.  Go to **Setup -\> Pages**.
3.  Set **Source** to *Deploy from a branch*
4.  Set the **Branch** to *master*, and then the folder to `/docs`.
5.  Click **Save**, reload the page and get the link to your website. YAY!

## The structure of the template repository

The repository contains several folders and files. Here's what they are for:

Folder `docs/` contains the rendered website. Do not ever adjust its contents. It's automatically generated.

File `.gitignore` includes a list of files that you might have in your local folder, but do not want them to be submitted to the public repository.

File `README.md` is the one you are reading right now. Feel free to edit this file having created your own repository from this template.

File `_quarto.yml` contains all the settings of the **quarto** project. Do not modify the existing setup unless you are sure of the consequences to the developed website. Feel free to add more detailed setup when you learn more about **quarto** over the semester.

File `index.qmd` is the quarto file in which you should develop your report. Please do not change its name or location. Otherwise modify as you will.

File `references.bib` contains **LaTeX** references to be used in the **quarto** document. Have a look at the recommendation of how to use it under the link provided in the template website. It is recommended to not change this file's name or location as they are set to the default values which make working in **RStudio** simple.

File **styles.css** contains the **CSS** style that determines the visual aspects of your website. You may modify or replace it, but please first read about it. You may also leave it as is and that's perfectly fine.

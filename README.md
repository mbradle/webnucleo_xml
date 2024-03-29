# webnucleo_xml

This project contains code to create and manipulate XML files for
[Webnucleo](https://webnucleo.readthedocs.io) projects.

## Jupyter notebooks

The following Jupyter notebooks let you create and/or manipulate Webnucleo XML.

You can run the notebooks on [Google Colaboratory](https://colab.research.google.com) by clicking on the Open in Colab badge at the end of the paragraph for each notebook.  You will need to sign in with your Google account.  If you receive a warning about the authorship of the notebook, you may ignore it by clicking on Run anyway.  Execute the whole notebook by clicking on Run all from the Runtime menu.  You can then change inputs or code in the notebook, as desired.

It is also possible to run the notebooks on [Binder](https://mybinder.org).  To do so, click on the launch binder badge at the end of this paragraph.  It will take a few minutes to build the appropriate environment, but once done, you can click on any of the notebooks to launch it.  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mbradle/webnucleo_xml/main)

Of course you can also run the notebooks on your local computer.  To do so, once you have installed [the Jupyter Notebook](https://jupyter.org), download the linked notebook above (right-click or control-click).  To run the notebook from the command line, type, for example,

**jupyter notebook create_nuclide_xml.ipynb**

Be sure to remove any suffix that is not *.ipynb* on the notebook file you download.  For example, some browsers will by default add a *.txt* to the downloaded file so that it has suffix *.ipynb.txt*.  Remove the *.txt* before running.

### Notebooks:

- **apply_xpath.ipynb:** Create a new Webnucleo XML file by applying XPath expressions to an old Webnucleo XML file.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbradle/webnucleo_xml/blob/main/apply_xpath.ipynb)

- **create_nuclide_xml.ipynb:** Create webnucleo nuclide XML data from user-supplied input.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbradle/webnucleo_xml/blob/main/create_nuclide_xml.ipynb)

- **create_reaction_xml.ipynb:** Create webnucleo reaction XML data from user-supplied input.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbradle/webnucleo_xml/blob/main/create_reaction_xml.ipynb)

- **create_zone_xml.ipynb:** Create webnucleo zone XML data from user-supplied input.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbradle/webnucleo_xml/blob/main/create_zone_xml.ipynb)

- **remove_species.ipynb:** Remove all instances of a species from a webnucleo XML file.  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mbradle/webnucleo_xml/blob/main/remove_species.ipynb)


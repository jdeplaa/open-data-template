# Creating a reproduction package

So, you are ready to submit your paper. Congratulations! Now, it is also a good time to think about a 
reproduction package. The checklist below guides you through the process.

## Create your package in (less than) 10 steps

1. **Create a separate directory for your reproduction package.** You can either clone/fork/download 
the template provided by this project or create a directory structure yourself. For example:
    ```
    linux:/data/user> git clone https://github.com/jdeplaa/open-data-template.git
    ```
2. **If you performed your analysis in Jupyter Notebooks, you can include the relevant files in the
``notebooks`` directory.** Please also include a short README file explaining how you need to run the
Jupyter notebooks and which part of the analysis can be found in which notebook. If your notebooks 
are complete, you can skip step 3 and 4. 

3. **For each figure in your paper, copy the files/scripts that you used to create the figure to the
``figures`` directory.** If you reserve one directory per figure, the relevant files are easier to find.
In each figure directory, add a short README file or log to explain how to generate the figure using the files.

4. **For each of your scientific results in the paper, copy the data end products and scripts to the 
``data`` directory.**  Data end products can be spectra, images, tables, etc. If possible, also provide 
the scripts/software how you derived the scientific results from these end products (e.g. the fitting process).
In the data directory, add a short README file or log how to derive the results using the scripts and 
data files.

5. **Write a README.md file in the top level of the reproduction package.** This will be the cover page for 
your package on Zenodo. In the file, list the software packages that you used and explain what can be found 
where in the package. The template README.md can guide you through this process.
 
6. **Show your package to a colleague/supervisor.** This is to check whether your package is clear enough 
for publication. Also check whether you did not include security sensitive data (usernames, passwords, 
computer names, etc.).

7. **Tar or Zip the figures/data/notebooks directories.** Do not include the ``README.md`` file in the top 
directory in the tar/zip package! The ``README.md`` needs to be outside the tar/zip package for Zenodo to 
display a preview of it.

8. **Do a test upload of your package to the [Zenodo sandbox](https://sandbox.zenodo.org/).** You can use 
your [ORCID](https://orcid.org/) to login. Show the result to a colleague/supervisor to check. This upload
will be removed after a couple of days.

9. **If all the checks are OK, upload your package to the real [Zenodo](https://zenodo.org).**
You can use your [ORCID](https://orcid.org/) to login. Do not forget to add the SRON community to your upload.
Be sure to let Zenodo create a DOI for you and do NOT use the DOI of the paper ([What is a DOI](https://en.wikipedia.org/wiki/Digital_object_identifier)).  

10. **Make clear in your paper that the data are available online.** Some journals require you to add a [data access statement](https://library.bath.ac.uk/research-data/archiving-and-sharing/data-access-statements#:~:text=Data%20access%20statements%2C%20also%20known,conditions%20they%20can%20be%20accessed.)
to your paper and the link provides examples how to do that. If your journal does not require it, it is 
anyway a good idea to show in your publication where they can find the reproduction package.
 
Congratulations! You are done! :)

## Useful links

- [Introduction to MarkDown (formatting language of this file)](https://guides.github.com/features/mastering-markdown/)
- [More help creating repro packages](https://personal.sron.nl/~jellep/openscience/).
- [An example reproduction package](https://doi.org/10.5281/zenodo.3543610).
- [Zenodo sandbox](https://sandbox.zenodo.org/).


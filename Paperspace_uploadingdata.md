# Uploading data to Paperspace

The simplest way to upload datasets (or code) from your local computer to Paperspace is using a Gradient Jupyter Notebook. 

Persistent Storage

Anything you store in `/storage` directory will be accessible across multiple runs of Jobs and Notebooks in a given storage region.

(1) After logging into Paperspace, toggle your mouse to the Gradient section (in the left hand column of the Paperspace consule) to see the drop down menu of Gradient options. Select Notebooks (second option) to access the control console for jupyter notebooks. 

(2) Next you need to create a notebook. This is done by selecting the bright seafoam green button in the middle of the right hand side of the Notebook console. You will be prompted to select a container (which sets up the operating system/environment in which to run the notebook). For uploading data you don't need anything in particular, so select the first option, titled fast.ai. You then need to scroll down the page and select the type of machine/computer you would like to run your notebook on. It is recommended to select P4000 or P5000 (the second or third option in the first row). Scroll down again to the section Notebook options. It is highly recommended to set a time limit upon your notebook; if you forget to stop the notebook, you will get charged for it! Scroll to the very bottom of the page, and select the dark teal +Create Notebook button.
This action creates a separate web page that is running the notebook instance.

(3) Toggle to the separate web page where your notebook is running. Under the files tab, you can view the file system of you Paperspace server. These of the files that all of your projects/jobs can access

There are also multiple datasets that are publicly available in Paperspace. They are located in the `/datasets` folder, and can be accessed in any project. A list of these datasets (and a brief description of them) is found 
[here]: https://docs.paperspace.com/gradient/data/public-datasets-repository
# Environment Setup

**Note**: In order to run the code in these notebooks, you need to use a runtime backend with a large amount of RAM. 
- In google colab, these are the A100 GPU, L4 GPU, and the TPU v2. 
- In the free version of google colab, you should be able to access a TPU v2. 
- On the colab notebook, click Runtime in the top menu bar and select change Runtime Type.
- Then, select TPU v2.
- If you are unable to use these in the free version, you need to upgrade colab to a paid tier, and then run using those compute units.
- Link to google colab paid tier: https://colab.research.google.com/signup/pricing

## Steps
### Setup CS_598_Proj folder
 1) In your Google Drive, "My Drive" folder, check if you have a "Colab Notebooks" folder.
 2) If not, create a folder named "Colab Notebooks"
 3) Then, create a shortcut to the CS_598_Proj folder in your "Colab Notebooks" folder on Google Drive
 4) Right-click on the CS_598_Proj folder in you drive and click "Organize" from the drop-down menu, then click "Add Shortcut"
 5) Add the CS_598_Proj folder to your root "Colab Notebooks" folder
 6) Once you open the Colab Notebook, after running the Mount command, make sure you allow access tothe Google Drive for Desktop when the pop-up comes up, otherwise the drive will not mount, and you will get errors
    
### Setup DataFolder and run final notebook
 1) Before running the main notebook, make sure the data folder is mounted to your google druve
 2) To mount the data to your google drive folder, open the link: https://drive.google.com/drive/folders/1aNS4aKUYo7HiJCyOTdjNxhxOlPP-WbDB?usp=drive_link in your google drive
 3) It will appear in "Shared with me"
 4) Right-click and select "Organize" -> "Add Shortcut"
 5) Add the folder to your "My Drive" folder
 6) To access the main notebook, go to: https://colab.research.google.com/drive/1551qz_-RaXk9tXLSNWeb0LAbIuFDmk2_?usp=sharing and then run the notebook

### Run Training Notebook
 1) Ensure you follow the above steps to setup the data folder on your google drive
 2) Go to https://colab.research.google.com/drive/1uAEvpmUV9L8iUmS0NO5OhQRm6gh3ObjF?usp=sharing and run the notebook
    
### Setup Plotting and Metrics Folder
 1) Copy the https://drive.google.com/drive/folders/1OtzZoxa24jiOQ_xCvGQ1AIyYVLwHW8zs?usp=sharing to the plots and metrics folder
 2) It will appear in "Shared with me"
 3) Right-click and select "Organize" -> "Add Shortcut"
 4) Add the folder to your "My Drive" folder
 5) Go to https://colab.research.google.com/drive/1_KabQX9RbDNArACSyeren3J6WRgWp0LW?usp=sharing and run the plotting notebook


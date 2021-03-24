# Downloading Anaconda

Anaconda Individual Edition can be downloaded as a Linux 64 Bit .sh

[Anaconda](https://www.anaconda.com/products/individual)

The .sh can be installed on most Linux distros such as Ubuntu, Mint, POPOS!, Fedora and DeepIn Linux. 

# Anaconda Installation

In this example I will use Fedora 34.

![001_download](001_download.png)

Wait for the Download to complete:

![002_download_complete](002_download_complete.png)

Then go to the Downloads folder:

![003_downloads_folder](003_downloads_folder.png)

Write click some black space with the folder and select Open in Terminal:

![004_open_in_terminal](004_open_in_terminal.png)

Right click the .sh file and select copy the file name including the extension.

![005_downloads_folder_copy](005_downloads_folder_copy.png)

Type in the following:

```bash```

Then paste in the file name. 

![006_bash_install](006_bash_install.png)

For example:

```bash Anaconda3-2020.11-Linux-x86_64.sh```

![007_bash_install2](007_bash_install2.png)

Hold down 

```↩``` 

to scroll quickly through the License Agreement:

![008_bash_install_license_agreement](008_bash_install_license_agreement.png)

![009_bash_install_license_agreement_end](009_bash_install_license_agreement_end.png)

Type in:

```yes```

to accept the License Agreement.

![010_license_agreement_accept](010_license_agreement_accept.png)

Type 

```↩``` 

to install in the default directory:

![011_install](011_install.png)

You will asked if you want to initialize Anaconda. You will need to do this to launch Anaconda from the terminal.

![012_conda_init](012_conda_init.png)

Type in 

```yes```

![013_conda_init](013_conda_init.png)

You will be informed Anaconda is now installed. Close the Terminal.

![014_anaconda_installed](014_anaconda_installed.png)

# Updating Anaconda and JupyterLab

Open up a new Terminal.

![015_terminal](015_terminal.png)

To update the Anaconda installation type in the following command:

```conda update anaconda```

![016_update_anaconda](016_update_anaconda.png)

Details about the latest versions available will be listed. Type in

```y``` 

to update to the latest versions.

![017_update_anaconda](017_update_anaconda.png)

A new prompt will display when updated.

![018_update_anaconda2](018_update_anaconda2.png)

The latest version of JupyterLab is available on conda forge. To update type in the following command:

```conda install -c conda-forge jupyterlab=3``` 

![019_update_jupyterlab](019_update_jupyterlab.png)

Once again type in 

```y```

to update to the latest version.

![020_update_jupyterlab](020_update_jupyterlab.png)

It is recommended to periodically look for updates to Anaconda and JupyterLab using the commands above.

Once updated a new prompt will display.

![021_updated](021_updated.png)

# Launching JupyterLab

Unlike on Windows no shortcuts for Anaconda are displayed on the Start Menu. The Anaconda Navigator can be launched from the terminal by typing in:

```anaconda-navigator```

![022_launching_anaconda_navigator](022_launching_anaconda_navigator.png)

The Anaconda navigator shows a number of tiles corresponding to Python IDEs. JupyterLab can be launched:

![023_JupyterLab_launch](023_JupyterLab_launch.png)

![024_jupyterlab](024_jupyterlab.png)

Alternatively JupyterLab can be launched directly from the terminal using:

```jupyter lab```

![025_jupyterlab](025_jupyterlab.png)

To the left hand side is the file explorer. A new launcher can be selected by pressing the ```+``` at the top left. From the new launcher (right hand side) a new Text File, Markdown File or Notebook can be selected.

# Getting Started with JupyterLab

For details about the Markdown file see:

[Markdown File Basics](https://github.com/PhilipYip1988/0-markdown-files/blob/main/markdown.md)

To get started with Python programming see:

[Getting Started with Python Programming](https://nbviewer.jupyter.org/github/PhilipYip1988/1-object-orientated-programming/blob/main/objectorientatedprogramming.ipynb)
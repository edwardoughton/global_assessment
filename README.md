# Global Assessment

Welcome to this introductory course on `Global Assessment`!

What is `Global Assessment`? This term is defined as the ability to undertake high-resolution computation of spatial processes at the planetary scale.

Imagine the power of being able to analyze data as granular as 1 square kilometer, but for the whole globe! This is the purpose of this set of learning materials.

Three main learning outcomes are identified:

-   Firstly, developing global geospatial data analytics in Python to support decisions in industry and government.
-   Secondly, gaining a proficient ability to work with high-resolution local data (e.g., 1 km^2) but at the global scale.
-   Finally, running basic parallel computing scripts, both on a single machine and on a High-Performance Computing (HPC) cluster.

The tools used focus on Python with affiliated packages such as Rasterio, GeoPandas, Matplotlib etc.


## Getting started

These tutorials utilize the open-source `Anaconda` distribution which is a common approach for scientific computing. You will need to download and install `Anaconda`, which not only provides a package manager for Python, but also various virtual environment functions.

Once installed, it would be handy to open the anaconda prompt on Windows, or the terminal on Mac. And then navigate to a suitable location to clone this repo to, e.g. your desktop or documents folder, wherever you prefer. You can clone the repo by using:

    git clone https://github.com/edwardoughton/global_assessment

Then you can navigate into the folder using the 'change directory' command (`cd`):

    cd global_assessment

You can then install the existing 'global_assessment' virtual conda environment (`ga`) provided
using the `ga.yml` file. The YAML file (which now stands for 'YAML Ain't Markup Language') details
all the packages and versions which exist in an environment we want to install. You can install
the environment as follows:

    conda env create -f ga.yml

Now you can activate the environment using `conda activate` comment:

    conda activate ga

In case you ever need to delete and reinstall a conda virtual environment, you can use the
`conda remove` functionality. For example, to remove the `ga` environment we installed, you can
do the following:

    conda remove --name ga --all

And to verfiy the environment was removed, you can look at your existing conda virtual
environments as follows:

    conda info --envs

You should now be ready to begin with the main packages required to engage with these resources.

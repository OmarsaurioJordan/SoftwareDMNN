# SoftwareDMNN

Tool to train the Dendral Morphological Neural Network by Stochastic Gradient Descent, Diferential Evolution or Particle Swarm Optimization, initializing it with K-means or Divide & Conquer.

Note: this was made in 2019, and because I am not a software engineer, I am an electronic engineer, at that time I dont knowed some things about software develop, so... for example, the code was putted in one file!!! crazy that men :S

## Installation

You should run the **SoftwareDMNN.py** file, it require the dependencies:

- sys, os, io, time
- PyQt5
- numpy
- xml.etree.ElementTree
- playsound

If you wanna create an **SoftwareDMNN.exe** file, you should use pyinstaller:

```bash
pip install pyinstaller
cd folder_path_with_all_the_files
chain_with_the_commands
```

The project contains a **compilar.txt file**, it has the chain with the commands, but if you realize some changes in the code, the
**SoftwareDMNN.py** has a description of the commands to compile, and a function to create the text chain.

You can use a **SoftwareDMNN.exe** here: https://omwekiatl.itch.io/softwaredmnn

## Usage

Read the **TutorialDMNN.pdf**, is the user guide, but the software should be intuitive, it has a good GUI.

Here you can **import a dataset of patterns for classification** (like the classic iris.txt), you can select the distribution bethween train, validation and test, you can normalize all and next... **create a DMNN** to solve the problem, this software was made with the purpose of compare the 3 train algorithms (**SGD, DE, PSO**) and the 2 initialization algorithms (**Kmeans, D&C**), but it is finally a **suit of solving classification problems**, testing it with **confussion matrix**, and giving a Python function than can be used in other projects, togheter to export of net method.

## Support & Author

I am Omar Jordan Jordan, my developer name is Omwekiatl (last time Omarsaurio), I create videogames and educational software most time.

mail: [ojorcio@gmail.com]

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

The **SoftwareDMNN.py** file contains at the end, a list of work to make, but now I work in other things...

# Secure and Private AI

This course introduced me to three cutting-edge technologies for privacy-preserving AI: Federated Learning, Differential Privacy, and Encrypted Computation. I learned how to use the newest privacy-preserving technologies, such as OpenMined's PySyft. PySyft extends Deep Learning tools—such as PyTorch—with the cryptographic and distributed technologies necessary to safely and securely train AI models on distributed private data.

## Dependencies

To run these notebooks you'll need to install Python 3.6+, PySyft, Numpy, PyTorch 1.0, and Jupyter Notebooks. The easiest way to install the required libraries is with Conda. Create a new environment, then install the dependencies in that environment. In your terminal:

```bash
conda create -n pysyft python=3
conda activate pysyft # some older version of conda require "source activate pysyft" instead.
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch # depends
pip install pysyft
```

If you have any errors relating to zstd - run the following (if everything above installed fine then skip this step):

```pip install --upgrade --force-reinstall zstd```

and then retry installing syft (pip install syft). If this still doesn't work, and you happen to be on OSX, make sure you have OSX command line tools installed and try again.

If you are using Windows, I suggest installing Anaconda and using the Anaconda Prompt to work from the command line.

With this environment activated and in the repo directory, launch Jupyter Notebook:

```jupyter notebook```

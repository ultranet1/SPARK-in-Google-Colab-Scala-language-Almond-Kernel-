# SPARK-in-Scala-and-Google-Colab


Scala Installer for Colaboratory
This notebook installs Almond, a Scala kernel for Jupyter, into Colaboratory and configures it to make the preinstalled Python libraries accessible to Scala code (through ScalaPy).

Because this installer is built on Almond, you get complete Scala support inside your notebooks, including the ability to get code completions and access to the Jupyter-specific APIs. In addition, this installer configures Almond to be able to load preinstalled modules in Colab such as numpy and tensorflow through ScalaPy.

If coming to this notebook from GitHub, make sure to not reset your runtime when running this notebook. In order to install the Scala kernel, the installer writes data to the runtime filesystem, so resetting would clear out the kernel.

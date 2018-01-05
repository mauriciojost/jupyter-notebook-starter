# README

```
export SPARK_HOME=$HOME/opt/spark
export PATH=$SPARK_HOME/bin:$PATH
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/
```


To install `jupyter-notebook`:

```
sudo apt-get install jupyter-notebook
```

To generate a password

From `ipython`:

```
from IPython.lib import passwd
password = passwd("secret")
password
```

Put it in the configuration `jupyter_notebook_config.py`.

```
jupyter-notebook --config jupyter_notebook_config.py --notebook-dir notebooks --port 7777 --ip martinenhome.com
```


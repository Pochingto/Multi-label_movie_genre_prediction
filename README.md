The notebook is run under the google colab environment.
I have also used the "zip file" and "unzip" in the colab environment which can be deleted if you are not running in google colab and have the dataset locally.

If you want to run the notebook, there are 3 things to take care:
1. run in order (from top to bottom)
2. I have set up a gpu-environment, so if cuda:0 is unavailable, please change the device type
3. specify your own file path for data (e.g. images folder, train.csv)
# thunderboard-reader
Read data over USB from the Silicon Labs Thunderboard Sense2 for plotting and saving to CSV


## Installation instructions
Install Python3 [Python downloads](https://www.python.org/downloads/)

Next we will use pip to install the Thunderboard package

In a terminal or Windows CMD prompt type:

```
pip install thunderboard-reader 

```

Alternatively if `pip` is not found as a command:
```
python3 -m pip install thunderboard-reader 

```

Now, connect the Thunderboard to your computer via USB. Next, launch the mobile phone app and startup the environment sensing data. Then within the same terminal / command prompt try these commands. 

```
tboard_read.py --help

tboard_read.py --sensor Temp

tboard_read.py --sensor all

tboard_read.py --sensor eCO2 --time 5
```
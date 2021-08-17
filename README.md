# Cleaning-temperature-data-log-file-using-R

The process of joining materials is known as additive manufacturing (AM) that makes objects from 3D model data, commonly in a layer by layer process. One such machine is called BAAM (Big Area Additive Manufacturing). The goal with BAAM is to 3D print large, near-net-shape parts as quickly as possible. Parts are typically post-processed to the final dimension by machining.

There are multiple temperature sensors installed in the machine which records temperature during the print. Once the machine completes the print, a log is generated that contains the time and the temperature recorded at that particular time by different sensors. The log generated is very messy, and it's hard to see how the temperature varies with time.

So, to solve that issue, I have written the function which cleans the data and provides the data in a tabular form. The function also plots the sensor data with respect to time.

The name of the sensors are:

- Tip 1
- Tip 2
- Inlet
- Barrel 1
- Barrel 2
- Barrel 3
- Barrel 4

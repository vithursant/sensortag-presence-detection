# sensortag-presence-detection

## Setup

```bash
# install bluepy
sudo apt-get install git build-essential
git clone https://github.com/IanHarvey/bluepy.git
cd bluepy
python setup.py build
sudo python setup.py install
```

## Run Script
```bash
sudo python sensortag-presence-detection.py
```

### Optional Command-Line Args
* -t {DURATION TIME} :  SensorTag scan timeout duration (seconds).
* -s {SLEEP TIME} : Sleep time (seconds) between scanning for devices.


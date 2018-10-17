# FreedarUK Setup Script :airplane:

These scripts aid in setting up your current ADS-B receiver to feed ADS-B Exchange.

### Obtaining And Using The Scripts

Running the following commands will download the contents of this repository and begin setup.

    sudo apt-get install git
    git clone https://github.com/WiganPI/FreedarUK.git
    cd adsb-exchange
    chmod +x freedarsetup.sh
    sudo ./freedarsetup.sh
    
**After completing the setup do not delete this repository.**

The script creates two files, one named freedaruk_maint.sh and another named freedaruk-netcat_maint.sh which will reside in this folder containing a clone of this repository. The path to execute these scripts after each reboot has been set to this location. Deleting this folder will result in both the freedaruk-mlat_maint.sh and freedaruk-netcat_maint.sh scripts to not be executed thus not enabling your receiver to feed FreedarUK after your device has been rebooted.

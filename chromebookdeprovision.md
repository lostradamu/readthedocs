### Requirements

* GAM
* List of Chromebook serial numbers in CSV format (one column with one header, "Serial")

### Deprovisioning Chromebooks using a CSV file

`gam csv CrosSerials.csv gam update cros query:id:~~serialNumber~~ action deprovision_same_model_replace acknowledge_device_touch_requirement`

# telegraf

## Generate sample configs
* `telegraf -sample-config -input-filter cpu:kernel:mem:processes:swap:system:docker -output-filter influxdb > telegraf.conf`


## Run
* `telegraf --config telegraf.conf`

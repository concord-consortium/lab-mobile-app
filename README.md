Lab Mobile App

================

To run the phonegap-benchmark app on iOS or Android, first you must have the respective SDK installed. Additionally, your devices must be configured and registered for development.

If you have a development-ready device and machine, follow these steps to run the phonegap-benchmark app:

1. [Install lab](https://github.com/concord-consortium/lab) and get it running. Note down the IP address of the machine running lab. For example, lab may be running on 192.168.1.1:9292/index.html
2. Install Phonegap from [here](http://phonegap.com/install/).
3. Clone this repo.
4. In the phonegap-benchmark/www folder, there is a file called index.sample.html. Copy and rename it to index.html.
5. On line 46, change the IP address to the IP address noted in Step 1.
6. Now, cd to the phonegap-benchmark folder. Run the command "phonegap run ios" or "phonegap run android" to create build for respective platforms.
7. cd to the phonegap-benchmark/platoforms folder. Here you'll find the projects for iOS and Android. Open the appropriate one and run it on your device.

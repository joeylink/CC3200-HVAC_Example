**CC3200 HVAC Demo**

**Software Setup**

 1. Install [Energia](http://energia.nu/download/)

 2. Navigate to http://energia.nu/guide/  select your operating system, then select CC3200 Launchpad, follow instructions listed (with device disconnected, download CC3200 LaunchPad CDC drivers zip files), then reboot computer
 
 3. Add CC3200 in Boards Manager 
     * Tools --> Board--> Boards Manager
     * Search for "CC3200"
     * Select it and click on "Install" button

4. Add the [Exosite Library](https://github.com/exosite-garage/arduino_exosite_library#installing)
    a.  

5. Open the HVAC Demo
    * File --> Examples --> Exosite --> CC3200HVACDemo
6. Open the Serial Monitor and run the HVAC Demo. Your MAC address will be printed at startup

**Murano Setup**
1. Create a new product in Murano
2. copy and paste the following URL into the Link to your product template field:

 `https://raw.githubusercontent.com/exosite-garage/arduino_exosite_library/master/examples/Murano-SmartLightBulb-ThingDevBoard/product_spec_smart_lightbulb_example.yaml`

 This will allow you to use a template spec file to automatically set up the product definition.
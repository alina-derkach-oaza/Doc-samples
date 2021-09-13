# PortaOne iPaaS 
PortaOne iPaaS (Integration Platform as a Service) is a new provisioning solution available in MR80-3 and starting with MR83-0. It enables you to deploy new functionalities (e.g., provision new CPE profiles) through containers that run in the cloud. This eliminates the need to update all of PortaSwitch® to the newest release. Thus, you reduce the time to market for new services.

A container is a portable software unit where all the components of new functionality (code, runtime, system tools, system libraries and settings) are stored as one package. Containers are deployed in the cloud-based PortaOne iPaaS independently from the PortaSwitch® installation. As a result, they are easily modified and extended.

To start using new features via the PortaOne iPaaS, subscribe to it. To find out about our subscription terms, contact our Sales department.

#### CPE provisioning via PortaOne iPaaS

The first functionality that’s available via PortaOne iPaaS is CPE provisioning for Yealink W80B – an IP multi-cell base station.

Refer to the **Auto-provisioning for Yealink W80B DECT IP multi-cell base station** section to read about auto-provisioning for Yealink W80B.

This is how CPE provisioning via PortaOne iPaaS works: 

Let’s say the service provider, Easy Call, wants to provision Yealink W80B to their customers. Since this device model is available via PortaOne iPaaS, Easy Call subscribes to the CPE provisioning service and enables it on their installation. So an administrator can configure the provisioning of Yealink W80B in PortaBilling® in just a matter of minutes now. 

When an administrator creates a CPE profile for Yealink W80B, PortaBilling® queries the CPE provisioning container via the API to generate a CPE profile. The CPE provisioning container returns the generated CPE profile and it is stored in the PortaBilling® database along with the internal CPE profiles. 

Then the administrator creates the Yealink W80B CPE device and assigns it to an account. PortaBilling® generates a configuration file with the CPE device parameters (username, password, device’s MAC address, etc.) and sends it to the CPE provisioning container. This configuration file is used in the CPE provisioning container to adjust Yealink W80B’s internal configuration.

Now Yealink W80B is ready to use by end users. 

##### Benefits
Service provisioning via PortaOne iPaaS: 
* Significantly saves your time and resources since you do not need to update your installation to receive a new functionality.
* Reduces time to market for new functionalities, thus makes you more competitive.
* Improves the customer experience. You can provide your customers with the newest devices and functionalities in the short term.

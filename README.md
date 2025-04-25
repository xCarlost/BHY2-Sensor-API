# BHY2-Sensor-API
## Sensor-API Overview

This repository uses the combined Sensor-API (BHY2), which supports devices such as BHI260AP, BHI360, and BHI380. While Bosch Sensortec has restructured their Sensor-API into dedicated repositories, this project retains the unified approach for broader compatibility and ease of use.

For reference, the dedicated repositories are:

- [BHI2xy SensorAPI](https://github.com/boschsensortec/BHI2xy_SensorAPI.git)
- [BHI360 SensorAPI](https://github.com/boschsensortec/BHI360_SensorAPI.git)
- BHI380 SensorAPI: (No dedicated repository yet)

**Note:** If your development environment supports modern C++ standards, you may consider using the dedicated Sensor APIs for the latest updates. However, this combined approach ensures compatibility with a wider range of toolchains, including older environments like PlatformIO with the Espressif32 framework.

> **Disclaimer:**  
> This code is part of a forked repository and is not maintained by Bosch.  
> The author of this fork is not responsible for any damages, data loss, or other issues that may arise from the use of this code.  
> Use this code at your own risk and ensure proper testing and validation before deploying it in any production environment.

----

### BHI260AB/BHA260AB/BHI260AP/BHI360/BHI380 SensorAPI (old readme)

This package contains BHI260AB/BHA260AB/BHI260AP/BHI360/BHI380 generically clustered as BHy2 SensorAPI.

This package can be used together with [COINES](https://www.bosch-sensortec.com/software-tools/tools/coines/) to modify, compile, and run the sample applications.

#### Product Links

- [BHA260AB](https://www.bosch-sensortec.com/products/smart-sensors/bha260ab.html)
- [BHI260AB](https://www.bosch-sensortec.com/products/smart-sensors/bhi260ab.html)
- [BHI260AP](https://www.bosch-sensortec.com/products/smart-sensors/bhi260ap/)
- [BHI360](https://www.bosch-sensortec.com/products/smart-sensor-systems/bhi360/)
- [BHI380](https://www.bosch-sensortec.com/products/smart-sensor-systems/bhi380/)

> If you are interested in the BHI380 smart sensor, please use our [contact form](https://www.bosch-sensortec.com/products/smart-sensor-systems/bhi380/#contact).

> *Please be aware that the BHI380 is currently only available to a limited number of projects. Therefore, we are only considering information requests for projects with a minimum lifetime quantity of 1,00,000 units and above.*

---

#### Copyright (C) 2023 Bosch Sensortec GmbH. All rights reserved.

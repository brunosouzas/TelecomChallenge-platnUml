# Solution recommendation for modernize customer onboarding

## Purpose
This document describes API recommendations for improve customer onboarding project and the functional and nonfunctional requirements/designs for each API identified.

## Solution Overview
This Solution will initially serve 2 projects to improve the management of customer data and the integration of customers with the company. From this point on, the company will have a simple and quick way to develop new applications with customer information, billing, payment and etc ...

### The projects:
#### Customer consolidated view
@import "https://github.com/brunosouzas/TelecomChallenge-platnUml/blob/master/consolidate_system/C4_Context_Consolidate.puml"

#### Account information System
@import "https://github.com/brunosouzas/TelecomChallenge-platnUml/blob/master/account_system/C4_Context_accountInformation.puml"

## API Identification
The solution requires some APIs: 
* Experience API
  * consolidatedCustomer
  * accountInformation

* Process API
  * contract-prc
  * invoice-prc
  * bill-prc
  * usage-prc

* System API
  * customer-sys
  * bill-sys
  * invoice-sys
  * contract-sys
  * telephoneTracking-sys
  * broadbandTracking-sys
  * plan-sys

### API led
@import "https://github.com/brunosouzas/TelecomChallenge-platnUml/blob/master/api_led/apiLed.puml"

#### API led for Customer consolidated view
@import "https://github.com/brunosouzas/TelecomChallenge-platnUml/blob/master/consolidate_system/apiLed.puml"

#### API led for Account information System
@import "https://github.com/brunosouzas/TelecomChallenge-platnUml/blob/master/account_system/apiLed.puml"

## Authors
* **Bruno Souza** - *Initial work* - [brunosouzas](https://github.com/brunosouzas)

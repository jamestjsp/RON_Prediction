
## Overview
Catalytic Reformer is a refinery reactor which convert heavy naphtha to aromatic rich gasoline blend stock. The product generally called reformate and it has a quality criterion known as research octane number. Which is affected by feed type, state of catalyst, reactor pressure (which generally does not change), reactor inlet temperature, hydrogen to hydrocarbon ratio, throughput to the reactor.

## Data source
A calibrated refinery reactor model using HYSYS

## How to run online
### Read and write data
Most of the distributed control systems (DCS) has an OPC server, OpenOPC is a free python OPC client which can be used to read and write data to DCS.
### Scheduled run
The model can be run in a specified interval using a batch file scheduled in windows task scheduler.

## Future improvements
Create categorical data of feed type and generate more data after updating the HYSYS model.
Predict catalyst cocking.

# Real Wait-Time TransJakarta Dataset

This repository contains sample datasets used to support the estimation of real waiting time in TransJakarta bus rapid transit systems.

## Dataset Description

### 1. AFC Data (Automated Fare Collection)
This dataset represents passenger tap-in activity at station gates.

Fields:
- Card_ID: Passenger identifier  
- FCD_ID: Gate identifier  
- Transaction_Type: Type of transaction  
- Time: Timestamp of tap-in  
- Station_Name: Station location  

This data can be used to estimate passenger inflow and queue conditions at each station.

---

### 2. AVL Data (Automated Vehicle Location)
This dataset contains real-time bus location and arrival information.

Fields:
- OBU_ID: Identifier of the GPS device installed on the bus
- Vehicle_ID: Bus identifier  
- Line_ID: Bus route  
- Latitude, Longitude: Bus position  
- Speed_kmh: Bus speed  
- Time: Timestamp  
- Next_Station: Next stop  
- ETA_seconds: Estimated arrival time  

This data provides real-time bus movement and arrival estimation.

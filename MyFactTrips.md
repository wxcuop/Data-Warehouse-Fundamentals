| Field Name | Details |
|---|---|
| TripID | Primary key - Unique identifier for each waste collection trip |
| DateID | Foreign Key - References the DateID in the MyDimDate table |
| WasteID | Foreign Key - References the WasteID in the MyDimWaste table |
| ZoneID | Foreign Key - References the ZoneID in the MyDimZone table |
| WasteCollectedTon | Amount of waste collected in tons |

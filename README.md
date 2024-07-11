# **Capstone-Module-2**

**Capstone Project Modul 2 Data Analysis (with Jupyter and Tableau)**

- Nama: Ahmadio Rasyadi Hermanu
- Program: Job Connector Data Science and Machine Learning (Online)
- Batch: JCDSOL-013
- Case Study: New York City TLC Trip Record
- Dataset bisa di unduh [di sini](https://drive.google.com/drive/folders/1NYHIL-RgVPW-HONz4pdzlcbIChF-c37N), gunakan Dataset US
- [Tableau Story](https://public.tableau.com/app/profile/ahmadio.rasyadi.hermanu2866/viz/NYCTLCTRIPRECORD-AhmadioRasyadiHermanu/Dashboard1?publish=yes)
- YouTube Video About This Project, [di sini](https://youtu.be/AHnr7FKG3MU)

This Project Talks About The New York City Taxi and Limousine Commission (TLC) oversees the operations of the city's various taxi and for-hire vehicle services. The NYC TLC Trip Record dataset provides comprehensive information about taxi trips in New York City, capturing various details such as pickup and dropoff times, locations, passenger counts, trip distances, fare amounts, and payment methods. This dataset is instrumental for analyzing taxi operations, passenger behavior, and fare structures.

**DATA DESCRIPTION**

This Datasets containing a Trip record of Taxi in New York City, In this data there's a total of 18 columns
1. VendorID: A code indicating the LPEP provider that provided the record.
    - 1 = Creative Mobile Technologies, LLC.
    - 2 = VeriFone Inc.
2. lpep_pickup_datetime: The date and time when the meter was engaged.
3. lpep_dropoff_datetime: The date and time when the meter was disengaged.
4. Passenger_count: The number of passengers in the vehicle. This is a driver-entered value.
5. Trip_distance: The elapsed trip distance in miles reported by the taximeter.
6. PULocationID: TLC Taxi Zone in which the taximeter was engaged.
7. DOLocationID: TLC Taxi Zone in which the taximeter was disengaged.
8. RateCodeID: The final rate code is in effect at the end of the trip.
    - 1 = Standard rate
    - 2 = JFK
    - 3 = Newark
    - 4 = Nassau or Westchester
    - 5 = Negotiated fare
    - 6 = Group ride
9. Store_and_fwd_flag: Indicates whether the trip record was held in the vehicle memory before sending to the vendor.
    - Y = store and forward trip
    - N = not a store and forward trip
10. Payment_type: A numeric code signifying how the passenger paid for the trip.
    - 1 = Credit card
    - 2 = Cash
    - 3 = No charge
    - 4 = Dispute
    - 5 = Unknown
    - 6 = Voided trip
11. Fare_amount: The time-and-distance fare calculated by the meter.
12. Extra: Miscellaneous extras and surcharges (e.g., $0.50 and $1 rush hour and overnight charges).
13. MTA_tax: $0.50 MTA tax automatically triggered based on the metered rate in use.
14. Improvement_surcharge: $0.30 improvement surcharge assessed on hailed trips at the flag drop.
15. Tip_amount: Automatically populated for credit card tips (cash tips are not included).
16. Tolls_amount: Total amount of all tolls paid in the trip.
17. Total_amount: Total amount charged to passengers (does not include cash tips).
18. Trip_type: Indicates whether the trip was a street hail or a dispatch.
    - 1 = Street-hail
    - 2 = Dispatch

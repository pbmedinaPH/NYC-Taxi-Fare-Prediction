## Data Dictionary
<table>
  <tr>
    <th>Variable name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ID</td>
    <td>Trip identification number</td>
  </tr>
  <tr>
    <td>VendorID</td>
    <td>A code indicating the TPEP provider that provided the record.<br>    
  
  1= Creative Mobile Technologies, LLC;<br>
    
  2= VeriFone Inc.<br></td>
  </tr>
  <tr>
    <td>tpep_pickup_datetime</td>
    <td>The date and time when the meter was engaged. </td>
  </tr>
  <tr>
    <td>tpep_dropoff_datetime </td>
    <td>The date and time when the meter was disengaged. </td>
  </tr>
  <tr>
    <td>Passenger_count </td>
    <td>The number of passengers in the vehicle. This is a driver-entered value.</td>
  </tr>
  <tr>
    <td>Trip_distance </td>
    <td>The elapsed trip distance in miles reported by the taximeter.</td>
  </tr>
    <tr>
    <td>PULocationID </td>
    <td>TLC Taxi Zone in which the taximeter was engaged</td>
  </tr>
  <tr>
    <td>DOLocationID </td>
    <td>TLC Taxi Zone in which the taximeter was disengaged</td>
  </tr>
  <tr>
    <td>RateCodeID</td>
    <td>The final rate code in effect at the end of the trip. 

1= Standard rate <br>

2=JFK <br>

3=Newark <br>

4=Nassau or Westchester <br>

5=Negotiated fare <br>

6=Group ride</td>
  </tr>
  <tr>
    <td>Store_and_fwd_flag </td>
    <td>This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,”  because the vehicle did not have a connection to the server. <br>

Y= store and forward trip <br>

N= not a store and forward trip</td>
  </tr>
    <tr>
    <td>Payment_type </td>
    <td>A numeric code signifying how the passenger paid for the trip.  <br>

1= Credit card <br>

2= Cash <br>

3= No charge <br> 

4= Dispute <br>

5= Unknown <br>

6= Voided trip</td>
  </tr>
  <tr>
    <td>Fare_amount </td>
    <td>The time-and-distance fare calculated by the meter.</td>
  </tr>
  <tr>
    <td>Extra </td>
    <td>Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.</td>
  </tr>
  <tr>
    <td>MTA_tax </td>
    <td>$0.50 MTA tax that is automatically triggered based on the metered rate in use.</td>
  </tr>
      <tr>
    <td>Improvement_surcharge </td>
    <td>$0.30 improvement surcharge assessed trips at the flag drop. The  improvement surcharge began being levied in 2015.</td>
  </tr>
  <tr>
    <td>Tip_amount </td>
    <td>Tip amount – This field is automatically populated for credit card tips. Cash tips are not included.</td>
  </tr>
  <tr>
    <td>Tolls_amount </td>
    <td>Total amount of all tolls paid in trip. </td>
  </tr>
  <tr>
    <td>Total_amount </td>
    <td>The total amount charged to passengers. Does not include cash tips.</td>
  </tr>
</table>

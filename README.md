## Address_clean_up

**Written using Oracle & uses REGEX**  
  
Intended to be validated with a USPS address verification tool after this code has been run. Will not yield perfect results as it doesn't account for typos or addresses written out of order (something written as "STE 100 BLDG 1" will not get the STE number pulled over into the second address line column. It should be written like "BLDG 1 STE 100").  

Code includes spaces for unique_ID, city, state, zip_code (these can be deleted if you don't need them in your code)  


## Address_clean_up_for_practice_data_set  

Code doesn't include spaces for unique_ID, city, state, zip_code. It is ready to be used for the practice data set with exception to the database name (change as needed)


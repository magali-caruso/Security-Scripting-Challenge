# Security-Scripting-Challenge

As a Security Operations Engineer, you face the challenge of preventing Denial Of Services attacks from generating downtime in productive services. 

The alarm that monitors anamalous traffic is triggered and you need to respond to the incident. 


##Expected Goals

1. Get the information the traffic monitor provides via API.
   1.1 The monitor endpoint is the following: https://fbfac7f8-bafe-42c5-8c37-b1db396ab3ba.trayapp.io 
   1.2 This endpoint will return a url to download the csv with the vpc-flow-logs, only via Browser.

2. Analyze the content and determine how to block the traffic to stop the DOS attack.
  
3. Execute the chosen response tactic via API.
   1.1 The endpoint to the WAF API is the following: https://403d7dc8-4b36-4db5-98fe-bdabfedf3904.trayapp.io
   1.2 The expected body is:
   ```
         data = {
                "account-id": <integer>,
                "ip-address": <string>,
                "region": <string>
               }
    ```
   1.3 If you complete the ip-address parameter and region at the same time, the ip-address will be blocked and the region not. 
   1.4 If you want to block a region, leave the ip-address parameter empty.

##Take into account
You can choose any programming language you want, python is preferred due to the hiring manager capabilities. 
Questions are welcome. 
Keep it simple, make it work. 



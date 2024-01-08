# Security-Scripting-Challenge

As a Security Operations Engineer, you face the challenge of preventing Denial Of Services attacks from generating downtime in productive services. 

The alarm that monitors anamalous traffic is triggered and you need to respond to the incident. 


## Expected Goals

1. Get the information the traffic monitor provides via API.
   - The monitor endpoint is the following: GET https://fbfac7f8-bafe-42c5-8c37-b1db396ab3ba.trayapp.io 
   - This endpoint will return a url to download the csv with the vpc-flow-logs, only via Browser.

3. Analyze the content and determine how to block the traffic to stop the DOS attack.
   - The instance needs to have port 22 and 443 exposed to the internet
   - It is expected that the instance receives traffic from USA and Europe. Any other region is not expected.  
  
4. Execute the chosen response tactic via API.
   - The endpoint to the WAF API is the following: POST https://403d7dc8-4b36-4db5-98fe-bdabfedf3904.trayapp.io
   - The expected body is:
     
      ```
            data = {
                   "account-id": <integer>,
                   "ip-address": <string>,
                   "country": <string>
                  }
       ```
   
   - If you complete the ip-address parameter and region at the same time, the ip-address will be blocked and the region not. 
   - If you want to block a region, leave the ip-address parameter empty.

## Take into account
You can choose any programming language you want, python is preferred due to the hiring manager capabilities. 
Questions are welcome. 
Keep it simple, make it work. 



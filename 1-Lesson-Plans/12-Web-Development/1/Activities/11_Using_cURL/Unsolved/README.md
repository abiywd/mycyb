## Activity File: Using curl

In this activity, you will continue in your role as a web application security engineer.

- You are tasked with writing various `curl` commands to interact with an HTTP web server. 

- You will use various `curl` options, request methods, and request headers to return specific responses.

Use the [`curl` Reference Sheet](https://docs.google.com/document/d/18IkhxEUQ9-eyEH8JhWFaQf5zhM5HzFv8YVCHS0c42Gw/edit?usp=sharing) as a reference for your activity.

### Instructions

You will use `curl` commands to send HTTP requests to the site httpbin.org.

After constructing and testing each `curl` command, answer the questions that follow.

1. Sending a GET Request

    - Run a GET request to httpbin.org/anything.

    - What is returned by this request? Is there anything that identifies the requestor?

2. Retrieving Response Headers

    - Run a GET request to httpbin.org with an added `curl` argument to display response headers.

    - What is the content-type for this page?

3. Retrieving New Response Headers

    - Run a GET request to httpbin.org/anything with an added `curl` argument to display response headers.

    - What is the content-type for this page?

4. Sending a POST Request

    - Run a POST request that enters `'{"Developer": "Andrew"}'` for the data argument.
    
   - Under what JSON object does the posted data appear?

5. Setting Parameters

    - Run a POST request with an added parameters `?EmployeeDirectory=frontend`.

    - After the parameters go through, where do they appear in the JSON response body?

6. Setting Headers

    - Run the same POST from Step 4 with an added header: `-H "Content-Type: application/json"`.

    - Where does the request body data end up?

---
© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved. 

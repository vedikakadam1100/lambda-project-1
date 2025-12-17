# Introduction

The Lambda Project is centered around the concept of serverless computing using AWS Lambda, a cloud-based service that allows developers to run code without provisioning or managing servers. This project leverages the power of event-driven architecture to create scalable, cost-effective, and efficient applications that automatically respond to triggers such as HTTP requests, file uploads, or database updates.
 
![](./Screenshot%202025-09-18%20192612.png)


 # Create a Lambda Function

Go to AWS Lambda Console
.

Click "Create function".

Choose:

Author from scratch

Function name: HelloLambda

Runtime: Python 3.9 (or Node.js, etc.)

Click "Create function".

![](./img/Screenshot%202025-09-21%20155348.png)
  
 ![](./img/Screenshot%202025-09-21%20160042.png)

After Clicking "Add Trigger" (in Lambda)

When you click Add Trigger, here's what happens and what to do next:

1. ✅ You Selected:

Trigger type: API Gateway

API type: HTTP API

Security: Open (for now)



Click "Create function"
![](./img/Screenshot%202025-09-21%20160227.png)


 # Create function"
I clicked on the function name, and now I want to edit the code. I have some code from my website, and I want to paste that code into the Lambda function.

I clicked on the function name.

I went to the Code section.

I deleted the existing code and pasted my website code.

Then I clicked the blue Deploy button (or pressed Ctrl + Shift + U).

After that, AWS processes the update and the new code goes live.


![](./img/Screenshot%202025-09-21%20160428.png)


# configuration file
After copying the code, click on Configuration.
Then go to the 'Function URL' section on the right side of the screen (next to the code editor, like on a laptop).
Click on the function URL — it will open the URL where your Lambda function runs.
After copying and saving your code, click on the Configuration tab.
On the right-hand side (like on your laptop screen), you'll see Function URL.
Click on the URL shown there.

![](./img/Screenshot%202025-09-21%20161024.png)


# policy
Go to the Configuration tab.

Click on Function URL from the left side menu.

You will see a section for Auth type.

Change the Auth type from AWS IAM to None (this allows anyone to access the URL — useful for testing).

Now you can access the URL and show your custom response like "policy"

![](./img/Screenshot%202025-09-21%20161730.png)

![](/img/Screenshot%202025-09-21%20161426.png)


# url
Go to the Function URL section in the Lambda configuration.

Copy the URL provided.

Open your web browser (like Chrome).

Paste the URL into the address bar and press Enter.

![](./img/Screenshot%202025-11-11%20002647.png)


# web page 
After opening the Function URL in the browser, the website I created will appear — with titles like Lambda’s Aniket and Lambda’s Aniket.
I also added my Instagram profile there, so that link will be visible as well







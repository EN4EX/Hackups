# Intro 4

## Assignment

In this challenge, we've been given a login form. Our task is to find the correct credentials to complete this level.



## Analyze

Normally, in these form-type challenges, we first check the page source code to see if we can find the correct credentials there. But not in this challenge—this one requires a different method.

I always start by entering 'test' as both the username and password to analyze how the website processes the credentials. To do this, we simply enter anything in both fields, then press F12 to open DevTools.

Next, we switch to the **Network** tab. For better efficiency, we click **More filters** at the top and select **Doc** to view only document-type requests. Once everything is set up, we press the **Log In** button and examine the request.

To inspect it, we simply click on it. Under the **Payload** tab, we can see what information is being sent along with the request. And there it is! At the very bottom, we find `passwordfile:` followed by its value, which tells us where the credentials are stored.

To view them, we copy the entire value—excluding `passwordfile:`—and paste it directly after the current URL in the address bar. Then, we hit **ENTER**.

Boom! We can now see the credentials we've been looking for in plain text.



## Findings

In this challenge, we've encountered a different method for discovering the credentials we need. We also learned a bit about using DevTools and viewing `.txt` files in the browser.

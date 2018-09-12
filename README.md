# SubDomainTakeoverTools

In this repository I will put a series of scripts for testing Subdomain Takeover vulnerability.

# ShopifySubdomainTakeoverCheck.py
The script is using three methods to detect if Subdomain Takeover is possible on Shopify.
We use three methods in order to avoid False Positives because are quite annoying on large scale and automation. 
First of all you must understand that on Shopify you have two methods to perform a Subdomain Takeover, more information are available in the following article: 
https://medium.com/@thebuckhacker/how-to-do-55-000-subdomain-takeover-in-a-blink-of-an-eye-a94954c3fc75

How to use:

python3 ./ShopifySubdomainTakeoverCheck.py sub.domain.to.check


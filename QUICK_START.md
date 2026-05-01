# Quick Start Guide

## How to use these pages in Cloudflare

Because each page has a unique style tailored to a specific error type, you need to match the HTML file to the correct Custom Page setting in Cloudflare.

1. Log in to your Cloudflare Dashboard.
2. Select your domain.
3. Go to **Rules** > **Custom Pages**.

### Matching Files to Page Types:

| Cloudflare Page Type | File to Use |
| --- | --- |
| **WAF Block** (403) | Copy contents of `waf_block.html` |
| **IP/Country Block** (403) | Copy contents of `ip_block.html` |
| **500 Class Errors** (500, 502, 504) | Copy contents of `500_errors.html` |
| **1000 Class Errors** (1000, 1001) | Copy contents of `1000_errors.html` |
| **Rate Limiting Block** (429) | Copy contents of `rate_limit.html` |

### Steps to Apply:
1. Open the relevant `.html` file from this repository in a text editor.
2. Copy all of the code.
3. In the Cloudflare Custom Pages dashboard, click **Custom Pages** next to the specific error type you want to change.
4. Paste the copied HTML code into the provided text box.
5. Click **Publish** or **Save**.
6. Repeat for the other error types!

## Testing Locally

Simply double-click and open any of the HTML files in your web browser. The built-in Javascript includes a local fallback mechanism that automatically populates the Cloudflare tokens (like `::RAY_ID::` and `::CLIENT_IP::`) with fake mock data, so you can test the interactive animations and dialect jokes perfectly without needing to deploy them first!

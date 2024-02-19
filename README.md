# Tutorial on how to implement PayPal donation via SDK

## PAYPAL DONATE (PRODUCTION)

**URL:**
https://www.paypal.com/donate/buttons/manage

In this link you can find all the "donation pages" that you created in your "Paypal account".
You just have to enter one of them and there you will be able to see the "BUTTON_ID" of the respective donation page.
You must use this ID with the value "production" in the "env" property.

**EXAMPLE:**

```js
env: "production",
hosted_button_id: "APZNDKV6SCG20"
```

## PAYPAL DONATE (SANDBOX)

**URL:**
https://www.sandbox.paypal.com/donate/buttons/manage

In this link you can find all the "donation pages" that you created in your "Paypal Sandbox account".
You just have to enter one of them and there you will be able to see the "BUTTON_ID" of the respective donation page.
You must use this ID with the value "sanbox" in the "env" property.

**EXAMPLE:**

```js
env: "sandbox",
hosted_button_id: "QYME3NYDVFASV"
```

### EXTRA ALTERNATIVE

In addition to using the javascript SDK to implement PayPal donation, you can also directly use the link from your PayPal donation page to share it directly on your social networks or use it as a referral link in an html hyperlink.

EXAMPLE:

```html
<a href="YOUR_PAYPAL_DONATION_URL"> Sponsor the project </a>
```

You can configure how your donation page will look from the administration panel of your PayPal account

### DOCS:

https://developer.paypal.com/sdk/donate

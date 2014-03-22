% W3C Payments Workshop
% Kumar McMillan
% March, 2014


# ![arewemobileyet](images/arewemobileyet.png)

#

    var request = navigator.mozPay([jwt]);
    request.onsuccess = function() {
        // Wait for postback
    };

# Web payments today:

* Amazon
* PayPal
* Stripe

It works!

# Problems

* Credit cards
* Mobile billing
* New customer info
* Asset ownership

# Credit card numbers are insecure
# Payment tokens for merchants

* Pay me $X
* I don't care how
* expires in 5 minutes

# Secure payment token

* merchant <-> processor
* customer <-> processor

# Token examples

* PayPal hosted flow
* mozPay JSON Web Token

# Mobile billing is broken

# How do we fix this?

* HTTP header injection
* every operator is different
* SMS hacks

# Silent SMS API (in mozPay)

# Becoming a new customer is hard

# Solutions

* Request Autocomplete
* standard web identity?

# How do you prove you own an item?

# Digital receipts

* portable
* decentralized
* verifiable

# Payments work well on the web

# What are the payment primitives?

This is the source for some slides I presented
at the [W3C Payments Workshop](http://www.w3.org/2013/10/payments/Overview.html) in 2014.

You can view them on [Github Pages](http://kumar303.github.io/w3c-payments/).

The paper we submitted is available [here](http://www.w3.org/2013/10/payments/papers/webpayments2014_submission_13.pdf).

# Hacking

[![Greenkeeper badge](https://badges.greenkeeper.io/kumar303/w3c-payments.svg)](https://greenkeeper.io/)

To build the slides, create a virtualenv and install some dependencies:

    pip install -r requirements.txt

Then run this script:

    ./build.sh

Open `www/index.html` in your favorite web browser.

Deploy the slides to Github Pages:

    npm install
    volo build && volo ghdeploy

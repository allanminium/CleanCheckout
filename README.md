# Firebear Checkout for Magento 2

Most features reach checkout for Magento 2 based on free and open source CleanCheckout


## Full / paid version Features

- One step or multiple steps checkout switch
- Mobile first: super optimised UX for mobile conversion growth 
- Option for skip cart page - single product quick purchase 
- VAT validation 
- Check out page constructor, which allow drag & drop checkout page builsing
- Default values for each checkout step/block 
- Delivery date / time selection 
- Store pickup with stores map 
- Easy guest to customer conversion after purchase 
- Checkout abandonment tracking and followup emails 
- Edit cart page, product options at checkout, implement coupon
- Gift wrap & gift message 
- Newsletter subscription integration with Mailchimp, Active campaign, SendGrid
- Login and registration directly at checkout 
- Add custom forms, banners, static blocks to checkout
- Add Google Analytics even for each field and step for advanced analytics tracking 
- Google Analytics enhanced e-commerce tracking integration 
- Full-text search for each dropdown to make things easier for customer
- Allow attach files to order by customer - PDF , DOC specification and more
- Integration with TypeForm for custom survey and get extra info on friendly way 
- Integration with Stripe and PayPal express checkout - get all data pre-filled from customer profile but checkout on Magento 

## Free version Features

- Overall checkout improvements, such as;
    - Show input labels next to the fields
    - Allow disabling checkout fields like telephone, company, etc.
    - Remove the header and footer from the checkout entirely.
    - Force totals mode, so the customer is aware of totals during entire checkout.
    - In addition to the above, always show cart items for additional clarity.
    - Move cart/totals blocks to more logical places.
    - Remove jerkiness when switching between checkout steps, and allow setting of step transaction speed.
    - Allow disabling of useless shipping method step with just 1 available option.
    - Allow changing of checkout colors using useful colorpickers.
    - Uses [Font Awesome](http://fontawesome.io/) to provider better icons.
- Geo IP: Customer country is detected and immediately injected in the right places so it will be used for Shipping and Billing country fields and for calculating tax estimates.
- Social Login: Uses [Hybridauth](https://hybridauth.github.io/) to allow customers to login with their favorite social media.
- Newsletter: Lets customers immediately subscribe to the newsletter from the final step in the checkout.
- Address Autocompletion: Using the [Google Maps Autocomplete API](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-addressform), we can significantly reduce the number of fields required by the customer.
- Field Order: Allow administrators to choose their own order of checkout fields.

All of these features are highly customizable from the backend.

## Installation

```bash
$ composer require rubic/magento2-module-clean-checkout
```

## Screenshot

![Image of Clean Checkout](https://i.imgur.com/Fs7So1d.png)

## Demo

You can find a demo environment [here](https://demo.cleancheckout.com/). Please note that it may not be running the latest version of this module at all times.

## License

Copyright 2017 Rubic

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

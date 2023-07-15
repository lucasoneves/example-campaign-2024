# Example Campaign

This is an example of a simple campaign that demostrates the a straight forward integration with the [29next Campaigns App](https://developers.29next.com/docs/api/campaigns/)

### Checkout page

A basic offer select and order summary with the customer information form and payment options.

Contains an example of using the [Create Cart](https://developers.29next.com/docs/api/campaigns/#create-cart) method to capture basic user information before creating an order.

The example of the [Create Order](https://developers.29next.com/docs/api/campaigns/#create-order) method shows:

- Has an example of the required [iFrame Payment Form](https://developers.29next.com/docs/api/admin/guides/iframe-payment-form/) integration for Bankcard payments

- Also shows an example of how to handle an example "APM Redirect Payment Flow" for paypal

We are utilizing [Just Validate](https://just-validate.dev/) as an example of form validation


### Upsell page

Demostrates a basic example of the [Retrieve Order Details](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to check if the choosen payment method supports post purchase upsells 

As well as the [Create Upsell Order](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to show how to add post purchase upsells to an order if the payment method supprts them

### Thank You  / Confirmation page

Shows an example of using the [Retrieve Order Details](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to map the values to the template to create an order summary for the customer.
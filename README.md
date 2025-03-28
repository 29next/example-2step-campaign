# Example 2 Step Campaign

This is an example of a simple 2 step campaign that demostrates a straight forward integration with the [29next Campaigns App](https://developers.29next.com/docs/api/campaigns/)

You can run these pages on a local server using this script and get real feedback from a test store on 29next

```
npm install

npm start
```

### Step 1 Customer Information Page

A basic offer select and order summary with the customer information form.

Contains an example of using the [Create Cart](https://developers.29next.com/docs/api/campaigns/#create-cart) method to capture user information before going to a payment page to complete the order.

We are utilizing [Just Validate](https://just-validate.dev/) as an example of form validation

We are utilizing [International Telephone Input](https://intl-tel-input.com/) for phone number validation
 
### Step 2 Payment Information Page

The example of the [Create Order](https://developers.29next.com/docs/api/campaigns/#create-order) method shows:

- An example of the required [iFrame Payment Form](https://developers.29next.com/docs/api/admin/guides/iframe-payment-form/) integration for Bankcard payments

- Also shows an example of how to handle an example "APM Redirect Payment Flow" for paypal

We are utilizing [Just Validate](https://just-validate.dev/) as an example of form validation

You can use our [test cards](https://docs.29next.com/manage/orders/test-orders) to create a card order


### Upsell page

Demostrates a basic example of the [Retrieve Order Details](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to check if the choosen payment method supports post purchase upsells 

As well as the [Create Upsell Order](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to show how to add post purchase upsells to an order if the payment method supports them


### Thank You  / Confirmation page

Shows an example of using the [Retrieve Order Details](https://developers.29next.com/docs/api/campaigns/#adding-upsells) method to map the values to the template to create an order summary for the customer.

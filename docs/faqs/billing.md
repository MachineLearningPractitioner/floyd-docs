Please see here for [Plan FAQs](./plans.md)

## Payment Questions

### What forms of payments do you accept?

We accept Visa, MasterCard, American Express and Discover credit and debit cards. We do not accept prepaid cards at the moment. 

We are a US based company. If you are outside the US, please ensure your card has 
international transactions enabled.

### Do you keep my credit card information?

No, we do not retain any credit card information. We use
[Stripe](https://stripe.com/) to process payments.

### Payment processing failed. Whay am I unable to add my payment method?

When you submit your payment details, you may received a "Error: Payment processing failed" error notification.

![Payment processing failed](../img/payment-processing-failed.jpg)

Some common causes are:

- **Credit and Debit cards only**: We currently accept only Visa, Mastercard and AmEx credit and debit cards. We do not accept prepaid cards. Please ensure you are using a valid credit or debit card.
- **Balance**: We issue a small $0-1 transaction on your card as a pending authorization request between our billing system and the bank that issued your credit or debit card. If this authorization fails, you won't be able to add your card. Please ensure you have enough balance and are using a valid card. *Note*: This is an authorization request only, not an actual charge.
- **Fraud Detection**: We use Stripe for managing all our payments. They have their own fraud detection algorithm which can decline some cards. Please try a different payment method.
- **International Cards**: We are a US based company. If you are outside the US please ensure your card has international transactions enabled.

If you are still unable to add your payment, please contact us directly at [support@floydhub.com](mailto:support@floydhub.com).



## Billing Questions

### What am I billed for?

Your usage includes compute (CPU / GPU) usage and storage consumption. 

- **Compute**: You will be billed exactly for the duration that your job runs, rounded off to the nearest second.

    Note that you are only charged for compute when your job is in the *Running* state. You will *not* be charged when your job is in any other state, including *Queued* and *Shutdown*.

- **Storage**: You will also be charged for the storage you consume, rounded off to the nearest kB. 

    Storage is consumed by the datasets that you upload, your code and the data that your jobs output.

### When will my card be charged?

For monthly subscription plans, your card will be charged every month on the day you upgraded to the plan. For example, if you upgraded from the Beginner to the Data Scientist plan on the 22nd of August, you will be charged immediately. You will be then billed on the 22nd of every month.

When you purchase Powerups, either directly from the [Powerups Dashboard](https://www.floydhub.com/settings/powerups) or via auto-refresh, you will be charged at the time of purchase.

### Can I upgrade or downgrade my plan?

You can upgrade or downgrade your subscriptions at anytime from your [Plans page](https://www.floydhub.com/settings/plan) under Settings on your dashboard. 
You will be immediately changed to the new plan. 

Upgrades and downgrades do not affect any Powerups you may have purchased.

### How do upgrades work?

When you upgrade from the Beginner plan to a paid plan, you will be charged immediately. You will then be billed on the 1 month anniversary of your subscription date every month. For example, if you upgrade on August 20th, 2017, you will be charged on that day and on the 20th of every subsequent month.

When you upgrade from one paid plan to another, you will be charged for your new plan on a pro-rated basis. Lets say your billing cycle is on the 20th of every month. If you upgrade from the Beginner to the Pro plan on the 5th, you will be charged for the new plan on a pro-rated basis (5th to 20th).

### How do downgrades work?

You can downgrade at any time to a lower or Beginner plan. 

[comment]: <> (If you are over the usage limits for the plan you are downgrading to, you will have to handle that first. For example, lets say you are downgrading from the Data Scientist to Beginner plan, but have 50GB data and private projects. You will have to delete some of your data and all your private projects before downgrading, since the Beginner plan only offers 10 GB and public projects.)

### How do I remove my credit card?

Please downgrade to the Beginner plan and remove your credit card on file.

### Do my remaining compute credits roll over each month if I don't use them all?

No, your monthly Plan compute credits are not rolled over. However, your Powerup credits will remain valid for one year from purchase date.

### Do you offer refunds?

No, we do not offer refunds. If there are extenuating circumstances, please open a ticket by contacting our support team.

{!contributing.md!}

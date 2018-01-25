# VirtueMart 3.x & Joomla 3.x:

### Setup
Download the Modernt Transact Virtuemart payment module [here]()
In your Joomla admin, navigate to Extensions -> Extension Manager
Upload tco.zip under Upload Package File
Under Components -> Shop -> VirtueMart -> Payment Methods, click New
Select 2Checkout as the payment method.
Enter a Payment Method Name
Select Yes for Published
Enter a Payment Description (Example: Credit Card (Visa, MasterCard, American Express, Discover, JCB, Diners Club) and PayPal)
Click Configuration
Enter your 2Checkout Seller ID (2Checkout Account Number)
Enter your 2Checkout Secret Word. (Must be the same value entered on your 2Checkout Site Management page.)
Set Sandbox to “Yes” for Sandbox mode. For live sales, ensure Sandbox is set to “No”
Set Inline Checkout to “Yes” to use Inline Checkout. For Hosted Checkout, ensure Inline Checkout is set to “No”
OPTIONAL: Select your preferred logo, if you have one (VirtueMart Images are stored in /images/stories/virtuemart/payment
Click Save.
2Checkout Settings:
Sign in to your 2Checkout account.
Click the Account tab and Site Management subcategory.
Under Direct Return select Header Redirect
Enter your Secret Word (Must be the same value entered in your VirtueMart admin.)
Click Save Changes
For more information visit: VirtueMart.net

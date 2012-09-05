#### _For a discount on 2Checkout’s monthly fees, enter promo code:  GIT2CO  during signup._

## MS-Core 2Checkout
----------------------------------------

### MS-Core Settings

1. Download or clone extension at https://github.com/craigchristenson/ms-core-2checkout
2. Extract and upload the uc\_2checkout directory to /modules/MS-Core/gateways on your hosting/server. 
3. Sign in to your Drupal admin.
4. Click **Modules**.
5. Under **MS-Core** activate **2Checkout** and save your changes.
6. From the admin menu click **Store**.
7. Click **Configure** select **2Checkout**.
8. Enter your Payment Method Title.
9. Under **Gateway Mode** select **Production** for live sales or **Test Mode** for demo sales.
10. Enter your [language code](https://www.2checkout.com/faq/).
11. Enter your **2Checkout Seller ID** (2Checkout Account Number).
12. Enter your **Secret Word**. (Must be the same value entered on your 2Checkout Site Management page.)
13. Enter your **2Checkout API Username** and **API Password**. (You must create a new API Username in your 2Checkout admin.)
14. Click **Save Configuration**.

### 2Checkout Settings

1. Sign in to your 2Checkout account. 
2. Click the **Account** tab and **Site Management** subcategory. 
3. Under **Direct Return** select **Header Redirect**. 
4. Enter your **Secret Word**._(Must be the same value entered in your UberCart admin.)_
5. Set your approved URL to "http://yourstore.com/ms\_twocheckout/return\_ok" replacing "yourstore.com" with your store URL.
6. Under the **Notifications** tab enable the Fraud Status Changed message and set the URL to "http://www.yourstore.com/ms\_twocheckout/return\_ok" replacing "yourstore.com" with your store URL.
7. Click **Save Changes**.

**Please contact 2Checkout directly with any integration questions.**
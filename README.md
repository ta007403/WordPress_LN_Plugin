🧩 WooCommerce LNBits Lightning Payment Gateway<br>

#

⚡ Overview<br>

The WooCommerce LNBits Gateway plugin allows your store to accept Bitcoin Lightning payments directly through your own LNBits instance — without intermediaries or custodians.<br>

It seamlessly integrates with WooCommerce checkout, generating a BOLT11 Lightning invoice for each order and automatically marking the order as completed once payment is confirmed on the Lightning Network.<br>

#

✨ Key Features<br>

💰 Accept Bitcoin Lightning Payments — create LN invoices instantly via LNBits API.<br>

🧾 Automatic Order Completion — the plugin polls LNBits and updates order status once payment is confirmed.<br>

🧱 Works with Any LNBits Instance — connect to your own self-hosted or cloud-hosted LNBits server.<br>

⚙️ Customizable API & Redirect URLs — configure LNBits endpoint, API key, and optional post-payment redirect via admin settings.<br>

🔒 Secure Integration — uses WooCommerce REST API consumer keys and HTTPS requests.<br>

🌐 Multilingual Support — includes Thai checkout message about Lightning payments.<br>

#

⚙️ How It Works<br>

Customer selects “Bitcoin Lightning (⚡ via LNBits)” at checkout.<br>

The plugin requests an invoice from your LNBits API.<br>

A QR code is displayed on the “Order Received” page.<br>

The system checks the payment status every few seconds.<br>

When LNBits reports "paid": true, WooCommerce marks the order completed automatically.<br>

(Optional) Redirects to your chosen thank-you page after confirmation.<br>

#

🧠 Requirements<br>

WordPress with WooCommerce<br>

LNBits instance (self-hosted or via Voltage / OpenNode / custom server)<br>

API key with invoice / read permissions<br>

WooCommerce REST API Consumer Key & Secret<br>

#

⚙️ Configuration<br>

In WordPress Admin → WooCommerce → Settings → Payments → LNBits Lightning<br>

Enable the gateway<br>

Set the following fields:<br>

LNBits API Endpoint (example: https://yourdomain.com)<br>

LNBits API Key (invoice/read key)<br>

WooCommerce Consumer Key<br>

WooCommerce Secret Key<br>

(optional) Redirect URL after successful payment<br>

#

This is a picture for more explaination<br>

![WP_LN_Plugin_2](https://github.com/user-attachments/assets/09b57c28-cb21-4c20-b8df-c8db486c607f)

#

![WP_LN_Plugin_1](https://github.com/user-attachments/assets/9cc8b32d-e19d-4545-916a-12ba1253fc02)

#

![WP_LN_Plugin_3](https://github.com/user-attachments/assets/d5d156e3-fd8d-4b1d-9873-3c1b397e4ce9)

#

![WP_LN_Plugin_4](https://github.com/user-attachments/assets/b394cbb7-cf60-4cab-9760-1b8e4af2e8ff)

#

![WP_LN_Plugin_5](https://github.com/user-attachments/assets/5cc3eda3-bd99-45ec-9584-18f7018882bf)

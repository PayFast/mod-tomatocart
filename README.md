mod-tomatocart
==============

PayFast module for TomatoCart

PayFast TomatoCart Module v1.00 for TomatoCart v1.1.8.1
-------------------------------------------------------
Copyright (c) 2011 - 2016 PayFast (Pty) Ltd

LICENSE:
 
This payment module is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published
by the Free Software Foundation; either version 3 of the License, or (at
your option) any later version.

This payment module is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public
License for more details.

Please see http://www.opensource.org/licenses/ for a copy of the GNU Lesser
General Public License.

INTEGRATION:
1. Unzip the module to a temporary location on your computer
2. Copy the “admin” and “includes” folders in the archive to your base “TomatoCart” folder
- This should NOT overwrite any existing files or folders and merely supplement them with the PayFast files
- This is however, dependent on the FTPprogram you use
3. Login to the admin section of your TomatoCart installation
4. Navigate to Start -> Modules -> Payment Modules
5. Scroll down to the PayFast Website Payments payment method and click the “Install” button to install the module
6. Once the module is installed, click on “Edit” button.
7. The PayFast options will then be shown, edit the payment status as required, edit the zones if required, select the sandbox mode, enable the payment module and click “Save”.
8. The module is now ready to be tested with the Sandbox. To test with the sandbox, use the following login credentials when redirected to the PayFast site:
- Username: sbtu01@payfast.co.za
- Password: clientpass

How can I test that it is working correctly?
If you followed the installation instructions above, the module is in “test” mode and you can test it by purchasing from your site as a buyer normally would. You will be redirected to PayFast for payment and can login with the user account detailed above and make payment using the balance in their wallet.

You will not be able to directly “test” a credit card, Instant EFT or Ukash payment in the sandbox, but you don”t really need to. The inputs to and outputs from PayFast are exactly the same, no matter which payment method is used, so using the wallet of the test user will give you exactly the same results as if you had used another payment method.

I”m ready to go live! What do I do?
In order to make the module “LIVE”, follow the instructions below:

1. Login to the admin section of your TomatoCart system
2. Navigate to Start -> Modules -> Payment Modules
3. Under PayFast Website Payments, click on the “Edit” link
4. In the PayFast Settings block, use the following settings:
5. Set Sandbox Mode = “Live”
6. Merchant ID = <Integration Page>
7. Merchant Key = <Integration Page>
8. Click Save

******************************************************************************
*                                                                            *
*    Please see the URL below for all information concerning this module:    *
*                                                                            *
*                 https://www.payfast.co.za/shopping-carts/tomatocart/       *
*                                                                            *
******************************************************************************
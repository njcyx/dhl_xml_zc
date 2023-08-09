# DHL XML Shipping for Zen-Cart. v2.0.0

8/9/2023 update: bug fixes

Code is based on DHL Shipping plug-in, v1.1.0. Author: bislewl
https://www.zen-cart.com/downloads.php?do=file&id=1910

Code tested in zc 1.5.7d & php 7.4.

DHL XML Api account is needed. To create an account, see below: 

https://xmlportal.dhl.com/login

Special thanks to upsoauth plug-in from @lat9 and fedexwebservices plug-in from @Numinix. 

Notes: 
1) This plug-in doesn't have an option to exclude the country from the shipping quote. To exclude countries, please edit modules/shipping/dhlxmlservices.php around line 140.
2) For some countries (like Ireland), the estimated shipping quote page in the shopping cart doesn't show the DHL quote. But during the checkout page, you will see the DHL shipping quote properly. It seems that DHL needs the "city" value to get a quote, at least for some countries. 

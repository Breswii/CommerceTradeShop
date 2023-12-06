# Free Version Quick-Start

## 1. Place *CommerceTradeShop* mod in mods folder

* Place *CommerceTradeShop* mod in the mods folder
![mods folder](images/mods.png)
* Start the server

## 2. Stop server and setting Stripe

* When your server finished load *CommerceTradeShop* mod, stop your server
* Your minecraft server folders 'config/commercetradeshop/' will be like below
* ![mods folder](images/config.png)
## 3. Create your Stripe account and get your API key
* open [Stripe Website](https://stripe.com)
* ![img.png](images/stripeweb.png)
* create a stripe account
* ![img.png](images/signup.png)

## 4. Create your product in Stripe(TEST)
* Try to create a product in Stripe
* ![img.png](img.png)
* ![img_1.png](img_1.png)
* ![img_2.png](img_2.png)


***⬇⬇⬇___MAKE SURE ITS ONE-OFF___⬇⬇⬇***

* ![img_3.png](img_3.png)
* Click your product page
* ![img_4.png](img_4.png)
* Copy your product's price api id and store it in a place
* ![img_5.png](img_5.png)

## 5. Test api(TEST)

* Copy your test api
* ![img_6.png](img_6.png)
* ![img_7.png](img_7.png)
* ![img_8.png](img_8.png)
* Paste api in your `config/commercetradeshop/account.json`
* ![img_9.png](img_9.png)

## 6. Create your shops

* Download the shop generator [ShopGenerator](ShopGenerator/shop.exe)
* Watch the video to learn [How to use ShopGenerator](ShopGenerator/ShopGenerator.mp4)
* The more details about shop json is in [ShopGeneratorDetails](../Details/ShopGenerator.md)
* Then put the json file into `config/commercetradeshop/shops`
* Last, start your server to preview use `/shop <your-json-file-name-which-is-also-shop-name>` just like `/shop free` which means shop's json file is free.json in the shops folder


## 7. Stripe recognize and Real trade

* When you get ready to have a real money trade:
  1. Continue to recognize your stripe account
  2. ![img_10.png](img_10.png)
  3. ![img_11.png](img_11.png)
  4. Remember to close the button and change your test api in `config/commercetradeshop/account.json` to the **REAL API**

## 8. For more detail
  1. Search the wiki
  2. [Add Discord Server](https://discord.gg/vVyGTSppQ7) 
  3. [Add Patreon VIP](https://www.patreon.com/breswii/membership)

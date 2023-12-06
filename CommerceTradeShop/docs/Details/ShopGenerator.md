# ShopGenerator Json Details

## Pro and Free

### name
    Your shop name

### size
    Your shop GUI size

### item id
    A unique id of your item

### item title
    your item title

### type
    choose what type your item want to show

### value
    your shop item's skull value which you can find more in below link
[MinecraftHead](https://minecraft-heads.com/)

### id
    your shop item's item icon id
<span style="color:red;">Warning</span>  
* <span style="color:red;">Make sure your icon id is lower letters, like "dirt"</span>


### buyable
    It's a boolean value, if you want your item to be buyable, set it to true, if not, set it to false
<span style="color:red;">Warning</span>  
* <span style="color:red;">When your Buyable is true, Make sure your Commands isn't empty</span>

### prid
    Your product's price id in stripe

### pos
    Your item's position in shop     
<span style="color:red;">Warning</span>  
* <span style="color:red;">Make sure your pos lower than your shop size</span>

### command id
    Your item's command unique id in shop

### command
    When player have bought your item the command will be executed
<span style="color:red;">Warning</span>  
* <span style="color:red;">Make sure your command have a "/" in the front, like "/time set day" </span>

### permission
    "1" means player to run the command, "2" means server to run the command

## Pro

### cd:
    When your player click check buy icon, there will be a cooldown time. Use second unit 

### AM:
    A boolean which is true means your item have animation.
<span style="color:red;">Warning</span>  
* <span style="color:red;">When you ser it to true, the icon will not be use </span>

### interval(iv):
    your animation interval. Use tick unit

### Random(rd):
    When you set it to true, the Animation will be random.

### amitems:
    They will be show as the queue.
<span style="color:red;">Warning</span>  
* <span style="color:red;">When AM is true, make sure this is not empty</span>

### count:
    Set yout icon counts.

### lore:
    Set your item's lore. Lores support color and placeholder. Check the details below link.
[PlaceholderAPI](https://placeholders.pb4.eu/)

### glow:
    Set your item to glow. a boolean value.

### web:
    Set your item to the website after buy the product.
<span style="color:red;">Warning</span>  
* <span style="color:red;">Make sure web is not empty</span>  
* <span style="color:red;">Make sure web be like " https://google.com " </span>


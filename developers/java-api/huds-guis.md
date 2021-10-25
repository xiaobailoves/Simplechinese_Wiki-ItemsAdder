# HUDs, GUIs...

To see how to use HUDs and GUIs API (Font Images) you can check my examples:

{% embed url="https://github.com/LoneDev6/API-ItemsAdder-Example-GUI" %}

{% embed url="https://github.com/LoneDev6/API-ItemsAdder-Example-ServerMonitor" %}



### Access mana bar value example

```java
PlayerHUDsHolderWrapper huds = new PlayerHUDsHolderWrapper(player);
PlayerQuantityHudWapper manaHud = 
                new PlayerQuantityHudWapper(huds, "magiccraft:mana_bar");
manaHud.setFloatValue(2.0f);
```

## FAQ

{% content-ref url="../../plugin-usage/adding-content/advanced/font-images/common-errors.md" %}
[common-errors.md](../../plugin-usage/adding-content/advanced/font-images/common-errors.md)
{% endcontent-ref %}

### Get Emoji or GUI character

```java
new FontImageWrapper("twitteremojis:confirm").getString()
```

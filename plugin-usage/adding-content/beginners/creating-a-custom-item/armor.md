# Armor

## Custom armor example

```yaml
items:
  ruby_head:
    display_name: Ruby helmet
    permission: rubyarmor
    resource:
      generate: true
    durability:
      max_custom_durability: 275
    specific_properties:
      armor:
        slot: head
        color: ff0000
    attribute_modifiers:
      head:
        armor: 9
        armorToughness: 1
  ruby_chest:
    display_name: Ruby chestplate
    permission: rubyarmor
    resource:
      generate: true
    durability:
      max_custom_durability: 400
    specific_properties:
      armor:
        slot: chest
        color: ff0000
    attribute_modifiers:
      chest:
        armor: 7
        armorToughness: 1
  ruby_legs:
    display_name: Ruby leggings
    permission: rubyarmor
    resource:
      generate: true
    durability:
      max_custom_durability: 375
    specific_properties:
      armor:
        slot: legs
        color: ff0000
    attribute_modifiers:
      legs:
        armor: 5
        armorToughness: 1
  ruby_boots:
    display_name: Ruby boots
    permission: rubyarmor
    resource:
      generate: true
    durability:
      max_custom_durability: 325
    specific_properties:
      armor:
        slot: FEET
        color: ff0000
    attribute_modifiers:
      feet:
        armor: 3
        armorToughness: 1
```

{% content-ref url="../../../../faq/can-i-create-slabs-stairs/" %}
[can-i-create-slabs-stairs](../../../../faq/can-i-create-slabs-stairs/)
{% endcontent-ref %}

## Custom texture (only in inventory)

To add a custom texture for an armor item you have to specify a texture or a model (like for every other custom item).

{% hint style="warning" %}
#### Update to ItemsAdder 2.4.17+
{% endhint %}

### Custom item texture

```yaml
items:
  custom_helmet:
    display_name: "Custom Helmet"
    permission: armors.custom_helmet
    resource:
      generate: true
      textures:
       - "item/custom_helmet"
```

### Custom item model

```yaml
items:
  custom_helmet:
    display_name: "Custom Helmet"
    permission: armors.custom_helmet
    resource:
      generate: false
      model_path: "item/custom_helmet"
```

### Custom on-body armor texture

{% content-ref url="../../optifine-only-features/armor-textures.md" %}
[armor-textures.md](../../optifine-only-features/armor-textures.md)
{% endcontent-ref %}


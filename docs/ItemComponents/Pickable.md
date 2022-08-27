# Pickable


## Attributes

Pickable allows an item to be picked up without being able to hold or use it, making it cheaper than [Holdable](Holdable.md). This item is not required if you're using another component which defines what slots it can go into.

If you wish for it to be holdable or useable use the [Holdable](Holdable.md) component instead.

This component supports the attributes defined in: [ItemComponent](ItemComponent.md)


## Example
```xml
<Item identifier="stungundartfulgurium" category="Weapon" maxstacksize="8" interactthroughwalls="true" cargocontaineridentifier="metalcrate" tags="smallitem,stungunammo" Scale="0.5" impactsoundtag="impact_metal_light">
  <Pickable slots="Any" msg="ItemMsgPickUpSelect" />
  [...]
</Item>
```


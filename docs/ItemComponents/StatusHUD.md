# StatusHUD


## Attributes

This component supports the attributes defined in: [ItemComponent](ItemComponent.md)

This component only supports being used as a child of [Wearable](Wearable.md).


## Example
```xml
<Item identifier="thermalgoggles" scale="0.5" category="Equipment" tags="smallitem,clothing" cargocontaineridentifier="metalcrate" impactsoundtag="impact_metal_light">
  <StatusHUD drawhudwhenequipped="true" overlaycolor="176,0,0,120" range="3000" thermalgoggles="true" showdeadcharacters="false" showtexts="false" />
  [...]
</Item>
```


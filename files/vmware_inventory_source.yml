---
hostnames:
- 'config.name'
properties:
- config
- runtime
filters:
- runtime.powerState == "poweredOn"
with_tags: true
with_nested_properties: true
keyed_groups:
- key: tags
  prefix: 'grp'
  separator: '_'
- key: config.guestFullName
  prefix: 'grp'
  separator: '_'

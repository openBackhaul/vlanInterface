# vlanInterface
- Technology specific interface definition for VLAN interfaces according to IEEE 802.1Q-2018
- Thorsten Heinze (Thorsten.Heinze@openBackhaul.com)

### Branch
- 1.0.0-tsp.d.t : Model for the Transport SDN Pilot at Telefonica Germany

### UML
- [VlanInterface_1.0.0-tsp.200731.1235](./VlanInterface_1.0.0-tsp.200731.1235.zip)

### Overview 
- [VlanInterface_1.0.0-tsp.200731.1235+overview.1](./VlanInterface_1.0.0-tsp.200731.1235+overview.1.png)

### List of Classes
- to be provided

### GenDoc Export
- [VlanInterface_1.0.0-tsp.200731.1235+gendoc.1](./VlanInterface_1.0.0-tsp.200731.1235+gendoc.1.docx)

### Augmentation Condition
- When statement in Augmentation statement demands for LayerProtocol::layerProtocolName==LAYER_PROTOCOL_NAME_TYPE_VLAN_LAYER

### YANG File
- [VlanInterface_1.0.0-tsp.200731.1235+yang.1](./VlanInterface_1.0.0-tsp.200731.1235+yang.1.zip)
- [VlanInterface_1.0.0-tsp.200731.1235+yang.2](./VlanInterface_1.0.0-tsp.200731.1235+yang.2.zip) is correcting issues [#11](../../issues/11) and [#12](../../issues/12)

### Interface Simulator
- to be provided 

### Interface Validator
- to be provided 

### Publication
- Candidate for ONF TR-532 v2.0

### Aspired Model Classification
- Live Network

### Open Issue List
- [vlanInterface/issues](../../issues)

### Comments
Starting with 1.0.0-tsp.190812.1840 the proposed VlanInterface definition is based on [ieee802-dot1q-bridge.yang](./ieee802-dot1q-bridge.yang), which has been published as a part of the IEEE Std 802.1Q-2018 in its revision 2018-03-07.

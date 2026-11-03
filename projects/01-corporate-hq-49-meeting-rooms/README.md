# Corporate HQ: 49 meeting rooms

**Client:** international company, new commercial building (Spain). Name withheld.
**Role:** AV Project Engineer: pre-sales, system design, Q-SYS programming, site coordination, commissioning and post-handover support.
**Scale:** tender above €1.5M · 49 meeting rooms in a single building.

## Brief

Equip a new building with meeting rooms that work the same way in every space, are simple for users, and can be supported and maintained after handover.

## System design

| Room type | Quantity | Video conferencing | Display | Audio and control |
|---|---|---|---|---|
| Meeting room | 40 | Cisco Room Kit EQ | Display | Cisco Room Kit EQ |
| LED meeting room | 9 | Cisco Room Kit EQ | LED wall with NovaStar processing | Q-SYS Core 8 Flex, Shure MXA920 ceiling microphones, Powersoft amplification |

In the LED rooms, the Cisco Room Kit EQ handles the video call while the Q-SYS Core 8 Flex runs audio processing and room control underneath it.

## Automation

Room control is automated in Q-SYS and exposed to users through UCI panels:

- Power on and off for the whole room (displays, LED processing, amplification)
- Source switching
- Picture-in-picture on the LED wall

Selected, anonymised control logic is in [`q-sys/`](q-sys/).

## Delivery

- AutoCAD drawings, schematics and rack elevations (anonymised versions in [`drawings/`](drawings/))
- Coordination with the building contractors and the client's IT network team
- Pricing and technical escalations with manufacturers and vendors
- Commissioning, quality control, user training and close-out documentation
- Post-handover support, monitoring and preventive maintenance

## Files

- `drawings/`: TODO: add anonymised block diagram and typical-room drawings (PDF)
- `q-sys/`: TODO: add anonymised screenshots of the UCI and design notes, plus any Lua scripts

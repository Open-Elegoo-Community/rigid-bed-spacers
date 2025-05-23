# Rigid Bed Spacers
Status: Experimental

## Proposal
While working on an AWD SYNC, I observed that the Y-axis base plate IS graph is rock solid. This led me to think that the bed is a shaking mess. From experience, we know that replacing the stock springs with silicone spacers provided better stability, but there was still a lot of room for improvement. A leading hint to this was that SilencedFrosted from the Elegoo Discord mentioned he used aluminum spacers, which he filed down to the appropriate lengths after repetitive testing.

I propose to replace the spacers with something that anchors better to the base plate, not just screws and give it some room for adjustment. 

## Testing

Input Shaping with Silicon Spacers:
![image](https://github.com/user-attachments/assets/3c144684-910d-41be-a6ea-eccfe320a5ad)

The first experiment was with aluminum spacers (bottom), a silicone washer (middle), and a fiber washer (top) so the silicone would not push through.

This tightened the IS graph, but I found the spacers I chose brought me too close to adxl345 in the center of my base plate (see AWD Y Axis). Additionally it was a pain to align the parts when remounting the bed, and the silicone was not spongy enough to keep the tension when loosening the bed screws while tramming the bed.

Fusion Model:
![image](https://github.com/user-attachments/assets/50d88841-5f0e-4206-a14d-3b4a5703a5df)

Input Shaping with aluminum/silicone/fiber:
![image](https://github.com/user-attachments/assets/d35fe255-1e2c-4696-9c63-de679106c35f)

I needed a way to have the spacers the height I needed without having to order them. They needed to be resistant to heat and be rigid. Why not print them? I created a quick model in Fusion and printed it in ASA. I also added silicone washer between the spacer and the fiber washer.

Input Shaping with ASA/silicone/fiber:
![image](https://github.com/user-attachments/assets/161dd943-3e31-4c17-af58-3659359ab71f)

## Conclusions
After several hours of printing ASA using an enclosure, I inspected the spacers. There was some small dimpling on the topmost layer. I placed a metal fender washer between the spacer and the silicone.
- The dimpling was likely due to too few top layers
- The fender washer is giving the stability needed. It will be a permanent addition to this modification.
- I would like to test with some spongier silicone

## BOM
- 4 x Fiber washer
- 1 x 0.125 inch sheet of silicone. If doubling, find a 0.25 inch thick sheet or washer.
- 4 x metal fender washers

Note: The ID of the washers needs to be 4mm.  

## Version 2 - Untested
To save on costs, I redesigned the spacer to use the original silicone spacer most of us have been using for years. 

I have not tested these yet, so I don't know if the IS performance changes. I have been busy printing other fun things, so I have not wanted to pull the bed up again and re-tram. Try it out and get back to me.

The installation is the same except you will want the smaller hole up on top.

![image](https://github.com/user-attachments/assets/cdc80bd3-775d-4c0a-9e62-25833e003e54)




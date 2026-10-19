##Challenge Description : 

DEADFACE has been researching companies connected to one of their latest targets. Among the files recovered was a photo of a traffic accident involving a commercial truck.

We believe the truck may identify a company DEADFACE has taken an interest in. Determine which company owns the truck and when that company was founded.

Submit the flag as: `deadface{MM_DD_YYYY}`. Example: `deadface{01_20_2026}`

truck_crash.png

## Solution :

First, I tried the obvious reverse image search but didn’t really an exact location. Then I looked at the signs, specifically - “S 200th St”. A quick google search made it clear that this was a photograph taken in SeaTac, Washington. 

Zooming on to the body of the truck - I noticed there is a code written on the cargo box of the truck  `USDOT : 080806`

Simply googling this number reveals the company - ***J B HUNT TRANSPORT INC.*** 

the official website says that the comany was established in **August 10, 1961** 

## Flag :

thus, the flag in the format `deadface{MM_DD_YYYY}` is : 

`deadface{08_10_1961}`

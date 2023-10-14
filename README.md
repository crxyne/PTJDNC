# PTJDNC
Fully configurable playtime + joindate based namecolor plugin for 1.19

In order to get access to any given name color, both the joindate requirement (JD min.) as well as the playtime requirement (PT min.) have to be fulfilled.
The playtime numbers here are measured in hours, whereas the joindate is either measured in days, or a certain date, where the player must have joined before it.

# Example Configuration
| color       | PT min. | JD min.      | example                       | hex code |
|-------------|---------|--------------|-------------------------------|----------|
| dark_red    | 384     | 365           | ![](examples/dark_red.png)    | #AA0000  |
| red         | 64      | 32         | ![](examples/red.png)         | #FF5555  |
| gold        | 48      | 24         | ![](examples/gold.png)        | #FFAA00  |
| yellow      | 96      | 64         | ![](examples/yellow.png)      | #FFFF55  |
| green       | 48      | 32         | ![](examples/green.png)           | #55FF55  |
| aqua        | 424      | 365         | ![](examples/aqua.png)        | #55FFFF  |
| dark_aqua   | 528     | 365   | ![](examples/dark_aqua.png)   | #00AAAA  |
| blue        | 16       | 8         | ![](examples/blue.png)        | #5555FF  |
| dark_purple | 32      | 32            | ![](examples/dark_purple.png) | #AA00AA  |
| white       | 2       | none         | ![](examples/white.png)       | #FFFFFF  |
| gray        | none    | none         | ![](examples/gray.png)        | #AAAAAA  |
| dark_gray   | 264     | 128          | ![](examples/dark_gray.png)   | #555555  |

| modifier   | PT min. | JD min.      | example                    | sample command                  |
|------------|---------|--------------|----------------------------|---------------------------------|
| bold       | 384      | 365           | ![](examples/bold.png)     |
| italic     | 428    | 564 | ![](examples/italic.png)   |
| gradient   | 400    | 420          | ![](examples/gradient.png) | /nc gradient dark_red dark_blue |
| flag       | 520    | 664          | ![](examples/flag.png)     | /nc flag denim white dark_red   |
| alternating | 464     | 528 | ![](examples/alternating.png)   | /nc alternating black white  |

## Donator Namecolors (example showing whitelist configuration)
Donators may get special perks for namecolor selection, such as additional namecolors not every other player can have, or an instant access to colors that would require some PT or JD.

| color        | example                        | hex code |
|--------------|--------------------------------|----------|
| light_purple | ![](examples/light_purple.png) | #FF55FF  |

| modifier   | example                      |
|------------|------------------------------|
| italic     | ![](examples/italic.png)     |

# Acrylic Layer Case (by Litster)

This acrylic case for the ErgoDox was designed by Litster. The original link
for these files on the ErgoDox [website](http://ergodox.org/Downloads.aspx) is
dead, but I was able to find the design on github [here](https://github.com/bishboria/ErgoDox/tree/master/ErgoDox%20Acrylic%20Case/ErgoDOX%20Acrylic%20Case%20-%20Designed%20by%20Litster).

Files for cutting are provided in AutoCad DXF and SVG formats.

The layers can be cut from acrylic, or another material if you're feeling
adventurous. The thickness of the layers is as follows:

* Layer 1: 3mm
* Layer 2: 4.5mm
* Layer 3: 4.5mm
* Layer 4: 4.5mm
* Layer 5: 3mm

The top and bottom layers can be cut from thinner material if you desire. They
do not have a minimum height.

### Notes:

Depending on your components, some connectors on the PCB may conflict with the
spacer layers (2 and 4). During my build I found that the TRRS connectors on
each side were ~6mm tall, and as a result left a small gap above and below the
plate layer. This can be solved by using a file or dremel to cut a groove which
can fit the oversized connector. I do NOT recommend using thicker material for
layer 3.

# Joined Case Layers

Because I wanted an easy way to ensure that the two halves of my ErgoDox are
always oriented the same way, I created joined alternatives for the top and
bottom layers. It is possible to use only the bottom joined layer, or to use
both the bottom and the top for a more solid build.

The joined layers can be found in `case/dxf/joined/` or `case/svg/joined/`.

For layers 2 through 4 just use the regular, non-joined layers.

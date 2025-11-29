# Speeds and feeds

### Overview

- cutting speed(RPM) - how fast is it spinning
- Feed rate - how fast cutting tool is moving through the work
- proper speeds/feeds work to reduce heat and productivity ie tool life, accuracy, production
- heat kills cutting tools

### Units

- SFM - speed difference between cutting tool and surface of work piece (mill specific)
- IPR - inches per revolution for lathes
- IPM - when work piece does not rotate

### Measurements

- measurements should start with the thousandths ie:
  0.100 - one hundred thousandths
  0.010 - ten thousandths
  0.001 - one thousandths

- primarily heat will cause cutters to fail, however work hardening and material softening may occur

### Speed and feed info:

- tool manufacturer
- technical manuals
- charts and formulas

  `RPM (Revolutions Per Minute): RPM = (Cutting Speed [SFM] x 3.82) / Tool Diameter [in].`

  `IPM = RPM x Chip Load [per tooth] x Number of Teeth.`

  `3.82 is pi/12 for the inch conversion`

- ask an experienced machinist

### Heat management

- as cutting speed increases, heat generation increases
- maintain ideal heat range for both workpiece and tool selection
- as work piece gets harder, cutting heat increases

### Determining Speeds and Feeds

- work material
- tool material
- wanted surface finish
- tool geometry
- horsepower
- tool design
- work holding - as rigid as possible is the goal
  - work should stick out only as far clearance for last feature

### Info

- harder work pieces demand slower initial speeds
- material references only provide a starting point
- processes should be adjusted and optimized as you continue production runs

### Constanst Surface speed

- manual machines generally fixed during cuts
- cnc can adjust mid cut
- speed increases as tool moves closer to centerline

### Feed

- you should fist select the heaviest depth of cut, then select an aggressive feed rate then adjust
- higher feed rates have less effect on tool wear than higher speeds, however too aggressive can stall machines

### Mill

- IPM this is how far a tool travels in one minute (however its actually table travel)
- tool companies provide feed rates as "Feed per Tooth" (FPT) in inches
- FPT allows for generalized feed values

`IPM = RPM x FPT x # of Flutes`

# 0.4.2

  * [BUGFIX] proper page track when used with turbolink #40 (thx @remiprev @musaffa)

# 0.4.1

  * [ENHANCEMENT] support zanox mastertag and tracking events

# 0.4.0

  * [BUGFIX] store event objects as hashes so they can be safely serialized using JSON (default since rails 4.1) #13
  * added support for Google Analytics User ID feature #15
  * added support for Google adwords conversion #24
  * added support for Google Tag Manager feature #29
  * added support for Google Analytics custom metrics and parameters #31 (thx @mnin)
  * added support for Google Enhanced Ecommerce #32 (thx @mnin)

# 0.3.0

  * [ENHANCEMENT] google analytics cookieDomain renamed to cookie_domain

# 0.2.6

  * [ENHANCEMENT] rails 3 support

# 0.2.5

  * [BUGFIX] stringify google analytics event values to be api compliant

# 0.2.4

  * [ENHANCEMENT] support all the rack versions >= 1.5.2

# 0.2.3

  * [ENHANCEMENT] support all the rails versions >= 4.0.0

# 0.2.2

  * [BUGFIX] the tracker key got lost while merging multiple nested events into env

# 0.2.1

  * [BUGFIX] sending the ecommerce cart was misspelled

# 0.2.0

  * added support for GoSquared
  * added support for Visual Website Optimizer

# 0.1.3

  * [BUGFIX] ecommerce events weren't created properly

# 0.1.2

  * cart is now auto submitted to when ecommerce is turned on and items or transactions are in the queue

# 0.1.1

  * [BUGFIX] return value of the `tracker`-block is kinda unpredictabel, so we skip further processing

# 0.1.0

  * README
  * unified facebook and google handler `#track`-signature (3009b3834ad07caf8818484ddd86d8a0eb128fe5)

# 0.0.4

  * keep events over multiple redirectes
  * allow multiple calls of the same handler in one `tracker` block

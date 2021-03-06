# MSX-UNAPI examples

This directory contains some examples on how to implement an MSX-UNAPI specification in various scenarios:

* [unapi-ram](unapi-ram.asm): Implementation that installs in a mapped RAM segment.

* [unapi-rom](unapi-rom.asm): Implementation inside a plain ROM.

* [unapi-specless](unapi-specless.asm): Application that uses the concept of "specificationless implementation": it uses the UNAPI infrastructure to install as a TSR, but doesn't actually implement any API specification.

* [unapi-nextor](unapi-nextor.asm): Implementation that lives inside a [Nextor](https://github.com/Konamiman/Nextor) driver.

Please see the code of each example for details on how to build them and how to customize them for your own API specification.

You may want to take a look at [InterNestor Lite](https://github.com/Konamiman/MSX/tree/master/SRC/INL), [DenyoNet BIOS](https://github.com/Konamiman/MSX/tree/master/SRC/DENYONET) and [ObsoNet BIOS 1.2](https://github.com/Konamiman/MSX/tree/master/SRC/ONET) as well as examples of implementations of UNAPI specifications.

To see examples of API client applications see the [tools](../tools) directory.

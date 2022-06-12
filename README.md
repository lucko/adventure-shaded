# adventure-shaded

This repo contains a collection of Maven buildscripts which produce shaded "uber" jars  for the [adventure](https://github.com/KyoriPowered/adventure) and [adventure-platform](https://github.com/KyoriPowered/adventure-platform) libraries.

adventure is spread across many (over 15!) modules, each of which is distributed as a separate jar file. For my use cases, this is not desirable.

Most users will not care about this, and therefore should not use this.
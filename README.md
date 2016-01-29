# Swift Breeze

This is an experiment in response to a
[thread](http://thread.gmane.org/gmane.comp.lang.swift.evolution/4640)
on the swift-evolution mailing list.

Breeze is a community incubator for the Swift standard library.

## What goes in the Breeze?

Ultimately, any module that the community wants here. Upgrades
to older modules in the standard library. Additions that one day
will be added to the standard library. Other libraries where it's
valuable to have everyone using the same API but aren't quite
suitable for the general Swift distribution.

A complex number library is a classic example. A great many projects use
complex numbers. You might want to import one library for RF processing
and another for audio processing. If they use different implementations
of complex numbers then you're stuck doing a lot of copying or unsafe
casting.

## How do I participate?

Post your idea on the
[swift-users mailing list]
(https://lists.swift.org/mailman/listinfo/swift-users)
or
[swift-evolution mailing list]
(https://lists.swift.org/mailman/listinfo/swift-evolution).
If the response is generally positive, create an issue in this project.
Include a gmane link to the thread for reference.

For now, if it looks like there's two-thirds in favor, it will be so.
When there's a few projects here, the project leaders will create a
formal process by committee.

## Copyright Transfer

Each project is free to choose an open source license and assign copyright as
they see fit. But it must be done in such a way that copyright can be
transferred to the Swift project and possibly Apple Computer. This policy
will likely change as we figure things out.

---
layout: post
title: From Ports to Pantheons
date: 2025-11-12 11:19 -0600
description: The Theology of Interface Security
---

I don’t usually think much about the old days, when keyboards plugged in through PS/2 ports and data came off optical disks. I was born well after USB replaced both, and for most of my life I took the modern interface for granted—until I learned about the *Rubber Ducky*, a device that forced me to reconsider the “universal” in **Universal Serial Bus**, and the sins that universality carries along.

Similarly, few people spend much time thinking about Greek mythology anymore: those intricate tales of gods, demigods, and mortals, none of whom were all-powerful or all-encompassing. We only revisit them in English class or on a museum plaque. When in trouble today, people tend to turn to a single, almighty savior—a “Swiss Army knife” deity who can handle anything—unlike the old pantheons where intellect went to Athena, marriage to Hera, storms to Zeus or Poseidon, and so on.

The shift to monotheism simplified faith. It lowered the barrier to entry, consolidating spiritual power into one source of truth. The evolution of the USB port followed a similar logic: one interface to rule them all. It replaced a chaotic menagerie of ports with a single, all-purpose connector. Just plug and play, and the omnipotent USB will fulfill your wish—keyboard, storage, charging, you name it. Universality delivered users from the confusion of specialized connectors, much like monotheism delivered believers from the clutter of gods.

![The Pantheon](assets/new_lib/pantheon.webp)
_The Pantheon in Rome, once a temple to many gods, was later re-consecrated as a church devoted to one._

But universality has its price. The USB port is terrible at distinguishing what it connects to. Every device plugs into the same interface, so the computer must simply **trust** the device to declare what it is. Since a computer assigns different levels of trust to different kinds of devices, and the device gets to decide what the computer thinks it is, a loophole was born.

The Rubber Ducky exploits that very design. Disguised as an ordinary flash drive, it announces itself to the computer as a keyboard instead. And because the computer has no reason to doubt that claim (it’s plugged into a port that a generic keyboard would use), it grants the device all the privileges of a keyboard—essentially the same as the logged-in user. This means you can patch USB storage exploits all day long, but if the attacker simply “pretends” to be a keyboard, those defenses get entirely circumvented just like the Maginot Line. A computer cannot quarantine a keyboard without distrusting its own user. Universality, it turns out, makes faith mandatory.

What can theology teach us about that? Well, in the “old days” of separate ports, a storage device could never masquerade as a keyboard; the physical connection itself enforced boundaries. Likewise, in the Greek myths, Hermes could play tricks on the gods, but his mischief was bounded—each deity rules a different domain, and collapse of one domain can affect at most one aspect of mortals’ lives. In monotheistic systems, however, both divinity and devilry scale to totality, in that all three of the Abrahamic religions have a Satan figure that can wreak unconstrained havoc. When there is only one interface to the divine, trust becomes absolute—and betrayal catastrophic.

The Rubber Ducky didn’t hack its way into the system. It didn’t even break the rules. It simply took advantage of the structure we built: the faith-based architecture of universality. Just as monotheism inevitably conjures its Satan, a unified interface summons its exploit. If the good can do all, the bad can, too.

Still, it would be foolish to declare war on convenience. The story of both technology and theology is the story of simplification, of making the world more accessible. Unification is a triumph of design—but one that must be tempered with humility. Even Christianity, the archetype of monotheism, developed its own distributed safeguards: different saints for different cities, many patrons for many professions, a trinity instead of a single unblinking eye. In practice, it became a kind of managed polytheism.

Perhaps interface design could learn from that. Maybe we don’t need to abandon universality, but we shouldn’t be blind-sighted by its glistening promises. Because whether we’re building networks or pantheons, the same truth applies: every universal system demands faith. And faith, without structure, always invites a devil.

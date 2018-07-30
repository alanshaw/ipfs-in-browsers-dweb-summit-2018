# Easy?

# No not easy!
Browsers have been built to work with the centralized web since...forever

So there's all sorts of challenges,
with trying to get a browser to talk to another browser
_without_ talking to a server

...and we've doubley not made it easy for ourselves:
We're trying to build a full and complete implementation of the IPFS stack,
in JavaScript :o

# Feature parity
Not just an API client or a cut down light version.
Its a full implementation of the IPFS protocol.
Everything you can currently do with the implementation of IPFS built in Go.
You should be able to do the same with the JS implementation.

# Interop
And they should be able to talk to each other seemlessly
It shouldn't matter that it's built in JS or Go or PHP or whatever.
They should all work together.

# In browsers
...all in the web browsers
Which by the way includes:
* Desktop
* Mobile
* Electron

# This is the mountain we're climbing...
...and it feels like we're near the top

...and I know that because I can see AMAZING dweb apps starting to appear that are using JS IPFS directly in the browser.

# PeerPad
ok, so we made that one, but! it's rad
It's distributed collaborative document editing

# Paratii
Video streaming and curation. Built on IPFS and Ethereum

# Filenation
Decentralized WeTransfer

# DWeb Archive
The whole of the internet archive, decentralized

# awesome.ipfs.io
See MOAR awesome here

# Asplode
Don't let your mind asplode yet!

# Community!
What's even more super rad, is that,
We have a vibrant community! Many contributors, so much pull request!

# Weekly call
The core JS team has a weekly call where you can come and see our blurry faces.
Web Browsers and GUI WG have an IRC catch up.
EVERYONE IS WELCOME!
We would love to have you there - bring a demo, come say hi or just listen

# IN web browsers
But what if IPFS was actually IIIINNNN the browser?
I've been talking mostly about an implementation of IPFS that runs in the browser
What if it was a native part of your browser?
What if I could just put an IPFS hash in my address bar and get the content?!
URGH THE DREAM!?

# Brave
So, we made progress there!

We were talking to the Brave Browser people about a native integration and
realised the easiest way for us to do that would be to leverage the power
of browser plugins.

Companion is this ace web extension that brings your IPFS node into your browser.

# Brave pony
We had Brave serving content directly from a locally running IPFS via the
companion plugin.

# mozilla/libdweb

What's also exciting is what's potentially coming to Firefox to allow us
to do the same thing.

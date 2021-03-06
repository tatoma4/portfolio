.. title: Plastics Product Design
.. slug: plastics-product-design
.. date: 2017-01-04 13:07:20 UTC+02:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

Assignment
----------

In the course Plastics Product Design we were given the task to prototype a platform for the *Catchbox*. 
We were given complete freedom to implement any features that we felt were important for the user.
Due to wireless nature of the product, it had normal AA batteries to power the microphone.
We wanted to replace these with rechargeable batteries and include wireless charging into the platform.

----

Team
----

Our team consisted of two electrical, mechanical and chemical engineers.
I was responsible for implementing the charging system modification inside the *Catchbox* and on the platform.

----


Requirements
------------


Requirement for the charging controller inside the *Catchbox* was to be as small as possible.
Looking at all the existing solutions, they didn't fulfill this requirement.
I wanted to try my hand at implementing a small form factor printed circuit board for charging NiMH batteries.
For achieving small size, I had to use tiny surface mount components. 
I used a known design for the circuit and designed a PCB around it.
Little did I know about the requirements for the design when manufacturing the board yourself...

----



Manufacturing
-------------

I made around five different revisions of the board and etched them myself.
Manufacturing at home requires looser tolerances which I did not take into account.
Unfortunately one of the ordered parts was in incorrect QFN-package, which requires special hot air tool to assemble.
I didn't have access to one, but I tried assembling carefully with regular hot air tool.
This failed completely, because without soldermask the whole board around the component oxidized fully, rendering the whole board useless.


In the timeframe of the course I didn't manage to assemble working board.
Learning from the failure, I corrected the errors in the board design and ordered more suitable parts for hand assembly.
Then instead of manufacturing the board myself, I ordered it from a professional manufacturer. The finished circuit board is really small only 3x2cm.

----

Summary
-------

I failed a lot of times during the course because I took a bigger bite than I could chew.
In hindsight I should have picked up a prototype module of the charging board and just get the job done.
After that I could have iterated and worked more on minimizing the design when it's verified to be working.


**Things I learned:**

* Electronics design
* PCB design and manufacturing
* Prototyping
* Iterate often, fail fast!

.. thumbnail:: /images/ltc4060.png
.. thumbnail:: /images/circuit.png
.. thumbnail:: /images/catchboxproto.jpg
	:width: 901
	:height: 1600
	:scale: 20 %
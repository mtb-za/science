# Background
The Karoo is an area of great geological interest. There is also a possibility that it contains large quantities of gas, which may be commercially viable. Unfortunately, while the broad sweep of how the Karoo as a geological body operates is understood (mostly), the fine details are not known.
In order to make sensible decisions as to whether or not to go ahead with gas (or other) development, we need more information.

# Problem
Existing datasets are generally low resolution, so can not answer questions about fine details.
The data is not always easy to understand, especially in three dimensions. So while we know what is happening at surface, there are only foggy ideas as to what is happening as we go deeper.

# How to solve
NMMU is doing a broad research program within the Karoo, looking at a wide variety of things, in the hope of being able to answer some of the questions.
Techniques exist to image subsurface geometry - faults, dykes and sills.
Computer-based images allow for good exploration of 3D; we are no longer limited to working on paper, in 2D.
So, with a new dataset, focused on the Karoo, we can try to get some subsurface information.
We also need to make it easy to view the data, whether as blocks or pseudo-sections or whatever.

# Work so far
I have implemented some filtering techniques from the literature, mostly in two-dimensions.
I have also been driving up and down the Jansenville area getting permission from land-owners to fly over their land.
We have identified about 200 land parcels, with approximately 100 unique landowners. For individual parcels, we have signed permission on 141, with 21 that are just waiting for signatures. About 40 are still being contacted. We are being refused from flying over the remaining 8 parcels. Side note: this is really, really good going, actually.
## Writing
Written 2 and a bit chapters, which have been reviewed and are currently being revised based on that.

# Current work
We need to finish getting permission, since the survey will be getting off the ground in the next week or so. This also involves liasing with the people contracted to fly the survey. Currently this is the biggest block to moving forward.
## Other items on my plate right now:
Restructuring dissertation to flow better. A decent amount has been written, but the structure is a bit wonky still, and links from one section to the next need to be made better. Also working on chapter 3: ####
Setting up tests to ensure that filters are behaving correctly, according to the papers that developed them. For example, tilt filter should be +ive over a body, 0 at or near edge, -ive outside body. Testing this is correct with synthetic data, to ensure that I have not made a mistake in the maths somewhere.

# Next steps
Actually fly the survey, which will start as soon as the permissions are sorted out. This should take about 6 weeks.
Will start working out the transition into 3D, based on some filters that give you depth estimates as well as xy position.
Need to get going on front-end development, since the back-end is reasonably stable. Front-end will be fairly minimalist, to aid ease of use. Links to the back-end documentation's docstrings will help. This will include an approach to viewing things in 3D, which for this type of data has its own problems. A big one will be how to view things behind other things, while not suggesting that there is empty space.

# On track?
More or less, the survey has taken far longer to get off the ground than we anticipated (the permissions have taken about 5 months).
The filter implementation is fairly straightforward, and going well, although making sure that they are tested is sometimes being tricky.
Writing has gone ok, and should be in a good place in a week or two, once the document has been restructured. Expanding and reworking these aspects should be relatively standard.

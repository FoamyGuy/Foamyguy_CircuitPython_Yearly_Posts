### Reflecting on 2021

2021 was my second full year involved in the CircuitPython project. This year I branched out further than ever contributing to different aspects of the project. Previously I had stuck mostly to the python side of things contributing mainly to CircuitPythohn Libraries.

I took the dive into the C code and made my real contributions to the core. I also learned about some of the non-primary, but still very important, projects like: Cookie Cutter, Adabot, CircuitPython.org page, and the Library / Learn Guide screenshot maker. I picked up the skills needed to prepare for and script automated changes to large sets of library repos, including interacting with Github itself to make issues and PRs. 

A few contributions from 2021 that I am particularly proud of are:

- `bitmaptools.boundary_fill()` My first real core contribution that added new functionality.
- Typing Issues on Github. Automatedly created issues accross all library repos to add basic typing information to all functions. We are making great progress on them (hug report to @tekktrik, who has completed many of them)
- Library / Project Screenshot utility. My first time using PIL, it's proven to be a nifty utility that I've gone on to use in a few other unrelated projects.

My favorite project that I worked on in 2021 is the PyPortal Etch-a-Sketch: https://github.com/FoamyGuy/CircuitPython_Blink_A_Sketch

Capping off a great year with CircuitPython I joined the Adafruit team to work on the project part time.

### Looking forward to 2022

As we kick off 2022 I am quite excited about what lies ahead with CircuitPython. This year I'll be dedicating Monday's to work on the project. As of the time of this writing I've had 3 CircuitPython Monday's so far and am enjoying that arrangment a lot. I'm looking forward to many more this year.

Some of the things I'm hoping to accomplish personally in 2022 are:

- Get more comfortable making functional changes to the core. One that I have in mind is changing a few things to take file names instead of opened files. But I'm sure the year will bring other opportunities as well.
- Continue building out displayio helpers to make it easier to build rich GUI applications
- Gain more knowledge about bus device communication with the aim to be able to write drivers for new and existing breakouts
- Improve the information available on the `board` module in the stubs
- Get involved with working on the BLE workflow with a native Android app.

I think the main specific thing that I hope to see from the overall project in 2022 is to at least begin moving away from the usage of secrets.py file. WipperSnapper uses secrets.json and I think we do similarly in CircuitPython. It will be a large effort due to the volume of published material that suggests secrets.py. But Overall I think will be good for us to free up the possibility of a built-in subset of CPython `secrets` module.

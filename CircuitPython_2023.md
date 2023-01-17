### Foamyguy CircuitPython 2023

#### Looking back: 
    
2022 will always be a special year in my story, at the 
beginning of the year I began a schedule of working a 
full work day per week on CircuitPython. It has been an 
incredible year of learning, coding and contribution. I
did dive a bit deeper into my understanding of the core, and
did change, expand, and improve upon displayio as I set 
out to do in last year's post. Another thing I've been excited
by is seeing new folks entering the community and began
their journey of contributing to various aspects of the project.
In particular, seeing new folks contributing typing to
the libraries is great.

One of my biggest wishes from last year's post was for us to
start the ball rolling on phasing out the use of secrets.py 
for authentication and configuration variables. Huge hug reports
are in order for the core team and anyone who worked or contributed 
in the discussions about the .env and/or toml implementations. 
There is still much work ahead, but the groundwork has been laid
with this new module giving us a different way to achieve what
secrets.py did originally.

#### Looking Forward:

One of the things I mentioned last year, that I didn't end up
getting much into is native mobile app(s) for interacting with
CircuitPython devices. I have renewed, but slightly redirected 
interest in this for 2023. The web workflow built out an API 
foundation to view and edit files on the device, I think there 
are some interesting possibilities for mobile work flows that can be
built un top of this that I'd like to explore. I am particularly
interested in figuring out ways to make the files available to
other existing apps, there are many nice looking editing environments
on mobile, perhaps we can find the best way to use them with CircuitPython.

Another thing I'd like to explore further this year is using secondary 
microcontrollers for displays. Things like adding a Feather TFT 
to an existing project as a display only, communicating back
to the main device only as much as is necessary to know what to
show.

Beyond those, a goal I'm setting for myself this year is to 
try to build a few more physical projects. I tend to gravitate
towards digital and display oriented projects naturally, but
I would like to push outside that comfort zone a bit further. 
Being able to interact with physical things in the world is perhaps
my favorite part about making software for microcontrollers in
the first place so I'm happy to venture further into it.

More generally within the project this year I'm expecting to 
spend some time on deprecation changes after the next major 
release is out and stable. The displayio API for showing things
has changed and there will be lots of code that need a minor
update for it. I'm sure there are some I'm not thinking of, but
the other one that comes to mind is starting the shift away from
settings.py to using the toml file instead. 
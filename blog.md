# LLMs make great magicians.
###### (But not everything is a magic trick)
by Nicholas Bowen

An obscure 2020 youtube video containing two industry renowned creative professionals haunts my thoughts on the regular. Elburz Sorkhabi asks for Matthew Ragan’s “number one tip” for those starting their careers in that field. 
Matt’s response:

> The number one tip I would give people is to remember that in this industry especially; it's all a magic trick. There is nothing that we do that is perfect or real or any of these kinds of notions that we often hold on to. Even in the client conversations that I have, we are ultimately in the business of crafting an experience that is an illusion. And so if you have to beg, steal, or borrow your way to get there then that's what it takes to get there. I wish that I had thought about those ideas earlier on because I've chased my tail in so many different circumstances looking for perfect simulations or the "right" or "legit" way to approach a problem or the perfect solution. For you know for any number of things and really it's like if it gets the job done, it gets the job done. If it's bubble gum and gaff tape but it gets you past the finish line then it got you past the finish line. I think that's pretty good advice.

Now, I don’t expect everyone reading this to know who these two are, as it’s quite specific. But the Youtube channel the quote is from is devoted primarily to TouchDesigner. I have always been partial to the following description from an org called the Node Institute.

> TouchDesigner will allow you to connect “everything to everything” in the digital media world. Everything that can be digitised can become an input to a TD application and everything that can be controlled digitally can be output from TD. It allows you to build your own, specialised applications which again allow you to do things that may be impossible with standard creative tools like the Adobe ecosystem.


In my opinion, this description, combined with Matthew’s advice explains what makes it one of the most top of the line tools for this. To me it’s like nothing else. I credit my journey with it with making me a better engineer, artist, and problem solver.

 I am currently down in Portland as a part of the winter lights festival helping my friend and collaborator, Rich Martin. He is a wizard of a different arcane school than I, delving into the terrifying energies of **C++**, electrical engineering, metal fabrication, welding, and production design. I am mostly tasked with showing up to do the fun part. Throwing pretty colors on his painstakingly crafted monuments to light and steel. Unfortunately, a critical pipeline to connect my spell book was severed. The Art I brought with me requires far more mana that a Teensy 4.1 would be able to handle. Worse, the controller that died was entrusted with the star of the installation, a 4000 led volume in the dead center of the display, right at the front of the show when guests walked up. 

Rich waged a hard fought battle to reestablish the bridge without success. I decided to give him some space, grab a bite to eat, and come back. When I returned, his friend said he went to sit in the uhaul. He was sitting on the passenger side glued to his phone. I gently knocked on the door, and he let me in. Understandably a bit demoralized, I decided to give him a minute and sat in silence next to him for a bit. Having just moved the weekend before, I cracked a joke to lighten the mood. “Didn’t expect to be behind the driver’s seat of a moving truck again so soon, but here we are”. He laughed.

Then I started to ask him some questions. In the back of my head was that advice from Matt. “It’s just a magic trick, no one gives a shit if the cool even TD bridge exists but us. Bubble gum and gaff tape is the name of the game” We dug down into the setup, and went back and forth. After about 5 minutes Rich’s demeanor suddenly changed, I witnessed the light bulb the moment it went on. He burst into action. We just needed to build a generative program that could run on the teensy itself and forget the bridge entirely.

We spent the next 90 minutes frantically commanding claude code and digging up old examples. We must have flashed that board 30 times. The light show staff knew we were having a hard time and would occasionally check in, they were rooting for us but obviously had no way to help. When the first working pattern flashed on they cheered and clapped. Once we got going, I could barely peel myself away, we were one of the last people to leave that night. Using straight prompts and Ralph Wiggum loops we not only got it working, it looked good, as good as anything my TD skills could have produced. 

In creative technology shows, everything is a magic trick. That time you spend public facing, the gaff tape is invisible. But if you distribute your code to others, the adhesive will not carry the weight forever. Making great tools you can depend on in the long term, sell to others, etc, is software engineering through and through. Building dependable software is not magic, it is craft. Chris Gregori recently wrote that I feel echoes this, its called “Code Is Cheap Now. Software Isn’t. The barrier to entry for building software has collapsed. The barrier to building something that matters hasn’t moved an inch.”
Chris is writing this in the context of the greater software context, which matters a lot here. When you are building software for the sole purpose of “Illusion” and artistic ends, then Claude Code might be truly one of the most valuable things for any creative technologist to learn. If you are building “Software”, then the parameters are just different. This isn’t to say that companies utilize their own magic tricks. 
Some of the biggest names in tech rely on a lot more necromancy than most would ever realize. Services you rely on are held together with zombie scripts that no one wishes to, or needs to do surgery on. If it ain’t broke, don’t fix it. If the script works and it’s meant to run once, who cares if you had to endure the stench for 30 seconds? Even regularly run jobs are fine for some artisanal necrotic jank now and again. I just hold my nose on when Gary the ghoul makes his regular pass into the office every other Tuesday. 

Prototypes are also relevant. If you get your unholy canvas “fresh” enough before initial animation, just give it a quick spray with the hose, hire a makeup artist, apply old spice generously, and throw some nice clothes on it. No one will be the wiser for the demo. But I must encourage caution in this approach, for this is a delicate gamble. Many codebases meant to be but to rest often end up in prod, before you know it decay will set in and then you’ll be in deep. Do this enough times the delirium will be having you considering relocating to a new tower, or worse, considering lichhood. 


This is not meant to be a wholesale rejection of agent use in production, quite the contrary. It’s meant to encourage you to really set proper expectations with yourself and others. To know the limits and strengths of the agents, but more importantly, yourself. There was a lot of technical and artistic intuition that just was absolutely needed to fix that nightmare. It was more of a story of Rich and I's problem solving, with claude code coming in very, very, clutch to. produce code faster than our hands could feasably move. One thing I know for certain, The smell in the office of an non-technical founder vibe coding an app must be unbearable. I have no interest in attempting to imagine it. But if I had to take a guess, I'd guess something akin to Paris, France in 1780.

#### P.S.A
An even more horrible part of this story than dead electronics was that Rich’s Truck got stolen early on Thursday morning. The prime suspects are currently the notorious **Portland Thieves Guild** known far and wide for their wanton harvesting of catalytic converters for use in black market alchemy. If you or someone you know is a diviner please reach out to nick@offlineartisan.com 

Sources:
TouchDesigner Tips with Matthew Ragan
https://www.youtube.com/watch?v=5UBC8kfWf-k
What is TouchDesigner and why should I use it?
https://thenodeinstitute.org/courses/introduction-to-visual-programming-with-touchdesigner/lessons/what-is-touchdesigner-and-why-should-i-use-it/
Code Is Cheap Now. Software Isn’t.
https://www.chrisgregori.dev/opinion/code-is-cheap-now-software-isnt


# Design Direction: The Weird Parts

![](../.gitbook/assets/iceberg.png)

**I recently started teaching Interaction Design at the** [**Creative Academy**](https://creativeacademy.ac.za)**, a tertiary-level design school situated in** [**Cape Town, South Africa**](https://en.wikipedia.org/wiki/Cape_Town)**.**

It's been a couple of years since I started my journey into the world of web design, and in the context of the former, I started retracing some of my steps. This included, amongst others, rummaging through several bookcases in search of a dusty [Don't Make Me Think](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515) by [Steve Krug](https://en.wikipedia.org/wiki/Steve_Krug) and \(the more recent\) [Atomic Design](https://shop.bradfrost.com/) by [Brad Frost](https://bradfrost.com/). I also went back into history, re-reading some seminal [Smashing Magazine](https://www.smashingmagazine.com/) and [A List Apart](https://alistapart.com/) articles.

Given that it's been almost a decade now, I was \(perhaps reasonably\) anticipating that most of the material would age quite poorly. To the contrary, I was surprised by the degree to which it still holds up. One thing I didn't anticipate though is how my own experiences over the last couple of years would shape how I would re-read them. Some sections and paragraphs that I glossed over initially ended up being treasure troves of insight this time around. The most prominent was perhaps the introductory paragraph to [Style Tiles and How They Work](https://alistapart.com/article/style-tiles-and-how-they-work) by [Samantha Warren](http://samanthatoy.com/) \(current _Director of Design_ at [Adobe](https://www.adobe.com/)\):

> _When you engage in a new client project how do you get started? A solid process plays a critical role in the project’s overall success, yet this process is one of the deepest darkest secrets of our industry_.
>
> — Samantha Warren, [Style Tiles and How They Work](https://alistapart.com/article/style-tiles-and-how-they-work)

My time in the industry shaped my appreciation for the ease with which a robust design process can derail. Furthermore, I also came to understand how much of the former is due to a designer \(or design team\) not fully stepping into the facilitator role.

### A Facilitator's Interface

**At some point, I had a naive expectation that a designer's job would be purely technical.** 

Over time I've come to realise that modern-day web designers are not only designing external-facing deliverables, but also internal-facing artefacts intended to help the client \(or team\) navigate the design process itself. I also became aware of how anaemic this part of the process tended to be. From what I've been able to piece together at that time it seemed to come down to a misconception of designers as solitary, creative creatures that disappear into their respectively little caves \(or perhaps cubicles\) and re-emerge with a creative masterpiece.

I've over-dramatised the above for comedic effect. In practice, the former tends to plays out more subtly. To quote [Adam Connor](http://adamconnor.com/) and [Aaron Irizarry](https://www.linkedin.com/in/aaroni/) from their seminal [Discussing Design](https://www.oreilly.com/library/view/discussing-design/9781491902394/) \(2015\):

> _What individuals and organizations that fall into this trap fail to realize is that when a project is tasked with making something, no matter what it is, every single team member is a part of the design process. Design doesn’t just happen in the design department. It happens with every decision about what will or won’t be part of the final product, whether that’s a feature, a paragraph of content, a color pallet, a user interface pattern — anything._
>
> _\[...\]_
>
> Collaboration and coordination are critical elements in the success of projects in most \(if not all\) modern organizations. There isn’t a single individual who is responsible for coming up with an idea, designing it, building it, selling it, and supporting it. Instead, these responsibilities and the expertise that come with them are divided among a variety of contributors who each bring knowledge to the team. So, we need to work together, combining our skills and know-how. And to work together, we need to talk with one another. We need to discuss what it is we’re designing, why we’re creating it, and how it will all come together.

Luckily for me, it appeared as of change was on the horizon.

I started seeing teams catch onto this notion. [Personas](https://en.wikipedia.org/wiki/Persona_%28user_experience%29), [experience maps](https://en.wikipedia.org/wiki/User_journey) and [user stories](https://en.wikipedia.org/wiki/User_story) started becoming the rule rather than the exception. In my own microcosm at OpenUp, it seems unreal how easily we were able to persuade  [South Africa's National Department of Treasury](https://openup.org.za/projects/vulekamali), a government department known for its layers of bureaucracy, to approach work in this manner.

**Indeed the language of user-centred design has become mainstream.**

However, I couldn't help but feel that we still missed one piece of the puzzle: a deliberate and calculated way in which to iterate and discuss stylistic \(otherwise known as look-and-feel\) concerns. More often than not conversations about stylistic decisions were preceded by designers retreating behind their magic-creative-curtain, while re-emerging with beautifully styled interface elements. We were lucky enough to have the incredibly talented [Matthew Stark](http://matthewstark.co/) on board, which means that more often than not, we landed firmly on our feet. However, I couldn't shake the feeling our approach ended up coming down to a sprint-long leap of faith before we had something to start talking about.

In short, it went something along these lines:

1. Have an initial discussion that included a lot of my branding-speak bingo: 'Respected', 'Playful', 'Modern', 'Friendly', 'Classic', 'Trustworthy', 'Professional' or 'Delightful'.
2. After some time, designers would then present a general look and feel they feel represent these adjectives.
3. If the latter didn't quite hit the mark, then the process repeated.

It felt like we were continually being teleported between the meticulous world of content/structure and the fuzzy world of style.

### Design as Remixing

**The above might sound a lot like your own approach.**

You might even tell me that this process works very well for you.

The sheer scope and plurality of approaches in the current web design landscape are so far beyond what a single person can comprehend. I don't claim to have any insight into the one-true process that works for everyone. The risk associated with the above in your context might be so small that rethinking your design process might event result in a negative return on investment. There is a big difference between getting the general look-and-feel wrong of a personal blog and getting the look-and-feel wrong of a governmental's public data portal.

It might also be that you are already working inside well-established stylistic confines. Perhaps you are part of a large corporate brand that already has a well thought-out design system, style guide and pattern library.

**I short: web design heaven.**

However, for the rest of us that are still stuck in web design purgatory, there should be probably numerous discussions on this topic? Right?

 **Wrong.**

When compared to discussions around the structure of digital products, the discourse around establishing a look-and-feel seem barren. Luckily, it's not completely missing. You just need to do some digging. In my experience, these folks tend to talk about it somewhat:

* [Dan Mall](https://danmall.me/)
* [Andy Clark](https://stuffandnonsense.co.uk/about)
* [Brad Frost](https://bradfrost.com/)
* [The Clearleft Team](https://clearleft.com/)

However, an interesting observation that I made while researching this topic is that those that tend to talk about this part of the design process also tend to be big advocates of [designing in the open](https://bradfrost.com/blog/post/designing-in-the-open). I can only speculate. However, my guess would be that at the root of this problem of designers not wanting to discuss/share about the look-and-feel part of their process is that it is rooted in insecurity. In my opinion, it highlights something that is at odds with the common understanding of designers as shared above. In short:

As creative creatures that disappear into their respectively little caves and re-emerge with a creative masterpiece. The implication being that these creatures are able to wield some hidden black-magic in order to conjure a vision from the nothingness of a blank screen or canvas.

My persona experience is a bit at odds with this. All designers, but web designers specifically, are deeply embedded in what anthropologists like [Claude Lévi-Strauss](https://en.wikipedia.org/wiki/Claude_L%C3%A9vi-Strauss) would call [bricolage](https://en.wikipedia.org/wiki/Bricolage):

> _"This is what is commonly called ‘bricolage’ in French. In its old sense the verb ‘bricoler’ applied to ball games and billiards, to hunting, shooting and riding. It was however always used with reference to some extraneous movement: a ball rebounding, a dog straying or a horse swerving from its direct course to avoid an obstacle. And in our own time the 'bricoleur' is still someone who works with his hands and uses devious means compared to those of a craftsman. \[...\]_
>
> The ‘bricoleur’ is adept at performing a large number of diverse tasks; but, unlike the engineer, he does not subordinate each of them to the availability of raw materials and tools conceived and procured for the purpose of the project. His universe of instruments is closed and the rules of his game are always to make do with ‘whatever is at hand’, that is to say with a set of tools and materials which is always finite and is also heterogeneous because what it contains bears no relation to the current project, or indeed to any particular project, but is the contingent result of all the occasions there have been to renew or enrich the stock or to maintain it with the remains of previous constructions or destructions._"_
>
> — Claude Lévi-Strauss, [The Savage Mind](http://web.mit.edu/allanmc/www/levistrauss.pdf) \(1962\)

**That is quite a mouthful!** 

Luckily, [Austin Kleon](http://austinkleon.com/) paraphrases it as follows in his New York Times Bestseller title, [Steal Like an Artist](https://austinkleon.com/steal/) \(2012\):

> _The writer Jonathan Lethem has said that when people call something “original,” nine out of ten times they just don’t know the references or the original sources involved. What a good artist understands is that nothing comes from nowhere. All creative work builds on what came before. Nothing is completely original._
>
> _\[...\]_
>
> _If we’re free from the burden of trying to be completely original, we can stop trying to make something out of nothing, and we can embrace influence instead of running away from it._

**In short:**

Not only do I see the way towards a more deliberate process around style/look-and-feel as being embedded in approaching web design as remixing, but that it furthermore requires us to have the courage to expose this hidden part of the process to our peers and clients.

![](../.gitbook/assets/messy%20%281%29.png)

### Manoeuvres with Black Markers

It is perhaps interesting to note that Austin Kleon, initially made a name for himself by creating [Vocabularyclept poems](https://en.wikipedia.org/wiki/Vocabularyclept_poem). A technique initially devised by early [Dadaists](https://en.wikipedia.org/wiki/Dada), in which a series of poems are assembly with existing textual content from newspaper clippings or even existing literature. Late Beat-era poet, [William S. Burroughs](https://en.wikipedia.org/wiki/William_S._Burroughs), really pushed this concept to its limit with a 336-page work of fiction titled [The Soft Machine](https://en.wikipedia.org/wiki/The_Soft_Machine) \(1961\). Both Kleon and Burroughts, in creating these works, bring to the forefront not only how central bricolage is to the act of creation, but that selecting what to leave \(by the act of cutting itself\) is equal in centrality. As Mark Twain elequently put it:

> Writing is easy. All you have to do is cross out the wrong words

I would say that establishing a look-and-feel direction is easy, you just need to cross out the wrong directions. Brad Frost further remarked that the process of web design is similar to the subtractive process of sculpting: 

> I believe a successful digital design process is quite similar to subtractive stone sculpture. At the beginning of the sculpting process, the artist and their patron have a general idea of what’s being created, but that vision won’t be fully realized until the sculpture is complete.
>
> The sculptor starts with a giant slab of rock and starts chipping away. A crude shape begins to form after the first pass, and the shape becomes more pronounced with every subsequent pass. After a few rounds of whacking away at the rock, it becomes clear that the sculptor’s subject is a human form.

I've shared this anologue with various practitioners and students over the years. It has served me extremely well. The critical implication \(once again\) being that similar to the sculpture we should start with broad strokes of negation \(or as Brad put it "whacking away at rock"\). However, I always felt that there might be a better analogy, since the above doesn't make provision for process artefacts. That is until I stumbled across an analogue that does allow this:

**The game of** [**Battleship**](https://en.wikipedia.org/wiki/Battleship_%28game%29)\*\*\*\*

![Source: Alibaba.com](../.gitbook/assets/htb1a.e9e5lak1rjszfxq6ympfxa3.jpg_350x350.jpg)



If you're not familiar with it the rules are as follows:

* Each player starts with two grid-based surfaces:
  * One to place your ships and record which \(and where\) your own ships have been hit
  * Another to record your own shots against the other player \(and whether they missed or hit\)
* Players take turns to fire shots by guessing coordinates where they think the other player's ships might be placed \(for example `E2` or `H7`\)
* If you guessed correctly you add a red pin, if you guessed incorrectly you add a white pin.
* The first one to sink all of the other player's ships wins.

### Placing our Pins

This might seem a bit antagonistic, especially when talking about clients or the marketing team.

![](../.gitbook/assets/line.png)

### Helpful Resources

...

### A Word of Warning

...

### Further Reading

...










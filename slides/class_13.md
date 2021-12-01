This page intentionally left blank. ⬇️, ➡️, or spacebar 🛰 to start slidedeck.
---
class: center, middle

# Welcome to Class 13!

- this is a stressful time on top of a stressful time

![](./img/bgstar.gif)

---
# Agenda

- Housekeeping
- Questions?
- News of the Week
- Break!
- Readings
- How things all come together
- Tech stacks
- Break!
- Digital preservation


---
## Assignment questions?

### Other questions?

---

## News of the Week

Drop a link on the etherpad:
<https://etherpad.wikimedia.org/p/prattsi654fa21-13>

---
class: middle, center

# Break!

---
# Readings

- c.2016. Karen Coyle. [Catalogs and Context](http://kcoyle.net/catcon.html) (39 min)
- Current. Digital Preservation Coalition. [Digital Preservation Handbook](https://dpconline.org/handbook) (Read "Introduction" "Technical solutions and tools" [you can skip over the "Resources" sections in each])
- 2017-12-15. Lauren J. Young. [ScienceFriday: Ghost in the Reels](https://apps.sciencefriday.com/data/ghosts.html) (13 min)
- 2019-02-07. David Rosenthal. [Cloud For Preservation](https://blog.dshr.org/2019/02/cloud-for-preservation.html) (34 min)

---
# Bringing all of this together...

- Catalogs
- Content Management Systems
- Collection Management Systems
- Digital preservation
- Tech infrastructure

---
# First, tech infrastructure

- Questions about this, things that are still confusing?
---
# Sides

Do you know what these terms mean?
- "Client-side", "server-side"
- "Backend", "Frontend"
---
# Tech "stacks"

![](./img/techstacks.png)

---
# Examples
Do you know about...
- a [LAMP](https://en.wikipedia.org/wiki/LAMP_%28software_bundle%29) stack?
- a [JAM](https://jamstack.wtf/#what-is-jamstack) stack?
- ["full stack JavaScript"](https://www.smashingmagazine.com/2013/11/introduction-to-full-stack-javascript/)

---
# AWS

Amazon kinda has their own complex infrastructure, too

![](./img/aws-diagram.webp)

---

# AWS

Perhaps you've heard the term `serverless`

What does `serverless` mean in this context?


---
# How do websites get built?

![](./img/fancy-horse.gif)

---
# Content Management Systems

--

![](https://www.codeproject.com/KB/showcase/KenticoCMS/schema.gif)


---

# Content Management Systems

## Separation of content, logic, and data

---

# Content Management Systems

The basics:
- Display of information
- Storage of information
- Interface for editing information


---
# Content Management Systems

Next levels of functionality:
- Multiple files (potentially millions and up…)
- Multiple users
- Access levels by user
- Images as well as text, and then other media types
    - Multiple data types
    - templates and other custom  according to data types
- Searchability
- Version control


---
# Content Management Systems

What it boils down to:

- Efficiency
- Flexibility
- Collaboration


---
class: center, middle 

# 🖲 Digital Preservation 🌀

---

# 🖲 Digital Preservation 🌀

![](https://blogs.loc.gov/thesignal/files/2012/03/crudewf.jpg)

---

# 🖲 Digital Preservation 🌀

![](https://blogs.loc.gov/thesignal/files/2012/02/nz_lifecycle.png)




---
# Digital Preservation 

"Digital Preservation means sourcing computer-based material that is worthy of preservation, getting that material under control, and then maintaining the usefulness of that material, forever."

["Elevator Pitch" from Dave Gerrard @ DPOC](http://www.dpoc.ac.uk/2016/12/06/digital-preservation-is-a-mature-concept/)

---
# What is Digital Preservation? 

The previous statement seems to use these following four words as a guideline:  
- Acquire 
- Curate 
- Control 
- Maintain 

---
# What is Digital Preservation?

The National Digital Stewardship Alliance (RIP) uses the following four words as a guideline:  

- Protect 
- Know 
- Monitor 
- Repair 

---
# Library of Congress Digital Preservation steps

- Identify (your digital content)
- Select (what portion to preserve)
- Store (long term)
- Protect (from threats / emergencies)
- Manage (and implement requirements)
- Provide (access over time)

[Digital Preservation Outreach & Education](http://digitalpreservation.gov/education/curriculum.html)

---
# What is Digital Preservation?

Meanwhile, OAIS, often used as a baseline for creating preservation systems, has six primary functions:  

- Ingest 
- Archival storage 
- Data management 
- Administration
- Preservation planning 
- Access

---
# What is Digital Preservation?

[The Theory and Craft of Digital Preservation](https://osf.io/preprints/lissa/5cpjt) arranges concepts by:  

- preservation intent and collection development
- managing copies and formats
- arranging and describing content
- multimodal access

---
# What is Digital Preservation?

Well, what does [Wikipedia](https://en.wikipedia.org/wiki/Digital_preservation) say, then? 

"In library and archival science, digital preservation is a formal endeavor to ensure that digital information of continuing value remains accessible and usable. It involves planning, resource allocation, and application of preservation methods and technologies, and it combines policies, strategies and actions to ensure access to reformatted and "born-digital" content, regardless of the challenges of media failure and technological change. The goal of digital preservation is the accurate rendering of authenticated content over time." According to the Harrod's Librarian Glossary, digital preservation is the method of keeping digital material alive so that they remain usable as technological advances render original hardware and software specification obsolete.

---
# What is not Digital Preservation?

**More than just "backing things up."**

Storage is just one aspect (although a very big and important one) of proper digital preservation. This can be the hardest to convey when discussing digital preservation planning in the framework/context of IT teams. 

---
# What is not Digital Preservation?

**More than just hard drives.**

"Digital" is found in more places than just computer storage drives.

---
# Threats 

The seminal article [Requirements for Digital Preservation Systems](http://www.dlib.org/dlib/november05/rosenthal/11rosenthal.html) classifies the following threat categories: 

- Media Failure
- Hardware Failure
- Software Failure
- Communication Errors
- Failure of Network Services
- Media & Hardware Obsolescence
- Software Obsolescence
- Operator Error
- Natural Disaster
- External Attack
- Internal Attack
- Economic Failure
- Organizational Failure

---
# Threat aversion 

And, how to avoid the threats: 

- Replication
- Migration
- Transparency 
- Diversity
- Auditing (everywhere)
- Economy (all the time)
- "Sloth" (accepting slowness in the process)

---
# What is Digital Preservation?

The Wikipedia page on this subject is pretty good, robust and clear, so I will use the framework collectively concluded-to to give an overview.  

- Appraisal 
- Identification 
- Fixity
- Characterization
- Sustainability
- Authenticity 
- Access 
- Preservation 

---
# Appraisal 

Humans are producing massive amounts of digital content. What is worth acquiring, caring for, preserving? This is much more relevant for digital preservation than it was for traditional preservation.

# 💵

---
# Identification 

Identify files you have (technical metadata) as well as the significance of the content within them (descriptive metadata).

See [Analysis Tools]({{ site.baseurl }}/presentations/other-analysis-tools.html) for more information about this topic. 

# 🔬

---
# Fixity

See [Fixity]({{ site.baseurl }}/presentations/fixity.html) for more information about this topic. 

# 🔨

--

## What is a checksum? 

These are defined sometimes as "digital fingerprints."

I think this word is heard quite often but not well-explained or well-understood, but the absolute essence of a checksum is just a "random" string... sorta. At least that is what it looks like, and underneath it is a complex algorithm that is able to compare your file to itself-from-the-past. 

What matters is that that string is the same now as it is later in the future and as it was before in the past.

--

Also critical: this is a one-way transformation!


---
# Characterization

What is the essence of the material? What are the technical characteristics? What are the "Significant Properties"?

# 🤠

---
# Sustainability

Are the objects useable now, and will they be in the future? What are the risks?  

Digital objects may have to be modified or transferred to different formats -- will that be okay?  

Are the aforementioned "Significant Properties" suitable for this kind of migration for preservation? Are there issues of physical or digital format obsolescence? What is difficult about these digital objects?

# 🗻 

---
# Authenticity 

Are the files what they say they are? This should be derived during acquisition during the identification and fixity phases, but routine maintenance and checkups are important.

# 🕰

---
# Access 

Preservation is useless without access. 

# 📲

---
# Preservation 

Finally, at the heart of it all, is preservation. Through all of the above and beyond, how can files be ensured to be stored for long-term safety and integrity?

# 🔒

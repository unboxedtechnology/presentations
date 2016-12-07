#HSLIDE

# Presentations Using Git Pitch

Rick Beddard - 2016.12.07

#HSLIDE

## What is Git Pitch?

A service that turns GitHub (or Bitbucket) repositories into interactive slideshows

#HSLIDE

## OMG! Not another presentation tool!!
That was my initial reaction <!-- .element: class="fragment" -->

Get the tool out of the way and focus on content <!-- .element: class="fragment" -->

#HSLIDE

## Why should I consider it?
- You're a Git ninja (Whassup Terry!) <!-- .element: class="fragment" -->
- Markdown <!-- .element: class="fragment" -->
- Cloud <!-- .element: class="fragment" -->
- Responsive <!-- .element: class="fragment" -->
- Collaboration <!-- .element: class="fragment" -->
- Themes <!-- .element: class="fragment" -->
- History <!-- .element: class="fragment" -->
- It doesn't suck (PowerPoint? KeyNote?) <!-- .element: class="fragment" -->

#HSLIDE

## What can it do?

- Horizontal and vertical <!-- .element: class="fragment" -->
- Text <!-- .element: class="fragment" -->
- Images / Video <!-- .element: class="fragment" -->
- Code / GIST <!-- .element: class="fragment" -->
- HTML <!-- .element: class="fragment" -->
- Fragments <!-- .element: class="fragment" -->

#HSLIDE

## But wait! There's more!!

- Promote using a GitHub badge
- Embed in a blog or website
- Share on Twitter, LinkedIn, Facebook, etc.
- Print as a PDF
- Download and present offline
- Much more...

#HSLIDE

## Quick Demo
https://gitpitch.com/gitpitch/gitpitch

Full feature demo: https://gitpitch.com/gitpitch/kitchen-sink

#HSLIDE

## How does it work?

- Slides in PITCHME.md
- Bootstrap and Reveal.js
- Play Framework 2.5x

#HSLIDE

## Let's try it out!

Roll up your sleeves and let's get busy!

#VSLIDE

Clone the example repository

```bash
git clone git@bitbucket.org:unboxedtech/devtalk-gitpitch.git
```

#VSLIDE

Create a branch for your presentation

```bash
cd devtalk-gitpitch
git checkout -b <your name>-sample-prez
```

#VSLIDE

Create the required PITCHME.md

```markdown
Whassup, Git Pitch!
```

#VSLIDE

Commit your changes

```bash
git add . && git commit -m "Created PITCHME.md" && git push
```

#VSLIDE

Have a look at your presenation by going to: http://gitpitch.com/unboxedtech/devtalk-gitpitch/name-of-your-branch

Change the source repository type to Bitbucket (lower left of browser window):

![Bitbucket Selection](images/bitbucket.png)

#VSLIDE

Add a slide in PITCHME

```Markdown
#HSLIDE
Whassup, Git Pitch!
#HSLIDE
The End
```
Commit your changes and refresh to see the updated prez

#VSLIDE

Add a vertical slide in PITCHME

```markdown
#HSLIDE
Whassup, Git Pitch!
#VSLIDE
Bring on the kittens!
![kitten](images/kitten.jpg)
#HSLIDE
The End
```
Commit your changes and refresh to see the updated prez. Notice you can now navigate down from the first slide.

#VSLIDE

#### That's it. What did you think?

#HSLIDE

## Questions?

#HSLIDE

## References

- [Git Pitch](http://www.gitpitch.com)
- [Git Pitch Wiki](https://github.com/gitpitch/gitpitch/wiki)
- [Git Pitch GitHub Project](https://github.com/gitpitch/gitpitch)
- [Play Framework](https://playframework.com/)

#HSLIDE

## About the Author

Rick Beddard is a Technology Aficionado (yes, I had to look up that spelling) located in Richmond, Virginia. He spends his days changing lives through his work at Unboxed Technology and his nights pursuing highly important endeavors such as being a husband and father.

#HSLIDE

(This page left intentionally blank. Except that it's not. Blank, that is.)

#HSLIDE

## The End

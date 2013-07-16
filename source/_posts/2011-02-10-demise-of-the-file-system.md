---
layout: post
title: The Irrelevancy of the File System
---

In speaking about [the simplification of computing][toto-simp], I touched briefly on the matter of the file system, and how Apple has been making it increasingly less relevant on their mobile platform. I'd like to expand on this topic some more.

[Alex King][king]:
> Apple’s iOS devices are treating files like historical artifacts that users should be protected from while popularity surges for Dropbox's file sync service.

Files **are** the historical artifacts of a dying metaphor: the office cabinet. When computing was nascent, rooting metaphors in the physical world made the barrier to entry significantly lower for office workers, who were the primary audience after computers left the research labs, and before mass home adoption was even remotely considered. It made practical sense to model the New after the Old, so we ended up with virtual files and the folders that contain them.

Four decades later, it's high-time for a change.

The file system's biggest problems are clutter and the difficulty of retrieving information. Clutter happens because of applications and the operating system, and the completely unnecessary 'feature' of being able to navigate to those locations. On that topic, [André Pang comments][pang]:

> I think the fundamental problem is that Windows Explorer, Finder, Nautilus and all the other file managers in the world are designed, by definition, to browse the filesystem. However, what we really want is an abstraction level for users that hides the filesystem from them, and only shows them relevant material, organised in a way that’s sensible for them.

I completely agree: users only care about their data. The other files and folders either confuse or annoy, and sometimes find their way into the great big void of the Trash can / Recycle Bin, only to subsequently reappear after the required software or operating system reinstall. I would say it's almost insulting to show users things they aren't meant to understand, yet the vast majority of the file system is just that. Out of over 1.5 million files that I can currently *see* on my computer, I care for about 100,000, and that's including plenty of source code. Average users care for about however many files you can count on their desktop. But on my iPad? I care about every single thing.

Information retrieval is a different problem, one not resolved entirely by search. The Google model applies very well when one is trying to find new information, but it breaks down (sometimes in hilarious ways) when it comes to retrieval. People just keep things on their virtual desktop until it, too, becomes as inscrutable as the rest of the file system.

To help users in both of these situations, Apple has added a layer of abstraction in iOS, as [Rob Foster points out][foster]:

> Apple is doing something rather daring with their new iPhone OS. They are essentially omitting features that people once took for granted in a typical computer. And one of the biggest things they’ve omitted is the visual file system. Instead, in the iPhone OS, the concept of the file is essentially gone. It’s been replaced by "apps and their stuff."

I hope a lot (more) of this goes back to the Mac.

## The Everything Buckets ##

There have been a series of articles from the very smart [Alex Payne][al3x] and [Shawn Blank][blanc] chiming in on the issue of Everything Buckets. In brief, applications like [Yojimbo][] and [Evernote][] are popular because they allow people to store all their documents in one place. But isn't that what the file system itself is supposed to provide? After all, the whole metaphor revolves around hierarchical organization of information via folders and files… But it doesn't work anymore. User data is piled on their virtual desktops, or tucked away into some kind of personal information organizer/manager. These everything buckets really are nothing more than an additional level of abstraction, as Pang suggests. A way to hide the irrelevant bits of the file system, and keep only the stuff that's meaningful in view. Arriving at this juncture is a pretty clear indication that the traditional file system representation is dated, and must die.

Apple knows this, because they've ignored the Finder for a long time. Instead of trying to find new ways to let users navigate the file system, they removed it for those things that matter the most. As [Sachin Agarwal points out][sachin]:

> When you launch iTunes, you see your music. When you launch iPhoto, you see your photos. When you launch Mail, you see your email. Where is it all stored? Who cares. Apple stores these files on your Mac in a folder or "package" that isn't meant to be examined or manipulated.

As for Alex King's observations, I believe (backed by no data but my own experience) that Dropbox is used very much like an everything bucket. A way to synchronize documents and photos and music, rather than files, at least insofar as users are concerned. And that's why Dropbox is increasingly mainstream. I don't think we can ever move away from using simple hierarchies for organizing our stuff, and semantic file systems are still a ways off, but removing all the clutter would be a good first step in making the whole experience of managing information better for users. It's not that we can't used the file system as a document store, is that there are all these *other*, unimportant things getting in our way.


[king]: http://alexking.org/blog/2011/01/06/files
[pang]: http://algorithm.com.au/blog/files/filesystem-abstraction.php#unique-entry-id-609
[foster]: http://nimbledesign.com/post/441423115/the-path-of-most-resistance
[toto-simp]: /essays/simplification-of-computing.html
[sachin]: http://sachin.posterous.com/the-finder-is-dead-soon-a-pc-wont-have-files
[Yojimbo]: http://www.barebones.com/products/yojimbo/
[Evernote]: http://www.evernote.com/
[al3x]: http://al3x.net/2009/01/31/against-everything-buckets.html
[blanc]: http://shawnblanc.net/2009/02/payne-against-buckets/

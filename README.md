# CANDY
Skin "engine" for barotrauma

// HUMAN.XML -> MOD'S XML 
// HUMAN2.XML -> CORE REPLACEMENT
// CANDY.XML -> 2ND CORE PACKAGE
// VANILLA.XML -> BASE BUT MODIFIED CORE PACKAGE
// RAGDOLL.XML -> MOD'S XML

// Do not mix them right now. Look at the Issues tab for more info

// Its still in experimenting mode.

// How to get it work? Use the updated Human.xml with the updated Ragdoll.xml to get the error message posted in "Issues" Tab.
// Alternately you can use CANDY/VANILLA (uploaded here, these are almost the same, use Vanilla.xml instead) to tweak the core package. MAKE SURE TO HAVE BACKUP! 
If it would be possible to have CANDY as core package besides VANILLA(The one that comes with the game) that'd be the ideal goal!

Ultimate goal: Add CANDY as core package into the game. 

How it meant to work: CANDY "should be" a core package.
What is a core package? > It tells the game what files to look at when loading content. 

The core package coming with the game called "Vanilla" this tells the game to look for Human.xml which is the basic human body "format" for the game. Having a 2nd version of this packed with a mod, seems to cause issues. So the change of a core package would re-write the routes for files and we can make the game read "our" files instead. 

How it would be used ?  ( Its just a plan )
1. You'll need CANDY as a core package. 
2. You get skin mods from workshop > The mod would come with texture files and ragdoll.xml. 
3. Enable CANDY to read the files we want.
4. Enable skinmods and it should work just like before the ###### update.

// Why need CANDY? > The basic human.xml that been released with the new update, screwing up the mods, is limited. If we make our own Human.xml. It would let the game read the mods the way it was before the update.

The "Vanilla" Core package, included with the game refers to the old one. We need a new core package to refer to our version of Human.xml

Why cant we just modify the existing core package? If we do so, every other people who wants to play with the mod, has to. Its really inconvinient... I wouldnt say it wont work tho.


===== SOME LOGS =====

I updated the old Human.xml and Ragdoll.xml ( what we used in our mods previously ) To fit the new way Barotrauma works. It makes errors yes!
Some info: After updating the files, the skins dont work but it fully renders the default models! 

I made CANDY as a core package, but the game doesn't recognizes .. yet.

Tweaked the Vanilla a little but forgot to save. It didnt work anyways.

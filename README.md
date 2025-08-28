Implements the Swashbuckler for the PF2e Baldur's Gate 3 mod.

https://mod.io/g/baldursgate3/m/swashbuckler-pf2e

**Features**
- Tumble Through is quite janky, but works more or less. Can be very difficult to find valid jump paths for enemies that aren't short. 
- An elegant panache system, which handles the interaction between the permanent panache granted on successes and the temporary panache granted on failures.
- Braggart, Fencer, Gymnast, Rascal, and Wit are implemented in full.
- There are at least 4 implemented feats for each level except 12, so there should be plenty to choose from throughout your playthroughs.
- Icons and animations that are all at least passable.

**Bugs and Requests**
- All feats have been tested to the best of my ability, but things will have surely slipped through the cracks. If you find issues, ideally report them here.
- Battledancer is not, and will never be, implemented, as the perform action isn't really very useful in a CRPG, so the play cycle would be weird and unsatisfying. Feats that are built for battledancer are therefore also unimplemented.
- A number of other feats are unimplemented due to technical limitations. Flying blade is also unimplemented, because although possible, it would essentially require duplicating every spell in the class for the sake of a single feat and double the time to test new builds. I have also not implemented any uncommon or rare feats. If there are particular feats you would like to see, open an issue and I will have a look at it.
- I am not an artist, so my icon work leaves a fair bit to be desired, so if you can do better than I did, I would welcome the support. Similarly, I would love to get some unique animations made up, particularly for Tumble Through and Shout spells.

**Known Limitations**
- Speed bonuses given by Stylish Combatant and Vivacious Speed are not typed, so will stack with Longstrider. If the base mod is updated to type speed bonuses and penalties this will be updated.
- Tumble Through makes an athletics check against a fixed DC, isntead of any quality of the target. In order for the jumping effect to work, this cannot be avoided.
- Tumble Through uses some particularly odd tech to sort out its animation. Performance dependent, swashbucklers may polymorph into a halberd briefly at the start of combat. A fix for this will come eventually, but it is waiting on another mod to update.

This mod uses trademarks and/or copyrights owned by Paizo Inc., used under [Paizo's Community Use Policy](<https://paizo.com/licenses/communityuse>). We are expressly prohibited from charging you to use or access this content. This mod is not published, endorsed, or specifically approved by Paizo. For more information about Paizo Inc. and Paizo products, visit [paizo.com](<https://paizo.com>).
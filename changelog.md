Changelog
-------------
0.1.0 - System Open

0.1.1 - Bug Fixed
  * Fixed Spirit Dice being out of sync
  * Fixed Influence is not worked in player
  
0.1.2 - Set Action Dice
  * Select action dice number ex) 2D -> 3D
  * Raise spirit dice number (use Macro)
  
0.1.3 - Bug Fixed & Influence Update
  * Fixed Instability of Spirit Dice
  * Change Influence UI.
  * Multiple Dice Influence.
  
0.1.4 - Chat module compatibility update
  * Sidebar Aesthetics's compatibility issue fix.
  
0.1.5 - Talent Description Update
  * Now you can see talent's timing, range, target, cost in your character sheet. 
  
0.1.6 - Term Collection
  * Dice Pull Macro -> Dice Pool Macro
  * Conjection -> Invocation, Insight -> Instinct, Armor -> Guard, Barrier -> Ward
  
0.2.0 - Add Enermy Sheet
  * Can create enery sheet
  
0.2.1 - Battle Tracker Initiative Update
  * Can use battle tracker by initiative
  
0.3.0 - Add Spirit Burn Support & Inventory Update
  * Can use spirit burn in actor sheet
  * Common equipment is showing its quantity in character's sheet
  * enermy -> enemy
  
0.3.5 - Change Enemy's Attack Option
  * Attack option item is added
  * Enemy attack option memo is added

0.3.6 - Typo correction
  * Fixed Transcend typo in chat window

0.4.0 - Add Spirit Dice Viewer
  * Added Spirit dice viewer
  * Added Enermy to enemy macro
  * Fixed Character coin is not synced
  * Invisible the attack button when the enemy's attack formula is empty

0.4.1 - Add Export feature & Bug Fix
  * Added feature which export item from actor sheet to item directory 
  * Fixed the problem of not syncing when more than one spirit dice dialog
  
0.4.2 - Compatible Update 0.7.5

0.5.0 - Automation Update
  * Character sheet is automaticaly calcutating status
  * Automaticaly calculating damage -> high dice and talent's rank, additional correction
  * Overflow can use in his sheet
  * Other etc...

0.5.1 - Add Talant Classify Option
  * Add talent classify option

0.5.2 - Bug fix
  * Fix Spirit Dice viewer not working

0.5.3 - Macro & Talent Update
  * Talent can set in macro hotbar
  * Add conditional setting that automatically turns talent activation into inactive

0.5.4 - Add Talent's option
  * Add roll only options (STR, AGI, INT, WIL, LCK)
  * Add ranged weapon's ※ pd option in equipment sheet option

0.6.0 - Detail damage option calculation
  * Add damage calculating option
  * Add the feature to apply damage to the targets

0.6.1 - Update damage apply
  * Damage can be applied for each enemy with a damage option set

0.6.2 - Item speicialize
  * Items are divided into SacramentItem and ConsumableItem.

0.6.3 - Typo correction
  * Armor -> Guard / Barrier -> Barrier

0.6.4 - Use talent, item's macro
  * Add talent's macro when use talent
  * Add item's macro when use item
  * Add Euipment toggle

0.6.5 - Bug fix
  * Fix an issue where the price was not included when copying an item

0.6.6 - Bug fix
  * Fix an issue in which damage decreases when targeting more than one body when calculating damage

0.6.7 - Add Item Macro Sample & AttackOption echo
  * Add sample compendium of heal macro
  * Add detail of attackOption's echo

0.6.8 - Add an Option of add modifier
  * Add config of additional modifier when roll

0.8.0 - Update some sheet
  * Add facade sheet
  * Add equipment on/off checkbox in actor sheet
  * Add level textbox in talent sheet

0.8.1 - Add Half options, bug fix
  * Add half options of damage calculation
  * Fix dice don't rolling bug when rollmode is Whisper, Blind, Roll  

0.8.2 - Change prompt -> dialog
  * change prompt, comfirm, alert to dialog

0.8.3 - Update Spirit Dice viewer
  * Add overflow in Spirit Dice viewer

0.8.4 - Bug fix
  * Combat tracker is not working
  * Talent's Disable timing is not working when setted after round, after battle
  
0.8.6 - Bug fix
  * Fix Concept Destruction bug

0.8.7 - Layout update
  * Few layout enhancement of sheets(Thanks jbblily)

1.0.0 - Combat Enhancement
  * Automate actions that can be used for timing
  * Automate recharge spirit dice when round is ended
  * Talant sheet's timing change to select box
  * Add some macros to view character's talent
  * Some bug fix

1.0.1 - Token Hud Support
  * Compatibility patch for tokenhud module

1.0.2 - Bug fix
  * Fix that combat initiative is not rolled when first time
  
1.0.3 - Add Setting
  * Add Setting of timing Dialog
  
1.0.4 - Add Suport
  * Add suport of Combat carousel
  
1.0.5 - Add Configuration
  * Add option of Timing Dialog
  * Add option of automatic spirit dice charge

1.0.6 - Change dice face
  * change dice face (thanks jbblily)

1.1.0 - Better Enemy Control
  * Add support of calculating enemy's damage
  * Add support of applying damage between enemy and character
  * Add recovery option when applying damage 
  * Categorizing enemy's Attack Options (+token-action-hud)
  
1.1.1 - Change Design
  * Localize dialog & Some minor template change (thanks jbblily)
  
1.1.2 - Bug Fix
  * Fix Influence bug

1.2.0 - Add Talent's Features
  * Add a text vox that records  the number of uses of the talent
  * Add a checkbox to determine whether targeting when using talent
  * Add an End Scene, End Session macro that reset talent's active and used

1.2.1 - Bug Fix
  * Fixed an issue where used is not reset when the talent is disabled

1.2.2 - Update English translation
  * Update English translation (thanks NotoriusNeo)

1.2.3 - Update Ancestry & Facet
  * Add buttons that allows you to add annestry and facet from the character sheet
  * Add localization when creating item

1.2.4 - Update actor's limited permission
  * Modify to show only the basics if you have limited permissions when viewing Enemy sheets

1.2.5 - Add Ctrl option when rolling the dice.
  * When you press Ctrl and roll a dice, update so that a modifier dialog comes out.
  * Remove some macros
  * Some code changed
  
1.2.6 - Add Damage reduce options
  * Add talent attributes that can be used to reduce damage.
  * Add a flag of the talent that is deactivated after damage reduction.
  * Fixed a bug that didn't reduce damage properly.

1.3.0 - Add talent attributes that apply to the target
  * Talent can have a target tab and put an effect that applies to the target.
  * Each character has an effect tab, where you can check the target talent applied.

1.3.1 - Bug fix
  * Fix a bug where the enermy sheet doesn't open.
  * Change the initial value of the enermy sheet to blank.
  * Modified the character to have priorities over enermy during battle.

1.3.2 - Bug fix
  * Fix a bug that do not add equipment ability.
  * Fix a bug that brings the disable effect from the item.

1.3.3 - Update equipment sheet
  * Change the description of the equipment sheet to the editor.

1.4.0 - Update about timing.
  * It is automatically applied even if you use a talent while the damage reduce dialog is floating.
  * During the damage reduce, an option has been added to ask all characters whether to use defense timing.
  * Added options to start, end, and defense timing dialogs.

1.4.1 - Bug fix
  * Fix a bug that the character sheet doesn't come out in some actions.
  * Add feature to show total damage and life after reduce damage.

1.4.2 - Update bond sheet
  * Change Bond sheet's description

1.4.3 - Bug fix
  * Fix a bug when enemy's defense is zero

1.4.4 - Add talent menu
  * Add talent bar where you can easily see talent or items.

1.4.5 - Update UI
  * Update chat portrait ui
  
1.4.6 - Minor update
  * Compatible Update v9
  * Add features of reset hp and crest

1.4.7 - Bug fix
  * Fixed a bug in which influence does not work in version 9.
  * Fixed a bug that doesn't work properly when you roll a dice, not 6d.
  * Add features of reset spirit dice pool (right click)
  * Expanding the size of select actors dialog.
  * Update the css a little bit.

1.4.8 - Bug fix
  * Fixed a bug that doesn't work as combat's initial roll
  
1.4.81 - Bug fix
  * Remove tab's padding

1.4.82 - Errata to status (Korean) 
  * Errata to status (Korean) 

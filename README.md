Collection of patches for Reksio and the UFO which reimplement some unused content and fix various bugs. Details listed below for each one:

- *14_3_Podworko/**kret14_1.seq*** : Adds unused Kretes line about friend from Rzeszów (***kre14_1_8.wav***)
- *21_0_Warsztat/**s21_0_Warsztat.cnv*** : Adds unused Narrator line introducing Kretes after finishing construction (***narr21_0_3.wav***)
- *75_port/**S75_PORT.cnv*** | ***kuraprawa.seq*** | ***kuralewa.seq*** : Changes sequence of alien hens' idle dialogues to be logically ordered rather than random, and plays the dialogue upon entry
- *Droga/**s71_droga.cnv*** : Changes behaviour when caught by alien hens to skip directly to cutscene instead of redundantly playing voice line a second time in the minigame screen
- *Pakman/**s62_pakman.cnv*** : Adds unused Narrator line when a character approaches the locked gate to the Ferment village while not holding the key (***narr62_0_2.wav***)
- *s1_0_intro1/**s1_0_intro1.cnv*** : Adjusts timing at the end of the first intro slide to match the music better
- *s42_1_skladzik/**s42_1_skladzik.cnv*** : Adds unused Narrator line presenting the process of fixing the spaceship (***narr43_2_1.wav***)
- *s43_lrbin/**s43_lrbin.cnv*** :
  - Adds unused lines for clicking on the doormat (***mol43_1_16.wav***), photo of three moles (***mol43_1_25.wav***), and Kretti (***mol43_1_22.wav***) using variable implemented in Przygoda.cnv mentioned below
  - Enables cancelling out of Molly's presentations by clicking on other interactibles
  - Disables redundant self-introductions by  following first visit, disables outdated presentation of Indor after visiting it, re-enables still-relevant presentations after returning from Kurakis
  - Adds frame-perfect priority changing to animation of Reksio changing into disguise so it doesn't overlap other sprites strangely
- *s46_odkurzacz/**s46_Odkurzacz.cnv*** : Adds unused lines with Kretoff's ideas about how to get the vacuum out (***kff46_0_9.wav***, ***kff46_0_10.wav***) and his pleas for other ideas after returning from Kurakis (***kff46_2_3.wav***, ***kff46_2_4.wav***)
- *s52_0_Wioska/**S52_0_WIOSKA.cnv*** | ***julita52.seq*** :
  - Adds unused lines with Julitta's lamentation after first entry greeting by the other bindor
  - Enables loop of Julitta waiting then saying random lamentation when idle
  - Enables cancelling out of the other bindor's self-presentation by clicking on other interactibles
  - Adds unused thank you line from Julitta's second head when talking to her after delivering the letter (***jul52_0_12.wav***)
- *s56_0_Wioska/**ROMAN56.SEQ*** : Adds unused Roman line about not hearing Juliita (***rom52_0_1.wav***)
- *s65_Zamek/**s65_Zamek.cnv*** : Fixes the initial cutscene (restores the fade-in effect, makes dust visible from the start, hides Reksio and Kretes sprites before they enter the scene, matched priority of character sprites with that from exiting, switched to correct entry animations, made background dust animate from the start)
- ***Przygoda.cnv*** : Adds missing variable (***FOTKASEEN***) necessary for behaviour of photo presentation in *s43_lrbin/**s43_lrbin.cnv*** mentioned above

To install, simply copy-paste the desired modification into the game's directory.

Installing this mod represents a modification of the game files in violation of the end-user licence agreement.

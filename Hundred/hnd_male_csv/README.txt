All Men's The Hundred match data in CSV format
==============================================

The background
--------------

As an experiment, after being asked by a user of the site, I started
converting the IPL data from YAML into this CSV format. This then expanded
to include international T20s, for both women and men, before, finally,
expanding again to cover all matches we provide.

This particular zip folder contains the CSV data for...
  All Men's The Hundred matches
...for which we have data, and is loosely based on the format that Retrosheet
uses for baseball, with some suitable hacks built in.

How you can help
----------------

Providing feedback on the data would be the most helpful. Tell me what you
like and what you don't. Is there anything that is in the JSON data that
you'd like to be included in the CSV? Could something be included in a better
format? General views and comments help, as well as incredibly detailed
feedback. All information is of use to me at this stage. I can only improve
the data if people tell me what does works and what doesn't. I'd like to make
the data as useful as possible but I need your help to do it. Also, which of
the 2 CSV formats do you prefer, this one or the newer "Ashwin" format?
Ideally I'd like to settle on a single CSV format so what should be kept
from each?

Finally, any feedback as to the licence the data should be released under
would be greatly appreciated. Licensing is a strange little world and I'd
like to choose the "right" licence. My basic criteria may be that:

  * the data should be free,
  * corrections are encouraged/required to be reported to the project,
  * derivative works are allowed,
  * you can't just take data and sell it.

Feedback, pointers, comments, etc on licensing are welcome.

The format of the data
----------------------

Full documentation of this CSV format can be found at:
  https://cricsheet.org/format/csv_original/
but the following is a brief summary of the details...

Each file has a 'version', multiple 'info' lines, and multiple 'ball' lines.
'version' is just 1.6.0, or 1.7.0 for now, and will change as I make changes.
The 'info' entries should be fairly self-explanatory but feel free to ask on
Mastodon (@cricsheet@deeden.co.uk) if you're unsure. If you look carefully
you may see some slight hints as to some data we'll be including in the full
data files in the future.

Each 'ball' line has the following fields:

  * The word 'ball' to identify it as such
  * Innings number, starting from 1
  * Over and ball
  * Batting team name
  * Batsman
  * Non-striker
  * Bowler
  * Runs-off-bat
  * Extras
  * Wides
  * No-balls
  * Byes
  * Leg-byes
  * Penalty
  * Kind of wicket, if any
  * Dismissed played, if there was a wicket

Matches included in this archive
--------------------------------

2021-07-22 - club - HND - male - 1252666 - Oval Invincibles vs Manchester Originals
2021-07-23 - club - HND - male - 1252667 - London Spirit vs Birmingham Phoenix
2021-07-24 - club - HND - male - 1252668 - Southern Brave vs Trent Rockets
2021-07-24 - club - HND - male - 1252669 - Welsh Fire vs Northern Superchargers
2021-07-25 - club - HND - male - 1252671 - Birmingham Phoenix vs Manchester Originals
2021-07-26 - club - HND - male - 1252672 - Northern Superchargers vs Trent Rockets
2021-07-27 - club - HND - male - 1252673 - Welsh Fire vs Southern Brave
2021-07-29 - club - HND - male - 1252675 - Trent Rockets vs London Spirit
2021-07-30 - club - HND - male - 1252676 - Birmingham Phoenix vs Southern Brave
2021-07-31 - club - HND - male - 1252677 - Welsh Fire vs Manchester Originals
2021-07-31 - club - HND - male - 1252678 - Oval Invincibles vs Northern Superchargers
2021-08-01 - club - HND - male - 1252679 - Trent Rockets vs Birmingham Phoenix
2021-08-01 - club - HND - male - 1252680 - Southern Brave vs London Spirit
2021-08-02 - club - HND - male - 1252681 - Welsh Fire vs Oval Invincibles
2021-08-03 - club - HND - male - 1252682 - Northern Superchargers vs London Spirit
2021-08-04 - club - HND - male - 1252683 - Oval Invincibles vs Birmingham Phoenix
2021-08-05 - club - HND - male - 1252684 - Manchester Originals vs Southern Brave
2021-08-06 - club - HND - male - 1252685 - Welsh Fire vs Trent Rockets
2021-08-07 - club - HND - male - 1252686 - Northern Superchargers vs Southern Brave
2021-08-08 - club - HND - male - 1252687 - Oval Invincibles vs Trent Rockets
2021-08-09 - club - HND - male - 1252688 - Birmingham Phoenix vs Welsh Fire
2021-08-10 - club - HND - male - 1252689 - London Spirit vs Manchester Originals
2021-08-11 - club - HND - male - 1252690 - Welsh Fire vs Southern Brave
2021-08-12 - club - HND - male - 1252691 - Northern Superchargers vs Manchester Originals
2021-08-13 - club - HND - male - 1252692 - Birmingham Phoenix vs Trent Rockets
2021-08-14 - club - HND - male - 1252693 - London Spirit vs Oval Invincibles
2021-08-15 - club - HND - male - 1252694 - Manchester Originals vs Trent Rockets
2021-08-16 - club - HND - male - 1252695 - Oval Invincibles vs Southern Brave
2021-08-17 - club - HND - male - 1252696 - Northern Superchargers vs Birmingham Phoenix
2021-08-18 - club - HND - male - 1252697 - London Spirit vs Welsh Fire
2021-08-20 - club - HND - male - 1252698 - Trent Rockets vs Southern Brave
2021-08-21 - club - HND - male - 1252699 - Southern Brave vs Birmingham Phoenix
2022-08-03 - club - HND - male - 1299171 - Welsh Fire vs Southern Brave
2022-08-04 - club - HND - male - 1299172 - London Spirit vs Oval Invincibles
2022-08-05 - club - HND - male - 1299173 - Manchester Originals vs Northern Superchargers
2022-08-06 - club - HND - male - 1299174 - Birmingham Phoenix vs Trent Rockets
2022-08-07 - club - HND - male - 1299175 - Oval Invincibles vs Welsh Fire
2022-08-08 - club - HND - male - 1299176 - London Spirit vs Manchester Originals
2022-08-09 - club - HND - male - 1299177 - Northern Superchargers vs Trent Rockets
2022-08-10 - club - HND - male - 1299178 - Birmingham Phoenix vs Southern Brave
2022-08-11 - club - HND - male - 1299179 - Northern Superchargers vs Oval Invincibles
2022-08-12 - club - HND - male - 1299180 - London Spirit vs Southern Brave
2022-08-13 - club - HND - male - 1299181 - Manchester Originals vs Trent Rockets
2022-08-13 - club - HND - male - 1299182 - Birmingham Phoenix vs Welsh Fire
2022-08-14 - club - HND - male - 1299183 - Northern Superchargers vs London Spirit
2022-08-14 - club - HND - male - 1299184 - Southern Brave vs Oval Invincibles
2022-08-15 - club - HND - male - 1299185 - Trent Rockets vs Birmingham Phoenix
2022-08-16 - club - HND - male - 1299186 - Manchester Originals vs Welsh Fire
2022-08-17 - club - HND - male - 1299187 - Trent Rockets vs Oval Invincibles
2022-08-18 - club - HND - male - 1299188 - Manchester Originals vs Southern Brave
2022-08-19 - club - HND - male - 1299189 - Northern Superchargers vs Birmingham Phoenix
2022-08-20 - club - HND - male - 1299190 - London Spirit vs Trent Rockets
2022-08-21 - club - HND - male - 1299191 - Manchester Originals vs Northern Superchargers
2022-08-22 - club - HND - male - 1299192 - Welsh Fire vs Southern Brave
2022-08-23 - club - HND - male - 1299193 - Birmingham Phoenix vs Oval Invincibles
2022-08-24 - club - HND - male - 1299194 - London Spirit vs Welsh Fire
2022-08-25 - club - HND - male - 1299195 - Trent Rockets vs Southern Brave
2022-08-26 - club - HND - male - 1299196 - Welsh Fire vs Northern Superchargers
2022-08-27 - club - HND - male - 1299197 - London Spirit vs Oval Invincibles
2022-08-28 - club - HND - male - 1299198 - Manchester Originals vs Birmingham Phoenix
2022-08-29 - club - HND - male - 1299199 - Trent Rockets vs Welsh Fire
2022-08-30 - club - HND - male - 1299200 - London Spirit vs Birmingham Phoenix
2022-08-31 - club - HND - male - 1299201 - Northern Superchargers vs Southern Brave
2022-08-31 - club - HND - male - 1299202 - Oval Invincibles vs Manchester Originals
2022-09-02 - club - HND - male - 1299203 - London Spirit vs Manchester Originals
2022-09-03 - club - HND - male - 1299204 - Manchester Originals vs Trent Rockets
2023-08-01 - club - HND - male - 1355606 - Trent Rockets vs Southern Brave
2023-08-02 - club - HND - male - 1355607 - Welsh Fire vs Manchester Originals
2023-08-02 - club - HND - male - 1355608 - London Spirit vs Oval Invincibles
2023-08-03 - club - HND - male - 1355609 - Birmingham Phoenix vs Northern Superchargers
2023-08-04 - club - HND - male - 1355610 - Southern Brave vs Welsh Fire
2023-08-05 - club - HND - male - 1355611 - Manchester Originals vs London Spirit
2023-08-06 - club - HND - male - 1355613 - Northern Superchargers vs Southern Brave
2023-08-06 - club - HND - male - 1355614 - Welsh Fire vs Oval Invincibles
2023-08-07 - club - HND - male - 1355615 - Manchester Originals vs Birmingham Phoenix
2023-08-08 - club - HND - male - 1355616 - Southern Brave vs London Spirit
2023-08-09 - club - HND - male - 1355617 - Northern Superchargers vs Trent Rockets
2023-08-09 - club - HND - male - 1355618 - Oval Invincibles vs Manchester Originals
2023-08-10 - club - HND - male - 1355619 - Birmingham Phoenix vs Welsh Fire
2023-08-11 - club - HND - male - 1355620 - Oval Invincibles vs Northern Superchargers
2023-08-12 - club - HND - male - 1355621 - London Spirit vs Trent Rockets
2023-08-12 - club - HND - male - 1355622 - Welsh Fire vs Southern Brave
2023-08-13 - club - HND - male - 1355623 - Manchester Originals vs Northern Superchargers
2023-08-13 - club - HND - male - 1355624 - Birmingham Phoenix vs Oval Invincibles
2023-08-14 - club - HND - male - 1355625 - Trent Rockets vs Welsh Fire
2023-08-15 - club - HND - male - 1355626 - Oval Invincibles vs London Spirit
2023-08-16 - club - HND - male - 1355627 - Birmingham Phoenix vs Southern Brave
2023-08-17 - club - HND - male - 1355628 - Manchester Originals vs Trent Rockets
2023-08-18 - club - HND - male - 1355629 - London Spirit vs Northern Superchargers
2023-08-19 - club - HND - male - 1355630 - Trent Rockets vs Birmingham Phoenix
2023-08-19 - club - HND - male - 1355631 - Oval Invincibles vs Southern Brave
2023-08-20 - club - HND - male - 1355632 - Manchester Originals vs Northern Superchargers
2023-08-20 - club - HND - male - 1355633 - London Spirit vs Welsh Fire
2023-08-21 - club - HND - male - 1355634 - Trent Rockets vs Oval Invincibles
2023-08-22 - club - HND - male - 1355635 - Northern Superchargers vs Welsh Fire
2023-08-23 - club - HND - male - 1355636 - Manchester Originals vs Southern Brave
2023-08-24 - club - HND - male - 1355637 - Birmingham Phoenix vs London Spirit
2023-08-26 - club - HND - male - 1355638 - Southern Brave vs Manchester Originals
2023-08-27 - club - HND - male - 1355639 - Oval Invincibles vs Manchester Originals
2024-07-23 - club - HND - male - 1417790 - Birmingham Phoenix vs Oval Invincibles
2024-07-24 - club - HND - male - 1417791 - London Spirit vs Southern Brave
2024-07-25 - club - HND - male - 1417792 - Manchester Originals vs Welsh Fire
2024-07-26 - club - HND - male - 1417793 - Trent Rockets vs Northern Superchargers
2024-07-27 - club - HND - male - 1417794 - London Spirit vs Birmingham Phoenix
2024-07-28 - club - HND - male - 1417795 - Oval Invincibles vs Welsh Fire
2024-07-29 - club - HND - male - 1417796 - Trent Rockets vs Manchester Originals
2024-07-30 - club - HND - male - 1417797 - Southern Brave vs Northern Superchargers
2024-07-31 - club - HND - male - 1417798 - Birmingham Phoenix vs Trent Rockets
2024-08-01 - club - HND - male - 1417799 - Welsh Fire vs London Spirit
2024-08-01 - club - HND - male - 1417800 - Manchester Originals vs Southern Brave
2024-08-02 - club - HND - male - 1417801 - Northern Superchargers vs Oval Invincibles
2024-08-03 - club - HND - male - 1417802 - Southern Brave vs Birmingham Phoenix
2024-08-03 - club - HND - male - 1417803 - Welsh Fire vs Trent Rockets
2024-08-04 - club - HND - male - 1417804 - Oval Invincibles vs London Spirit
2024-08-04 - club - HND - male - 1417805 - Northern Superchargers vs Manchester Originals
2024-08-05 - club - HND - male - 1417806 - Southern Brave vs Welsh Fire
2024-08-06 - club - HND - male - 1417807 - Oval Invincibles vs Manchester Originals
2024-08-06 - club - HND - male - 1417808 - Northern Superchargers vs Birmingham Phoenix
2024-08-07 - club - HND - male - 1417809 - Trent Rockets vs London Spirit
2024-08-08 - club - HND - male - 1417810 - Northern Superchargers vs Welsh Fire
2024-08-08 - club - HND - male - 1417811 - Southern Brave vs Oval Invincibles
2024-08-09 - club - HND - male - 1417812 - Manchester Originals vs London Spirit
2024-08-10 - club - HND - male - 1417813 - Trent Rockets vs Southern Brave
2024-08-10 - club - HND - male - 1417814 - Welsh Fire vs Birmingham Phoenix
2024-08-11 - club - HND - male - 1417815 - London Spirit vs Oval Invincibles
2024-08-11 - club - HND - male - 1417816 - Manchester Originals vs Northern Superchargers
2024-08-12 - club - HND - male - 1417817 - Trent Rockets vs Birmingham Phoenix
2024-08-13 - club - HND - male - 1417818 - London Spirit vs Northern Superchargers
2024-08-14 - club - HND - male - 1417819 - Welsh Fire vs Southern Brave
2024-08-14 - club - HND - male - 1417820 - Oval Invincibles vs Trent Rockets
2024-08-15 - club - HND - male - 1417821 - Manchester Originals vs Birmingham Phoenix
2024-08-17 - club - HND - male - 1417822 - Southern Brave vs Birmingham Phoenix
2024-08-18 - club - HND - male - 1417823 - Oval Invincibles vs Southern Brave

Further information
-------------------

You can find all of our currently available data at https://cricsheet.org/

You can contact me via the following methods:
  Email   : stephen@cricsheet.org
  Mastodon: @cricsheet@deeden.co.uk

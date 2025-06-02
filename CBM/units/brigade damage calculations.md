Forum says formula is: 
(brig strength / 3k) * base casualties from roll * ((1 + attack stat) / 10) * (1 / (enemy national mil tactics + enemy fort mil tactics)) * (1 / (1 + enemy exp))

plains battles no fort 1836


137 - 256
9 - 4
-1 dig in

107 - 209 third tick after arty is def frontline



60 - 50
5 - 4
-1 dig in

58 - 49 second tick

1 * 96 * (2 / 10) * (1 / 2) * (1 / 1.05)

96 * 0.2 * 0.5 * 0.95
9.12

... doesnt work?

add leading 10

1 * 96 * (12 / 10) * (1 / 2) * (1 / 1.05)

96 * 1.2 * 0.5 * 0.95
54.72

4 higher than expected??
remove the added one?

50.16
We did it!


the formula works, now we figure out how the backline works


724 - 50

724 / 2 = 362

gonna figure out prussia side casualites

1 * 180 * (11 / 10) * (1 / 1.75) * (1 / 1.06) INF BRIGADE DAMAGE
180 * 1.1 * 0.57 * 0.94
106.1


1 * 180 * (11.5 / 10) * (1 / 1.75) * (1 / 1.06) ART BRIGADE DAMAGE if support does nothing
180 * 1.15 * 0.57 * 0.94
110.9

1 * 180 * (15.5 / 10) * (1 / 1.75) * (1 / 1.06) ART BRIGADE DAMAGE if support multiplies before the division
180 * 1.55 * 0.57 * 0.94
149


still missing some...
could brigades without manuever hit from the sides?

510.2 for the middle two
two more 106.1 from side brigs gives 722.4, within rounding error 
any further outside brigades must not be able to hit them w/o manuever


WE KNOW HOW IT WORKS

so now we can do balancing

infantry day 1: 17 damage att and defense, 0 on backline

artillery: 11 damage on frontline att 11.5 defense. 14.85 backline att 15.5 backline defense

arty more consistent but inf mixed in is better.


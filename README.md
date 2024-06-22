# LPColorAPI

This is a simple API that allows you to implement a "rank color" system into your plugins using the LuckPerms permissions system. This seemed like a good idea since most custom (or even paid) cores come with rank color functionality. Any plugin can now utilize colors that you designate.

To use, simply designate all your intended "rank" groups as having a meta value of "rank-color" set to whatever you like. For example: `/lp group owner meta set rank-color &4` will set the color of "owner" to dark red. Then, add this JAR to your project and simply run the method `getRankColor()`, which takes the player as a parameter and returns a string containing the player's rank color.

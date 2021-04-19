# editActionSpeeds
AWS DeepRacer Edit Your Custom Action Space Speeds


Paste in your full action space into the file "action_space.json", it can handle index values if you have them already
Run this script with desired parameters on the last line"


1st Parameter either a positive or negative value for editing all speeds the same value
2nd/3rd/4th Parameter boolean for changing left(positive), straight or right steering angles
5th Parameter is for adding index values


# EXAMPLE 1 - Add Speed of 0.5 to all actions, with updating index values
edit_action_speeds(0.5, True, True, True, True)

# EXAMPLE 2 - Minus Speed of 0.1 to all actions, with no change to index values
edit_action_speeds(-0.1, True, True, True, False)

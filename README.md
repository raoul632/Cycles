# Cycles
Cycle de test strudel

ready to use 
setcpm(140/4)
samples({
 playyvette: 'Full-Mix-Pad-Unprocessed.wav'
 }, 'https://raw.githubusercontent.com/raoul632/Cycles/master/');
$: s("[bd ~]*2, [~ hh]*2, ~ sd")
$:s("tbd:2!4").scope()
$: n("0 2 3 5".add(-7)).scale("g:minor").s("supersaw")


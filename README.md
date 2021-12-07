# Mersenne-Twister
Mersenne-Twister RNG for Factorio
modify for luajit 2.0.x


function MT19937.seed(seed): 

	Set a seed.
	Seed should be an integer above 0.
function MT19937.random(p, q): 

	Get a random number.
	Works the same as math.random in the lua standard library.
	If called before setting a seed, it will use the map seed.

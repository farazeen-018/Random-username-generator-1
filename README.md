# Random-username-generator-1
import random
import string 
adjectives = ["beautiful", "me", "Happy", "cute"]
nouns = ["daisy", "classy", "place", "teddy"]
adjective = random.choice(adjectives)
noun = random.choice(nouns)
number = random.randint(1, 99)
username = adjective + noun + str(number)
print("Generated username:", username)

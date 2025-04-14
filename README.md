# python-week-5-assignment

class Hero:

def__init__(self, name, true_name, ability):

self.name = name # Name of the superhero

self.real_name = real_name # Actual name of the superhero

self.power = power # Distinct ability of the superhero

def utilize_power(self):

return f"{self.name} employs {self.power}!"

def disclose_identity(self):

return f"{self.name} is in reality {self.real_name}."

class SoaringHero(Hero):

def __init__(self, name, true_name, ability, speed_of_flight):

super().__init__(name, actual_name, strength)

self.flight_speed = flight_speed # Rate of flight

def soar(self):

return f"{self.name} soars at {self.flight_speed} mph!"

# Sample application

hero1 = Hero("Invisible Man", "John Doe", "Invisibility")

output(hero1.activate_ability())

display(hero1.reveal_identity())

flying_hero1 = FlyingHero("Aerial Commander", "Jessica Jackson", "Aviation", 200)

print(flying_hero1.activate_ability())

print(flying_hero1.take_flight())

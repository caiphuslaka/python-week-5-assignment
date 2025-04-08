# python-week-5-assignment

# Create a Superhero class
class Superhero:
    def _init_(self, name, power, speed):
        self.name = name
        self.power = power
        self.speed = speed
    def display(self):
        return f"Name: {self.name}, Power: {self.power}, Speed: {self.speed}"
# Create a subclass for FlyingSuperhero
class FlyingSuperhero(Superhero):
    def _init_(self, name, power, speed, fly_height):
        super()._init_(name, power, speed)
        self.fly_height = fly_height
    def display(self):
        return f"{super().display()}, Fly Height: {self.fly_height}"
# Example usage:
superhero = Superhero("Iron Man", "Laser eyes", 50)
flying_superhero = FlyingSuperhero("Superman", "X-ray vision", 100, 10000)
print(superhero.display())
print(flying_superhero.display())

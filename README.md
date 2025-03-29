```py
class Miszx:
    def __init__(self):
        self.languages = ["Python", "Go"]
        self.specialties = ["Discord Bots", "Discord Tools", "APIs"]

    def __str__(self):
        return f"🔥 miszx - {', '.join(self.languages)} Dev | Specialties: {', '.join(self.specialties)}"

me = Miszx()
print(me)```

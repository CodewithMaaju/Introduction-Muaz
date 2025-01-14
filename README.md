# Introduction-Muaz
My Introduction in Python 
class Introduction:
    def __init__(self):
        self.name = "Muhammad Muaz Khan"
        self.status = "Graduate Student"
        self.skills = ["Python"]
        self.passion = "I enjoy collaborating with passionate people and contributing to their projects."

    def introduce(self):
        print(f"Hello, I am {self.name}.")
        print(f"A {self.status} proficient in {', '.join(self.skills)}.")
        print(self.passion)

if __name__ == "__main__":
    intro = Introduction()
    intro.introduce()

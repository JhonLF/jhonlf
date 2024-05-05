```python
class PersonalInfo:
    def __init__(self):
        self.name = "Jhon L. Fernandes"
        self.age = 33
        self.nationality = "Brazilian"
        self.languages = ["English", "Portuguese"]
        self.marital_status = "Married"
        self.location = "London, UK"

    def say_hi(self):
        print(f"👋 Hi there! My name is {self.name}.")

    def contact_info(self):
        print("💬 Contact me to discuss software development opportunities!")

class Career:
    def __init__(self):
        self.role = "Software Developer"
        self.studies = "📚 Currently studying:"
        self.courses = [
            "Python Programming",
            "SQL",
            "Go",
            "Algorithms and Data Structures",
            "Agile Methodologies"
        ]
        self.looking_for = "🔍 Open to job opportunities as a software developer or software engineer."

    def get_info(self):
        print(f"💼 I'm a {self.role} {self.studies}")
        for course in self.courses:
            print(f" - {course}")
        print(self.looking_for)

profile = PersonalInfo()
career = Career()
profile.say_hi()
career.get_info()
profile.contact_info()
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jhonlf/jhonlf/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jhonlf/jhonlf/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/jhonlf/jhonlf/output/github-contribution-grid-snake.svg">
</picture>



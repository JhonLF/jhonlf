```python
class PersonalInfo:
    def __init__(self):
        self.name = "Jhon L. Fernandes"
        self.languages = ["English", "Portuguese", "Italian (B1)"]
        self.location = "Europe / Remote 🌍"
    
    def say_hi(self):
        print(f"👋 Hi there! I'm {self.name}, a Full Stack & Mobile Developer.")
    
    def contact_info(self):
        print("💬 Let's connect to talk about Full Stack, React Native, or Cloud Engineering projects!")

class Career:
    def __init__(self):
        self.role = "Full Stack & Cloud Developer"
        self.focus = "📚 Currently working with:"
        self.skills = [
            "Frontend: React, React Native, Redux",
            "Backend: Node.js, Express, Go",
            "Cloud & DevOps: AWS (Lambda, EC2, S3), Terraform, CI/CD",
            "Database: PostgreSQL, MongoDB, Redis",
            "Mobile: React Native, Expo, AWS Integration"
        ]
        self.looking_for = "🔍 Open to remote opportunities in Full Stack or Cloud Development."
    
    def get_info(self):
        print(f"💼 I'm a {self.role}")
        print(self.focus)
        for skill in self.skills:
            print(f" - {skill}")
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



```python
class PersonalInfo:
    def __init__(self):
        self.name = "Jhon L. Fernandes"
        self.languages = ["English", "Portuguese"]
        self.location = "London, UK"
    
    def say_hi(self):
        print(f"👋 Hi there! My name is {self.name}.")
    
    def contact_info(self):
        print("💬 Contact me to discuss DevOps and Cloud Computing opportunities!")

class Career:
    def __init__(self):
        self.role = "Software Engineer"
        self.studies = "📚 Currently focusing on:"
        self.skills = [
            "Containerization (Docker, Kubernetes)",
            "CI/CD (Jenkins, GitLab CI)",
            "Infrastructure as Code (Terraform, Ansible)",
            "Cloud Platforms (AWS, Azure, GCP)",
            "Monitoring and Logging (Prometheus, ELK Stack)"
        ]
        self.looking_for = "🔍 Open to job opportunities in DevOps and Cloud Engineering roles."
    
    def get_info(self):
        print(f"💼 I'm a {self.role}")
        print(self.studies)
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



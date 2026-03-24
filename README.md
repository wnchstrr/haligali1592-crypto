class Developer:
    def __init__(self):
        self.name = "[wnchstrr]"
        self.role = "Python Backend Explorer"
        self.languages = ["Russian", "English"]
        self.tech_stack = []
        self.goal = "Become solid backend Python developer"

    def get_info(self):
        print("Hello, GitHub!")
        print(f"Name: {self.name}")
        print(f"Role: {self.role}")
        print(f"Languages: {', '.join(self.languages)}")
        print(f"Tech stack: {', '.join(self.tech_stack) if self.tech_stack else 'empty (learning)'}")
        print(f"Goal: {self.goal}")

me = Developer()
me.get_info()







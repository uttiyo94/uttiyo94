-class GitHubProfile:
    def __init__(self, name, username, bio, skills):
        self.name = name
        self.username = username
        self.bio = bio
        self.skills = skills

    def create_profile(self):
        print(f"Creating GitHub profile for {self.name}...")
        print("Profile created successfully!")
        print("Name:", self.name)
        print("Username:", self.username)
        print("Bio:", self.bio)
        print("Skills:", ", ".join(self.skills))

if __name__ == "__main__":
    name = "Uttiyo Manna"
    username = "uttiyomanna"
    bio = "Beginner Python coder exploring the world of programming!"
    skills = ["Python", "Programming Basics", "Problem Solving"]
    
    uttiyo_profile = GitHubProfile(name, username, bio, skills)
    uttiyo_profile.create_profile()

<!---
uttiyo94/uttiyo94 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

class Developer:
    def __init__(self):
        self.name = "Nandan H M"
        self.location = "Mysore, Karnataka, India"
        self.education = "BCA @ BGS First Grade College (CGPA: 8.76/10)"
        self.role = ["Python Full Stack Developer", "Software Developer", "Web Developer"]
        self.skills = ["Python", "SQL", "Full Stack Development", "AI & ML"]
        self.languages = ["Kannada", "English", "Hindi"]
        self.status = "Open to opportunities 🚀"

    def about(self):
        return ("Motivated BCA graduate with practical experience in SQL and "
                "Python Full Stack development, passionate about building "
                "AI-powered, real-world applications.")

me = Developer()
print(me.about())

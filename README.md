class Alinsha:
    def __init__(self):
        self.name           = "Alinsha S"
        self.location       = "Kollam, Kerala, India"
        self.degree         = "B.Tech Computer Science Engineering (2026)"
        self.university     = "College of Engineering Kottarakara, KTU"

        self.stack = [
            "Python", "C", "SQL",
            "HTML", "CSS", "JavaScript",
            "Figma", "Canva",
            "Solidity", "Web3.js", "MySQL"
        ]

        self.currently_learning = [
            "React.js",
            "Blockchain Development",
            "Machine Learning & NLP"
        ]

        self.fun_fact = "I design UIs in Figma before writing a single line of code 🎨"

    def motto(self):
        return "Combining creativity and technology for innovative solutions 🚀"

me = Alinsha()
print(me.motto())

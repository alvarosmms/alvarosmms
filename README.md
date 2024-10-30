# Bio de GitHub: Nivel Principiante 🚀
class Aprendiz:
    def __init__(self):
        self.nombre = "Álvaro"
        self.skills = ["🐍"]
        self.hobbies = ["📸","🏖️","📺"]
        self.paciente = False  # ¡Todavía falta trabajo en la paciencia! 🙄
        self.objetivos = ["aprender", "no romper nada... mucho", "tomar café ☕ "]

    def progreso(self):
        return f"{self.nombre} está aprendiendo a programar... ¡Paciencia={self.paciente}! 🍀"

yo = Aprendiz()
print(yo.progreso())

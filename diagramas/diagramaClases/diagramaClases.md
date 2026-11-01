class Usuario {
}

class Secretaria {
}

class Actividad {
}

class Inscripcion {
}

class Acreditacion {
}

Usuario <|-- Estudiante : Es un
Usuario <|-- Secretaria : Es un

Estudiante "1" -- "0.." Inscripcion : realiza >
Actividad "1" -- "0.." Inscripcion : oferta >
Inscripcion "1" -- "0..1" Acreditacion : genera >
Secretaria "1" -- "0.." Actividad : administra >
Secretaria "1" -- "0.." Estudiante : supervisa expediente >
﻿

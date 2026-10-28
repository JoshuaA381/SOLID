el código cumple DIP porque AdmProducto (alto nivel) y EnviarEmail/EnviarApp (bajo nivel) no se conocen entre sí, ambos dependen de la abstracción EnvioRecibo, y la elección de la implementación concreta se hace fuera (en main) y se inyecta como puntero a la abstracción


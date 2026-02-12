# Ejercicio-Propuesto-No-17
import math

class Calculos:
    @staticmethod
    def calcular_longitud_circunferencia(radio):
        # Usamos math.pi para obtener el valor de PI
        return 2 * math.pi * radio

    @staticmethod
    def calcular_area_circulo(radio):
        # Usamos math.pi y el operador ** para elevar al cuadrado
        return math.pi * math.pow(radio,2)

radio = 3.0

# Llamada a los métodos estáticos
longitud_circunferencia = Calculos.calcular_longitud_circunferencia(radio)
area_circulo = Calculos.calcular_area_circulo(radio)

# Imprimimos los resultados con f-strings
print("Longitud circunferencia: ", longitud_circunferencia)
print("Área círculo: ", area_circulo)

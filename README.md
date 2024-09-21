# Practica-4-strings
print(" ")
print("Angel Andrey Muñoz Centeno 3W: strings")
print(" ")
def main():
    print("¡Bienvenido al programa de manipulación de strings!")
    user_input = input("Por favor, ingresa un texto: ")

    while True:
        print("\n¿Qué te gustaría hacer con el texto?")
        print("1. Convertir a mayúsculas")
        print("2. Convertir a minúsculas")
        print("3. Contar caracteres")
        print("4. Reemplazar una palabra")
        print("5. Invertir el texto")
        print("6. Salir")

        choice = input("Elige una opción (1-6): ")

        if choice == '1':
            print("Texto en mayúsculas:", user_input.upper())
        elif choice == '2':
            print("Texto en minúsculas:", user_input.lower())
        elif choice == '3':
            print("Número de caracteres:", len(user_input))
        elif choice == '4':
            old_word = input("Ingresa la palabra a reemplazar: ")
            new_word = input("Ingresa la nueva palabra: ")
            print("Texto modificado:", user_input.replace(old_word, new_word))
        elif choice == '5':
            print("Texto invertido:", user_input[::-1])
        elif choice == '6':
            print("¡Hasta luego!")
            break
        else:
            print("Opción no válida. Por favor, elige un número entre 1 y 6.")

if __name__ == "__main__":
    main()
    ![image](https://github.com/user-attachments/assets/5bcf4d4e-5a2e-4946-8f20-a20bd1fd13e0)

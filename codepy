import pyttsx3

if __name__ == '__main__':
    engine = pyttsx3.init()
    print("Welcome to Robo Speaker 1.1 created by Ams")
    while True:
        x = input("Enter what you want me to say: ")
        if x.lower() == "quittt":  # Case-insensitive check
            print("Goodbye!!")
            break
        engine.say(x)
        engine.runAndWait()

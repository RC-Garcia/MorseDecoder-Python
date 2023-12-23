MORSE_CODE_DICT = {
    'A': '.-', 'B': '-...', 'C': '-.-.', 'D': '-..', 'E': '.', 'F': '..-.',
    'G': '--.', 'H': '....', 'I': '..', 'J': '.---', 'K': '-.-', 'L': '.-..',
    'M': '--', 'N': '-.', 'O': '---', 'P': '.--.', 'Q': '--.-', 'R': '.-.',
    'S': '...', 'T': '-', 'U': '..-', 'V': '...-', 'W': '.--', 'X': '-..-',
    'Y': '-.--', 'Z': '--..',
    '1': '.----', '2': '..---', '3': '...--', '4': '....-', '5': '.....',
    '6': '-....', '7': '--...', '8': '---..', '9': '----.', '0': '-----',
    ' ': '/'
}

def decode_morse_code(morse_code):
    morse_code = morse_code.strip().split(' ')
    decoded_message = ''
    for symbol in morse_code:
        for key, value in MORSE_CODE_DICT.items():
            if symbol == value:
                decoded_message += key
    return decoded_message

if __name__ == "__main__":
    # Example Morse code
    morse_code_input = "... --- ..."
    decoded_message = decode_morse_code(morse_code_input)
    print(f"Decoded Message: {decoded_message}")

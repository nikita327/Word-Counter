# Word-Counter
def count_words(text):
    words = text.split()  
    return len(words)  

def main():
    print("\n===== Word Counter Program =====")
    user_input = input("Enter a sentence or paragraph: ").strip()
    if not user_input:
        print("Error: No input provided. Please enter valid text.")
        return
    word_count = count_words(user_input)
    print("\n===== Results =====")
    print(f"Total Word Count: {word_count}")

if __name__ == "__main__":
    main()

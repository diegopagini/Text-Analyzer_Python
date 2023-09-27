# Text-Analyzer_Python

```python
text = input("Enter your text: ")
letters = []
text = text.lower()

letters.append(input("Enter the first character: ").lower())
letters.append(input("Enter the second character: ").lower())
letters.append(input("Enter the third character: ").lower())

print("\n")
print("Number of letters")
number_of_letters_1 = text.count(letters[0])
number_of_letters_2 = text.count(letters[1])
number_of_letters_3 = text.count(letters[2])
print(f"The letter '{letters[0].upper()}' has being found {number_of_letters_1} times.")
print(f"The letter '{letters[1].upper()}' has being found {number_of_letters_2} times.")
print(f"The letter '{letters[2].upper()}' has being found {number_of_letters_3} times.")

print("\n")
print("Number of words")
words = text.split()
print(f"The number of words is: {len(words)} in your text.")

print("\n")
print("Start and end letter")
start_letter = text[0]
end_letter = text[-1]
print(f"The start letter is: '{start_letter}' and the end letter is: '{end_letter}'.")

print("\n")
print("Reversed text")
words.reverse()
inverted_text = ' '.join(words)
print(f"If we order your text backwards they read like this: '{inverted_text}'")

print("\n")
print("Searching 'Python'")
is_python = 'python' in text
dic = {True: "exists", False: "not exist"}
print(f"The word 'Python' {dic[is_python]} in your text")
```

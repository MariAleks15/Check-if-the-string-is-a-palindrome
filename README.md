def is_palindrome(s):
    return s == s[::-1]

# Получаем строку от пользователя
string = input("Введите строку: ")

if is_palindrome(string):
    print(f"'{string}' является палиндромом.")
else:
    print(f"'{string}' не является палиндромом.")
# Check-if-the-string-is-a-palindrome
This code checks if the string entered by the user is a palindrome (reads the same both ways).

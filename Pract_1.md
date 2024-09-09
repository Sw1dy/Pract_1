# Задание 1
cat > passwd

![изображение](https://github.com/user-attachments/assets/4816089c-8aac-45b7-9f73-07be90e763ab)

grep -i '[a-z]' passwd | sort

![изображение](https://github.com/user-attachments/assets/a4bf1db4-6ac1-4a36-ae45-a1dd021cc773)

# Задание 2
cat /etc/protocols | awk '{print($2, $1)}' | sort -nr | head -5

![изображение](https://github.com/user-attachments/assets/66482b27-8486-4177-b8c9-832a202950dd)

# Задание 3

word = raw_input()
lw = len(word)
print("+" + "-"*lw + "+")
print("|" + word + "|")
print("+" + "-"*lw + "+")

![изображение](https://github.com/user-attachments/assets/aa1a5426-8557-448b-9a0a-ed2c927f5c67)



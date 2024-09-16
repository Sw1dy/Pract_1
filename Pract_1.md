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

# Задание 4

import re

def extract_identifiers(code):
    identifier_pattern = r'\b[a-zA-Z_][a-zA-Z0-9_]*\b'

    identifiers = re.findall(identifier_pattern, code)

    unique_identifiers = set(identifiers)

    return unique_identifiers

def main():
    cpp_code = """
    #include <iostream>
    using namespace std;

    int main() {
        int a = 5;
        int b = 10;
        int sum = a + b;
        cout << "Sum: " << sum << endl;
        return 0;
    }
    """

    unique_identifiers = extract_identifiers(cpp_code)

    for identifier in unique_identifiers:
        print(identifier)

if __name__ == "__main__":
    main()


![изображение](https://github.com/user-attachments/assets/73d6a939-d1eb-469c-bf58-642201891028)

# Задание 5
#!/bin/bash

file=$1
chmod 755 "./$file"
sudo cp "$file" /usr/local/bin/
echo "Программа '$file' сохранена в usr/local/bin/, права были выданы"

![изображение](https://github.com/user-attachments/assets/dbb07869-b7d9-4723-93d1-8e2054bf9a79)


# Задание 6
![изображение](https://github.com/user-attachments/assets/d66cc68a-13d6-47d6-a324-7232697c10bc)



 
![изображение](https://github.com/user-attachments/assets/27a9c16d-8c2e-48e4-9c22-df71e25ad257)

# Задание 7
![изображение](https://github.com/user-attachments/assets/110ed8d5-3679-4ee8-ab1e-5f7c4db3cd20)

![изображение](https://github.com/user-attachments/assets/274a61b2-46bb-4a8a-8874-312ed85c7770)


![изображение](https://github.com/user-attachments/assets/b3966c94-3c99-4882-bbf0-51b81d27692c)

# Задание 8
![изображение](https://github.com/user-attachments/assets/d0c8d85e-e0c0-4297-892e-053ffa46fc39)

![изображение](https://github.com/user-attachments/assets/66a379f9-d6e5-41f3-b128-c0ebd0cda836)
# Задание 9
![изображение](https://github.com/user-attachments/assets/b67c166f-b776-43ce-9e6f-7c6803884df0)

![изображение](https://github.com/user-attachments/assets/0dce0da5-3bc9-4763-8592-985a22344536)










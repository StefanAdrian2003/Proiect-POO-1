# 📚 Simple Library Management System in C++

This is a basic C++ console application that simulates a library management system. It allows users to register, borrow books, and return them. The program tracks book availability and the number of books each user has borrowed.

## 🚀 Features

- **Add books** to the library  
- **Register users**  
- **Borrow books** (only if available)  
- **Return borrowed books**  
- **Track** number of books borrowed per user  
- **Display informative messages** for each operation  

## 🧱 Structure

- **`Carte`**: Represents a book with title, author, and availability.  
- **`Utilizator`**: Represents a user with name and count of borrowed books.  
- **`Biblioteca`**: Manages collections of books and users; handles lending/returning logic.  
- **`main()`**: Demonstrates usage by creating books, users, and simulating various operations.  

## 📝 Sample Output

> The following output is a simulation of the program's execution:

```text
Cartea Ultima noapte de dragoste, intaia noapte de razboi a fost imprumutata de Laura. (Carti imprumutate in total: 1)
Cartea Comuniune a fost returnata de Stefan. (Carti imprumutate in total: 1)
Cartea Paradis a fost returnata de Elena. (Carti imprumutate in total: 0)
Cartea nu a fost imprumutata sau nu exista.
```

## ⚙️ How to Run

Compile and run the program using any modern C++ compiler:

```bash
g++ -o biblioteca biblioteca.cpp
./biblioteca
```

## 🧠 Concepts Used

- **OOP**: Encapsulation, constructors, class interaction  
- **Vectors** for dynamic storage  
- **Input/output and conditionals**  
- **Separation of concerns** across classes  

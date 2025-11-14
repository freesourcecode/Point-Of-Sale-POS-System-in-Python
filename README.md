# Point Of Sale [POS] System in Python with Source Code

The **Point Of Sale in Python** is a system that was created in Python programming language, Python is very easy to research the syntax emphasizes readability and it is able to reduce time ingesting in developing.

In this tutorial, I will Teach you How To make a Point of Sale System in Python, nowadays python programming is more well-known than other programming languages.

This article is ideal for beginners or student who wants to learn Python programming.

To start developing this simple point-of-sale system in Python, I will be using Pycharm IDE for this project.

By the way, if you are new to Python programming and don’t know what would be Python IDE to use, I have here a list of the **[Best Python IDE for Windows, Linux, and Mac OS](https://itsourcecode.com/blogs/best-python-ide-for-windows-2021/)** that will suit you.

I also have here **[How to Download and Install Latest Version of Python on Windows](https://itsourcecode.com/blogs/how-to-download-and-install-latest-version-of-python-on-windows-2021/)**.

## What is a Point of Sale (POS) System in Python?

A **Point-of-Sale (POS) System** lets your business take payments from customers and track sales transactions. 

It sounds easy, but there are different ways to set it up depending on whether you sell online, in a storefront, or both. 

A store’s cash register was once called a point-of-sale system.

## How to Make a Point of Sale System in Python?

1. **Create a project name**.

First, you will click the “File” After that create your project name and then click the “Create” button.

2. **Create a python file**.

Right-click the “project name” and click “New” and then create a “python file”.

3. **Name the python file**.

In the Python file window, name the file “cashiering” and then click “Enter.”

4. **Now you can start coding**.

In this step, you are now free to code on your “python file.”

5. **The actual code to be applied to your file**.

You are free to apply this code to your project. In that code given below, which declares the class and method of the system and its variable name to be called in public.

6. **Ordering method**

This method displays the listing of the menu that you want to order.

7. **Display Results**

8. **Payment method**.

This method displays the total purchases of the customer and the customer’s cash and their change.

9. **Final Output**

## Complete Source Code of Point of Sales System in Python

You can copy and execute the code of this Python point-of-sale tutorial to your computer.

```
class cashieringsystem:

    def __init__(self, a=0, r=0,recieve=0,change=0,temp=0):

        print("\n\n*****WELCOME TO SIMPLE CASHIERING SYSTEM*****\n")

        self.a = a
        self.r = r
        self.recieve = recieve
        self.change = change
        self.temp = temp

    def foods(self):

        print("*****JUDE'S RESTAURANT MENU*****")

        print("1.Adobo----->30", "\n2.Nilaga----->35", "\n3.Pork Chop--->50", "\n4.Letchon Paksiw---->40","\n5.Cash Out", "\n6.Exit")

        while (1):

            c = int(input("Choose:\n"))

            if (c == 1):

                d = int(input("Enter the quantity:\n"))
                self.r = self.r + 30 * d

            elif (c == 2):
                d = int(input("Enter the quantity:\n"))
                self.r = self.r + 35 * d

            elif (c == 3):
                d = int(input("Enter the quantity:\n"))
                self.r = self.r + 50 * d

            elif (c == 4):
                d = int(input("Enter the quantity:\n"))
                self.r = self.r + 40 * d

            elif (c == 5):
                print("total:", self.r)
                if (self.r > 0):
                    recieve = int(input("Input Money Recieve:\n"))
                    print("Change:",recieve - self.r)
                    print("*****Thank You Come Again!!!*****")
                    quit()
            elif (c == 6):
                quit()
            else:
                print("Invalid option")





def main():
    a = cashieringsystem()

    while (1):

            a.foods()





main()
```

### 📌 Here's the full documentation for the [Point Of Sale [POS] System in Python](https://itsourcecode.com/free-projects/python-projects/how-to-make-a-point-of-sale-system-in-python/)

### Related Articles
* **[POS in PHP with Free Source Code](https://itsourcecode.com/free-projects/php-project/pos-in-php-with-free-source-code/)**
* **[Point Of Sale (POS) In Java With Source Code](https://itsourcecode.com/free-projects/java-projects/point-of-sale-pos-in-java-with-source-code/)**
* **[Point Of Sale System Project in CodeIgniter](https://itsourcecode.com/free-projects/php-project/point-of-sale-system-project-in-codeigniter-with-source-code/)**
* **[Complete POS and Inventory System using VB.Net](https://itsourcecode.com/free-projects/vb-net/complete-pos-and-inventory-system/)**
* **[Point of Sale (POS) System UML Diagrams](https://itsourcecode.com/uml/point-of-sale-pos-system-uml-diagrams/)**








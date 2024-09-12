# Number-Exploration-Tool

## I did this project in serval steps

> > 0. Asking for user Name
> > 1. Asking for user three fav Numbers
> > 2. Collecting fav three number from user
> > 3. saving fav numbers in a list
> > 4. checking if the numbers are even or odd and storing the result in a new list of tuple
> > 5. Display the personalized greeting and even/odd information
> > 6. Creating a list of tuples containing each number and its square
> > 7. Calculate the sum of three numbers
> > 8. Determine if the number is prime number or not
> > 9. Printing Thank you message

#### Here is the code of my Project

````Markdown
```python


user_name = input("Enter Your Name ?")
print(f"Hey,{user_name}! Please Enter your fav three numbers")


favorite_numbers = []
for i in range(1, 4):
    number = int(input(f"Enter favorite number {i}: "))
     favorite_numbers.append(number)` ``


even_odd_info=[]
for num in favorite_numbers:
    if num % 2 == 0:
        print(f"{num} is even ")
    else:
        print(f"{num} is odd ")



print(f"Nice to meet you {user_name}, here are the information of number you give if they are even or odd")
for number, status in  even_odd_info:
    print(f"{num} is {status}")


print("\nLet's see the square of numbers")
squares = []
for num in favorite_numbers:
    square_tuple = (num,num**2 )
    squares.append(square_tuple)
    print(f"{num} square is {square_tuple[1]}")


total_sum = sum(favorite_numbers)
print(f"\n the sum of three numbers is {total_sum}!")
print("That's a awesome number, isn't it.")


def is_prime(n):
    if n <= 1:
        return False
    for i in range(2,int(n**0.5)+1):
        if n % i ==0:
            return False
        return True

if is_prime(total_sum):
        print(f"Wao, {total_sum} it's a prime number! that's really great.")
else:
        print(f"Ohh, {total_sum} is not a prime! but it's still nice and great.")

print(f"\nThank you {user_name} hope you enjoy finding for fav number")

```
````

### You can also test my project by clicking on this link

[Number-Exploring-Tool](https://github.com/Abubakarshah1/Number-Exploration-Tool.git)

### Pasting image for practice

[image-of-coding-adding-just-for-practice](![alt text](https://media.istockphoto.com/id/1403644222/photo/illustration-demonstrates-the-routing-of-ip-packets-throughout-the-internet-a-lan-computer.jpg?s=612x612&w=0&k=20&c=MCdnCecf2rfzLnsnivu5DOXL-6Ata-Sq6MGLvmXngPc=))

### image 2 pasting as a link tab to see

[coding image](https://media.istockphoto.com/id/1413990965/photo/glowing-python-programming-language-code-on-a-blue-digital-surface-with-a-sphere-grid-design.jpg?s=612x612&w=0&k=20&c=sC5Gcktg85_J6e50P5DGngrez1MElLql5xrYKd13sA4=)

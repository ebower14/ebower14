### Welcome

<!--
**ebower14/ebower14** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
### Cybersecurity 2027

Java Programming

```
import java.util.Scanner;
 
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
 
        // Ask user for quantity
        System.out.print("Please, enter the quantity: ");
        int quantity = scanner.nextInt();
 
        // Ask user for price
        System.out.print("Please,enter the price per item: ");
        double price = scanner.nextDouble();
 
        // Calculate the total cost
        double totalCost = quantity * price;
 
        // Display the total cost
        System.out.println("Total cost: " + totalCost);
 
        // Close the scanner
        scanner.close();
    }
}
 
```
C++ initial input assignment
```
#include <iostream>

using namespace std;

int main() {
    char firstInitial, lastInitial;
    
    std::cout << "Please enter your first initial followed by your last initial: \n";
    
    cin >> firstInitial >> lastInitial;
    
    std::cout << "Your initials are: \n" << firstInitial << lastInitial << endl;
    
    return 0;
}
```

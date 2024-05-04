# Dependency Inversion

The NEU Library offers a variety of resources, including books, theses, capstones, internet access, journals, and newspapers.

Currently, the Student object has methods like borrowBook(), borrowJournal() with a parameter of title, which directly depend on specific resource types.

To adhere to the Dependency Inversion Principle (DIP) and ensure flexibility for future changes (such as introducing audio books or e-journals), we need to refactor the program while maintaining SOLID principles. The goal is to create a robust system that can seamlessly accommodate new resource types in the future.

Your solution should not violate other SOLID principles.

## Proposed Solution

![Uml Image](https://media.discordapp.net/attachments/1024219092611239936/1236105554582175784/LAB_Assignment7_Ramos_Arvyx_2BSCS-1.png?ex=6636cc81&is=66357b01&hm=449f6e05dfc7326d40c7b4f56e80620adadccd7c2da90e9c1d266e76da8e19d5&=&format=webp&quality=lossless&width=930&height=603)
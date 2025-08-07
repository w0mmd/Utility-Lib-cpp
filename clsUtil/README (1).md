# clsDate

A lightweight C++ date manipulation library featuring a custom `clsDate` class.  
Created as a personal project for learning and utility purposes.

---

## 🔧 Features

- Custom `clsDate` class for representing and manipulating dates  
- Add or subtract days, months, and years  
- Compare dates easily  
- Format dates as readable strings  
- Beginner-friendly and lightweight  

---

## 📂 Project Structure

```
clsDate/
└── include/
    └── clsDate.h   # Header file with the clsDate class
```

---

## **Example Usage**

```cpp
#include "clsDate.h"
#include <iostream>

int main() {
    clsDate today(2025, 8, 7);
    clsDate futureDate = today.addDays(30);
    std::cout << today.toString() << "\n";
    std::cout << futureDate.toString() << "\n";
    return 0;
}
```

---

## 📖 How to Use

1. Include the `clsDate.h` header in your project.
2. Make sure to also include the `clsString` library, as `clsDate` depends on it.
3. Use the `clsDate` class and its methods for date operations.

---

## 🧩 Dependencies

This library depends on the custom [`clsString`](https://github.com/YourUsername/String-Lib-cpp) library for internal string handling.  
Make sure to include and link `clsString` in your project if it's not already part of your codebase.

---

## 🔄 Related Projects

- [clsString](https://github.com/YourUsername/String-Lib-cpp): A custom string manipulation library used internally by `clsDate`.

---

## 🤝 Contributing

Contributions are welcome!  
If you have suggestions, bug reports, or improvements, feel free to open an issue or submit a pull request.

---

## Contact

Created by Mohammad Alhamad — feel free to open issues or contribute!
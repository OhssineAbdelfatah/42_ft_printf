## ft_printf: Your Custom printf Function

**Tired of the limitations of standard printf?** 

This project empowers you to create your very own `ft_printf` function, replicating the functionality of the classic `printf` while potentially adding your own unique features! 

### Take Control of Formatting

Embrace the power to format output exactly how you desire! This project focuses on implementing essential format specifiers like:

* `%d`: Print integers
* `%s`: Print strings
* `%c`: Print characters
* `%p`: Print pointers
* (and potentially more!)

### Mastering ft_printf

This project serves as a stepping stone towards mastering formatted output. By implementing `ft_printf` yourself, you'll gain a deeper understanding of:

* Variable arguments
* Format string parsing
* Conditional printing based on format specifiers
* Memory manipulation (for handling strings and pointers)

### Getting Started

**Ready to unleash your inner printf pro?**

1. **Clone the repository:**

Utilisez ce code avec précaution.

git clone https://<your_github_username>@github.com/<your_username>/ft_printf.git


2. **Compile the project:**

make


3. **Link the library (if using in another project):**

   - Specify the path to the compiled library (`libftprintf.a`) during compilation of your main project.

### Usage

**Crafting your formatted output:**

Use `ft_printf` just like the standard `printf`:

```c
#include "ft_printf.h"

int main() {
  int num = 42;
  char str[] = "Hello, world!";

  ft_printf("The answer is %d\n", num);
  ft_printf("The greeting is %s\n", str);

  return 0;
}
```
This code will print:

```bash
The answer is 42
The greeting is Hello, world!
```
Bonus Round (Optional)

This project can be extended to implement additional functionalities not found in standard printf, pushing your formatting skills even further!
Contributing

Feeling inspired? We welcome contributions! Fork the repository and share your improvements through pull requests.

Let's build a powerful and versatile ft_printf together!

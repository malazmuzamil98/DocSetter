# DocSetter

## Description
This is made by an **ALX student** for **ALX students** who struggle with making *Doctests* for there python projects

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example](#Example)
- [Contributing](#contributing)
- [License](#license)


## installation

1. Clone the repository inside your project directory.

	```bash
	git clone https://github.com/AlWaleedMusa/DocSetter.git

## Usage
- ```bash
	$ python <main.py> <file.py>
- *file.py* : name of the module you have the function in that you want to test.

- If you need to add more tests just copy from (::) to the next (::) and past
it underneath your last test.

- Press and change the dots (...) to **YOUR** function requirement.
	*(Make sure to fill all the ...)*

- Error handling is at the end of the file.
	- Make sure to add (:) a colon after your Error name its a MOST.
	- Example:<br>
		Traceback (most recent call last):<br>
		ValueError: <--- *(if this colon is missing doctest will not process your code)*

## Example
- ```bash
	$ python <main.py> <0-add_integer.py>

- Folder **tests** created plus the **.txt** file created

![picture shows a new directory created](/images/tests_created.png)

- Here you can see a ready to edit blueprint of a doctest file with function name
	on the right placed and the file name too to be ready to import modules when tests are ran

![picture of a text file](/images/txt_file.png)


## Contributing

1. Fork the project.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.


## License

This project is licensed under the [MIT License](/LICENCE).

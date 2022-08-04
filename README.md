# HTML LINK PARSER

This program written in GoLang (following Jon Calhoun's Gophercise) will iterate through an HTML an parse every link with the attribute "href", returning this value and any text associated with it, in the form of a verbose slice of strings.

There are a few steps you must follow before using the program:

1. First, (and after you've clone the repo, of course), you must run the follwing command to initialize the link module implemented in parse.go, making its methods and typè available to each example.

```powershell
go mod init link
```

2. This program uses Go's the html package. Even though its a library developed by Go's engineers, it's not native to the program, so you must install it using the following command:

```
go get -u golang.org/x/net/html
```

3. Enjoy! Actually, here's how this works. Each directory in examples/ contains a main.go file, with an example HTML from which to parse the links. There are four examples ready, but if you want to test any other HTML, just assign it as a string to the exampleHtml variable inside main, and you're good to GO. Run the script by using this command:

```
go run examples/<example_directory_to_test(e.g.ex1)>/main.go  
```

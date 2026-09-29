# PHP Password Checker

A small PHP learning project that demonstrates common string functions by
displaying information about a sample password. See [`index.php`](index.php)
for the implementation.

## Why this project is useful

This example shows how to use PHP's built-in functions to:

- Measure a string's length and word count.
- Reverse a string.
- Find the position of a character.
- Replace characters in a string.

Despite its name, this is a string-functions demonstration, not a password
strength validator or authentication tool.

## Getting started

You need PHP with the command-line server enabled. No additional dependencies
or installation steps are required.

1. Clone this repository and change into its directory.
2. Start PHP's built-in development server:

   ```sh
   php -S localhost:8000
   ```

3. Open <http://localhost:8000> in your browser.

The page displays the sample password and the results of the string operations.
To try different input, edit the `$password` value in [`index.php`](index.php)
and refresh the page.

> **Note:** The example prints the password directly in the page. Do not enter
> real or sensitive passwords; this project is for learning only.

## Help and documentation

- For questions or bug reports, [open an issue](../../issues).
- Learn more about the PHP functions used here:
  [strlen](https://www.php.net/manual/en/function.strlen.php),
  [str_word_count](https://www.php.net/manual/en/function.str-word-count.php),
  [strrev](https://www.php.net/manual/en/function.strrev.php),
  [strpos](https://www.php.net/manual/en/function.strpos.php), and
  [str_replace](https://www.php.net/manual/en/function.str-replace.php).

## Maintainers and contributions

No maintainer or separate contribution guide is listed in this repository.
Contributions are welcome: open an issue to discuss a change, then submit a
pull request with a clear description of what it changes.

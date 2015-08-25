# code-generator

Generates a number of random codes in a given format.

Use "B" for a random letter and "1" for a random number in the format
string; all other characters will be left intact.

This project is written in Rust. It’s been tested on Rust 1.2.0.

It’s pretty fast, or at least plenty fast enough for our needs, thanks
to Rust being awesome. On a recent MacBook Pro it will write 10 million
unique codes to a file in around 10 seconds.

## Installation

1. Clone the repository
2. `cargo build`

## Usage

	code-generator NUM FORMAT

## Examples

	./code-generator 5 BB11BB11BB11
	RC93AL64EW63
	LA34YK47TE93
	HR74AP94LT49
	WX49XH39FR46
	LA63KC47PW34

	./code-generator 5 XX11BB11
	XX73LH46
	XX64HF77
	XX44FE74
	XX96YM39
	XX37FF67


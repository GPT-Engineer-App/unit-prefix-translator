# unit-prefix-translator

When the robot Algorithmius mentions a distance, area, or volume, it uses a multitude of prefixes from the International System of Units (SI). Each SI prefix multiplies the unit of measurement by a power of ten. For instance, Algorithmius might say “megananokilogigamicrometer,” which corresponds to 10^3 meters (10^6 * 10^-9 * 10^9 * 10^-6). When it comes to volume, it could say “millimeter^3,” which equals 10^-9 cubic meters.

Algorithmius employs the following prefixes:

tera: 10^12
giga: 10^9
mega: 10^6
kilo: 10^3
deci: 10^-1
centi: 10^-2
milli: 10^-3
micro: 10^-6
nano: 10^-9
The rules for applying prefixes to square and cubic measurements are also standardized. For example, one cubic meter equals 10^6 cubic centimeters.

Now, let’s write a program that will “decode” what Algorithmius said. It will translate the mentioned unit of measurement into meters, square meters, or cubic meters, depending on the magnitude of the output unit. It’s straightforward to demonstrate that you’ll end up with a value that equals 10^x (meters, square meters, or cubic meters), where x is an integer.

Input Format: The input consists of a single line containing the word spoken by Algorithmius. The length of the word does not exceed 105 characters. It is guaranteed that the word was formed by sequentially appending several prefixes from the table to “meter,” “meter^2,” or “meter^3.”

Output Format: Print an integer x such that if you convert the unit of measurement mentioned by Algorithmius to meters, square meters, or cubic meters, it will result in 10^x.

Examples:

Test Case 1:
Input: “meter”
Output: 0
Test Case 2:
Input: “kilometer”
Output: 3


## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/unit-prefix-translator.git
cd unit-prefix-translator
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

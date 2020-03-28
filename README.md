# Link Roulette

Input a list of links, and get a single link which will redirect to a random link

## Usage

1. Go here: https://joaker-public.s3.us-east-2.amazonaws.com/link-roulette/create/index.html
2. Add links
3. Press "Create Link Roulette"

Example:

- type https://www.bing.com (hit enter)
  => list now has "https://www.bing.com"
- type https://www.google.com (hit enter)
  => list now has "https://www.bing.com" and "https://www.google.com"
- hit "Create Link Roulette"
  => Generated link: https://joaker-public.s3.us-east-2.amazonaws.com/link-roulette/link/index.html?encoded=aHR0cHM6Ly93d3cuYmluZy5jb20=&encoded=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbQ==

Clicking that link will result in randomly being taken to the bing or google

## Installation

```bash
yarn i
yarn start
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

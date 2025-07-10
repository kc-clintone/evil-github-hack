# Evilgit

A playful Node.js script to automate random git commits with custom dates, inspired by the "contribution graph" effect.

## Description

This project generates a series of git commits with randomized dates over the past year, creating a pattern on your GitHub contributions graph. It uses `jsonfile` to write a date to a JSON file, `moment` for date manipulation, `random` for randomization, and `simple-git` to automate git commands.

## Usage

1. **Install dependencies:**

   ```sh
   npm install
   ```

2. **Run the script:**

   ```sh
   node index.js
   ```

   This will create 100 random commits spread over the past year.

## Files

- `index.js` - Main script to generate commits.
- `data.json` - Temporary file used for commit content.
- `package.json` - Project metadata and dependencies.
- `.gitignore` - Standard Node.js ignores.
- `LICENSE` - MIT License.

## Disclaimer

This project is for educational and entertainment purposes only. Please use responsibly and do not abuse automated commit generation.

## License

MIT © 2024 Harsh Mehta
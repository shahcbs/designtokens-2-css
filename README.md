# designtokens-2-css

This is a tool that takes a list of design tokens in a structured format such as JSON or YAML and converts them to a list of CSS preprocessor variables (Less, Sass/SCSS, and Stylus currently supported).

## Usage

With stdin/stdout:

```bash
cat tokens/*.json | token2css > output.css

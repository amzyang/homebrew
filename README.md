# Amzyang Homebrew

## How do I install these formulae?

`brew install amzyang/homebrew/<formula>`

Or `brew tap amzyang/homebrew` and then `brew install <formula>`.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## libedit

`brew install amzyang/homebrew/libedit`

### Using libedit

For M1

`env PKG_CONFIG_PATH="/opt/homebrew/opt/libedit/lib/pkgconfig" LDFLAGS="-L/opt/homebrew/opt/libedit/lib" CPPFLAGS="-I/opt/homebrew/opt/libedit/include" brew install --build-from-source php`

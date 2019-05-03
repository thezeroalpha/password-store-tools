# Export passwords to CSV
Run `./export-csv [outfile]`.
The passwords will be in `outfile`, in Chrome-style format.
So if you want to import into e.g. Bitwarden, select to import from Chrome.

# Check if passwords were compromised
Run `./pwnedpasswords`.
It'll show you which accounts have compromised passwords, along with the number of times they appear in the database.

# Check if a single password was compromised
Run `./pwnedpass`.
Either type in the password, or pipe it into the command.

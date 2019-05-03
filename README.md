# Export passwords to CSV
Run `./export-csv [outfile]`.
The passwords will be in `outfile`, in Chrome-style CSV format.
So if you want to import into e.g. Bitwarden, select to import from Chrome.

# Check if passwords were compromised
Run `./pwnedpasswords`.
It'll show you which accounts have compromised passwords, along with the number of times they appear in the database.

# Check if a single password was compromised
Run `./pwnedpass`.
Either type in the password, or pipe it into the command.

# Export Safari Passwords
Open `safari-export.csv` in Script Editor.
Close all Safari windows, go to Safari preferences, click on the 'password' tab.
Open a new plaintext file in TextEdit.

Replace "PASSWORD" with your Safari Passwords password (it's needed to unlock the passwords, they lock periodically).
Set "n_passwords" to the number of passwords you want to export.
Then click 'run' in Script Editor.

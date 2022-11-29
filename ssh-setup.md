# SSH Setup 2022-11-29 21:17

# Assumptions

Assumtion is SSH has been setup, I'll add some additional insutructions on how to do this at a later time.

## To get SSH working we need to run the following on my Mac.

1. `eval "$(ssh-agent -s)"` Use this command to start the ssh-agent. Should really add this into my .zshrc.
2. `ssh-add --apple-use-keychain ~/.ssh/id_ed25519_password` This adds the key into the Mac keychain.

We should had this information into our profile environment.

# Add public key onto target environment.

Next we need to add the public key onto the target environment. Simply put, we just need to send the output or
copy the output to where ever it needs to go. For example this could be **Github** or another server somewhere. 

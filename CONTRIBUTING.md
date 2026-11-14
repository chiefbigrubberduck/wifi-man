# Contributing
Welcome! Thanks for contributing. Follow the below workflow:          

- Open pull request
- Ask to merge
- Code will get reviewed

Please keep in mind:                                                                                                            
- Language/Translation is welcome!
- Do not use `set -euo pipefail` or any other variation, as the internal logic of wifi-man requires errors to correctly set variables.                                                                                         
- Please use clean syntax and uppercase named variables, so they are easily visible.                                            
- Always use a fallback alternative if the command fails, for example: `echo "Hi." || { echo "Echo failed... Exiting..."; exit; }`
- Integrate, keep it to one file, integrate edits or new features into the main file.

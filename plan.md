# Plan of operations

#### User-level vulnerability
We make a user named 'testuser' that can be found referenced in app.py.
The user is justified by saying that the user is only used by devs to check out new features.
That user will have insecure input fields and therefor is available for sql injection.
The password for testuser will not be stored in plaintext, but will have a SHA-256 hash that is stored in app.py as plaintext.
The password will be from the password list from learnit.
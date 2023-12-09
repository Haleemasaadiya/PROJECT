# PROJECT
# SECRET MESSAGE ENCRYPTION AND DECRYPTION TOOL
In My Project, the primary data structures used are:

    Variables:
        code is a StringVar used to store the password entered by the user.
        text1 is a Text widget used to input and display text messages.

    Strings:
        Strings are used to store and manipulate the user-entered password (password), the text messages (message, encrypt, decrypt), and other string literals used in the GUI.

    Lists/Tuples:
        There are no explicit uses of lists or tuples in the provided code. However, if you plan to expand the functionality, you might use lists or tuples to store multiple pieces of data.

    Message Boxes:
        messagebox from Tkinter is used to display error messages in pop-up boxes.

    Tkinter Widgets:
        Tkinter provides various widgets like Tk, Toplevel, Text, Label, Entry, and Button, which are used to create the graphical user interface.

    Dictionary (Potential):
# USES 
My Project is about a simple Tkinter-based Python application for text encryption and decryption. It creates a graphical user interface (GUI) with the following features:

    Main Screen:
        The main_screen function sets up the main application window (screen) with a specified size and title.
        It creates a text area (text1) for entering the text to be encrypted or decrypted.
        It adds labels, an entry field (code) for the secret key (password), and buttons for encryption, decryption, and resetting.

    Encryption Function (encrypt):
        Gets the password from the entry field.
        If the password is correct ("1234"), it opens a new window (screen1) for encryption.
        Encodes the entered text using ASCII encoding, then encodes it using base64.
        Displays the encrypted text in a text area.

    Decryption Function (decrypt):
        Gets the password from the entry field.
        If the password is correct ("1234"), it opens a new window (screen2) for decryption.
        Decodes the entered text using base64 and then decodes it using ASCII encoding.
        Displays the decrypted text in a text area.

    Reset Function (reset):
        Clears the password entry field (code) and the text area (text1).

    Tkinter Widgets:
        Utilizes various Tkinter widgets like Tk, Toplevel, Text, Label, Entry, and Button to create the GUI.

    Message Boxes:
        Uses the messagebox module from Tkinter to show error messages if the password is missing or incorrect.

    Styling:
        Applies background colors and font styles to different GUI elements for visual appeal.

    Event Handling:
        Associates the encrypt, decrypt, and reset functions with the corresponding buttons using the command parameter.

To use this application, you can run the script, and a window will appear with an interface to input text, a password, and perform encryption or decryption based on the provided password.

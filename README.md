# CONTACT_BOOK

This code appears to be a simple contact book application using the Tkinter library in Python. Here's a brief overview of the code:

1. The `home` function sets up the main window with labels, entry fields, and buttons for adding and searching contacts.

2. The `insert` function is triggered when the "Add" button is clicked. It retrieves the values entered in the entry fields (`e1`, `e2`, `e3`, and `e4`), writes them to a CSV file (`details.csv`), and then clears the entry fields.

3. The `retrive` function is triggered when the "Search" button is clicked. It reads the CSV file and searches for a contact with a matching name (`ent5`). If found, it displays the contact details in a new window using the `put_display` function. If not found, it displays a "NAME NOT FOUND" message.

4. The `put_display` function creates a new window to display the contact details or the "NAME NOT FOUND" message.

5. The `if __name__ == '__main__':` block ensures that the `home` function is called when the script is run.

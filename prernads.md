import tkinter as tk

# Create the main application window
app = tk.Tk()
app.title("Simple GUI Example")

# Function to be called when the button is clicked
def button_click():
    label.config(text="Button Clicked!")

# Create a button widget
button = tk.Button(app, text="Click Me", command=button_click)

# Create a label widget
label = tk.Label(app, text="Hello, GUI!")

# Pack the button and label widgets onto the window
button.pack()
label.pack()

# Start the main event loop
app.mainloop()

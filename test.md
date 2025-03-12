# anshu
import tkinter as tk

# Create the main window
root = tk.Tk()
root.title("Happy Birthday")
root.geometry("400x300")
root.configure(bg="lightyellow")

# Happy Birthday message
label_title = tk.Label(root, text="🎉 Happy Birthday! 🎉", font=("Arial", 18, "bold"), fg="purple", bg="lightyellow")
label_title.pack(pady=20)

# Shayari
shayari = """Zindagi ke har mod par khushi mile aapko,
Kabhi na ho dukh ka samna aapko,
Khushiyon se bhara rahe jeevan aapka,
Bas yahi dua hai hamari aapko!"""
label_shayari = tk.Label(root, text=shayari, font=("Arial", 12), fg="darkblue", bg="lightyellow", justify="center")
label_shayari.pack(pady=20)

# Run the application
root.mainloop()

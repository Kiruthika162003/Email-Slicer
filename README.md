# Email-Slicer
email = input("Enter Your Email: ").strip()
username = email[:email.index('@')]
domain = email[email.index('@') + 1:]
print("Your username is",username)
print("And your domain is",domain)

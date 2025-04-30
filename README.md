# Step 1: Read from the original file
with open('input.txt', 'r') as file:
    content = file.read()

# Step 2: Modify the content
modified_content = content.upper()  # You can replace this with any transformation

# Step 3: Write to a new file
with open('output.txt', 'w') as file:
    file.write(modified_content)

print("File has been read, modified, and written to output.txt.")

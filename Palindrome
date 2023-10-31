def is_palindrome(input_str):
    # Remove spaces and convert to lowercase for case-insensitive comparison
    cleaned_str = ''.join(input_str.split()).lower()
    
    # Compare the cleaned string with its reverse
    return cleaned_str == cleaned_str[::-1]

# Test the function
input_string = "A man a plan a canal Panama"
if is_palindrome(input_string):
    print(f"'{input_string}' is a palindrome.")
else:
    print(f"'{input_string}' is not a palindrome.")

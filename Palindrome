def is_palindrome(text: str) -> bool:
    # Clean string: convert to lowercase and keep only alphanumeric characters
    cleaned = "".join(char.lower() for char in text if char.isalnum())
    return cleaned == cleaned[::-1]


# Example usage
print(is_palindrome("A man, a plan, a canal: Panama"))  # Output: True
print(is_palindrome("Hello World"))  # Output: False

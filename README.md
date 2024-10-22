def calculation(a, b):
    # Calculate multiplication
    multiplication = a * b
    
    # Calculate division (handle division by zero)
    division = a / b if b != 0 else "Undefined (division by zero)"
    
    return multiplication, division

# Example usage:
result_mul, result_div = calculation(10, 5)
print(f"Multiplication: {result_mul}, Division: {result_div}")
